# Project:   
Text messaging service where students can send a text asking when the next assignment in 
a certain class is due and the student will receive an appropriate response. Professors 
will be able to update class assignment deadlines by sending out a text. 

# Questions:
1.	When would you use this application?
2.	How often would you use realistically this application?
3.	Why is this application better than Brightspace?
4.	What other info would you want?
5.	Would you want to see future assignments as well?
6.	Would you like to receive notifications?
7.	If you were a teacher/professor, what would be an incentive for you to use this application?
8.	Would you want to receive all class assignments or just a certain class? 
9.	Would you want a reminder text?
10. As a professor what other capabilities would you like this application to have? 


## Question 1:
1.	Whenever I’m getting ready to work on assignments so I can find out when my assignments are
2.	When I’m thinking of whatever class I have the next day, I’ll use this
3.	When I want to know what assignments I have due that week 

## Question 2:
1.	Once a day or once every other day, as many times as I have classes. 
2.	Daily
3.	Everyday so that I know if I have anything due the next day that I might have forgotten about

## Question 3:
1.	Easier to send a text and get a fast response then pulling out comp and logging into Brightspace to look at due date
2.	Brightspace is very cluttered, this is very straight to the point and I can get the answers I want faster
3.	Will get a response fast instead of clicking through a million webpages looking for what I want

## Question 4:
1.	Estimate of how long assignment will take, info about assignment, name of assignment, etc.
2.	Maybe something about how big this assignment is as a percentage of my total grade
3.	A description of the assignment would be nice to have in there as well, just in case I forgot what the assignment was. Any other information I can just get on Brightspace when I’m starting the assignment

## Question 5:
1.	Yes, maybe a weeks or months’ worth of assignments so I can plan out my time appropriately
2.	Sure, that would be fine. It would allow me to plan a little bit into the future. 
3.	It would be nice to have an option where I can see all my upcoming assignments in a certain class 

## Question 6:
1.	Yes, if a prof assigns an assignment I want to know that the assignment and its due date are up so that I can avoid procrastinating
2.	Notifications would be nice. 
3.	Having the option of receiving notifications for when a professor adds or edits an assignment deadline would be nice but u not necessary for this application

## Question 7:
1.	To make sure my students turn in my assignments or have to fail them
2.	For teachers it’s a way to get info into to students in as easier way. I’m on my phone way more than I’m on Brightspace and this would be a better platform for communication and would allow for less excuses regarding missed assignments. 
3.	Some professors truly do care about their students and would start using this service if students request it

## Question 8:
1.	Would like to have the option to do both
2.	Just a certain class but with a later option to opt in class by class 
3.	Just a certain class is enough, if I wanted to see more classes I could just more text messages. 

## Question 9:
1.	No, the point of this app is if I want to find out, I don’t need my phone telling me what to do
2.	Sure, it would be useful just in case I forget about something. 
3.	I can set reminders on Brightspace, I don’t really need this service to do that

## Question 10:
1.	Would want to be able to remove assignments, and have the ability to distribute grades to students 
2.	If a prof wants to send out a reminder or announcement it could be kind of like the Alert VU thing where you can reply yes or no if you’ve seen the message. 
3.	The ability to remove assignments or just send out the latest announcements that students can receive over texts would also be nice.


# Requirements:

## Objectives:
1. Make assignment deadlines easily available to students.
2. Students should be able to clearly see the deadline of the next assignment plus a short description of the assignment.
3. Professor should be able to update the upcoming assignment's deadline and description
4. Application should be setup so that future functionality can be easily added

## Functionality:
1. Need to make sure data send by teacher is properly stored in application.
2. Application needs to determine what class info to fetch based on input from student. 
    1. needs to handle invalid input or typos properly
    2. class identifier should be course number, such as "CS1101".
3. Automatic text sent to students when teacher makes an update to a current assignment.
4. Professor should be be able to link students phone #s to class.
5. Professor phone # should be linked to that class

# Development Approach:

The requirements for this application were derived from the interviewing of potential users.
Users wanted a very simple application that would simple show due date and short description 
of the upcoming assignments. While some users wanted more advances functionality, the general
audience wanted to keep the application simple and less cluttered. The core functionality will 
be built first, but the application will be designed so that more functionality can be easily added 
at a later date. 