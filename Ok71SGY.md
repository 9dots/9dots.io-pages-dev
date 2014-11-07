---
author: danleavitt0
views: 0
published: true
type: lesson
title: Title
blurb: "This lesson provides an introduction to robotics and specifically the engineering side of building a robot. To start, students will learn about engineers and watch a brief video about the process of engineering. Students will then build a robot using the instructions provided in the attachments."
org: 9dots
objective: 
  - One
  - two
  - Three
id: "9dots-Ok71SGY"
image: "http://uploads.9dots.io/OkyaANf_md.jpg"
fullImage: "http://uploads.9dots.io/OkyaANf_lrg.jpg"
attachments: 
  - path: "http://uploads.9dots.io/Okg5PsZ.pdf"
    name: LittleBitsBrainstorm.pdf

---

By the end of the lesson, students will be able to define a structural wall and demonstrate learning by creating a sturdy #tower capable of holding weight.
## Lesson Overview

## Setup

### Materials:

- Lego Mindstorm kit (with Touch Sensor)
- Computer with EV3 software
- Example touch sensor attachment
- Iteration and wrap-up handout

### Project Time:

- 45 minutes

## Engage
Relate human senses to robotic sensors and discuss how those senses can be used to react to external stimuli. Then, explain the goal for this lesson.

1. Discuss with students how people use their senses to react to their environment.
	- _What do people do if they bump into a wall?_
		Answers should include: stop walking, turn around, or back up.

	- _Which of your senses do you use to know that you are touching the wall?_
		The sense of touch is how a person knows that they have run into a wall.

2. Explain that the robot uses sensors to mimic human senses and allow it to react to its surroundings.
	- The touch sensor can let the robot know when it has run into a wall.

2. The goal of the day will be to make a robot that can run into as many walls as possible in 1 minute.

## Explore
Review the definition of an attachment for a robot and then give students time to create a touch sensor attachment.

1. This attachment will not be used at the same time as their push attachments. Different attachments are used to solve different problems.

2. Students have ten minutes to attempt to attach the touch sensor to their robot. The touch sensor should be connected to the front of their robot so that when it runs into a wall it will get pressed.

## Explain
Start out by reviewing what they already know about programming the robot. Then, discuss what behaviors are necessary to accomplish the goal for today. Finally, show them how to program those behaviors and play a game to reinforce learning.

1. Revisit the options associated with the move block that they learned previously, specifically the steering and the duration.
![](http://uploads.9dots.io/OiQh9jS_md.jpg) 

2. To accomplish the goal for today there are four necessary behaviors:

    1. Make the robot move forward forever
    2. Wait for the touch sensor to be activated
    3. Turn
    4. Repeat steps 1-3

3. To accompish the first behavior the duration on the move block must be changed to **on**. This makes the robot move for an unlimited amount of time like referenced in the image below.
![](http://uploads.9dots.io/OiQhIX8_md.jpg) 

4. The Wait block means that we continue whatever comes before the block until the touch sensor gets pressed.
![](http://uploads.9dots.io/OiQj0Nu_md.jpg) 

5. Students will remember from the previous lesson to use the Move Steering block to turn.

6. The Loop block means that any blocks within the loop are repeated forever.
![](http://uploads.9dots.io/OiQjPzY_md.jpg) 

7. Play a game of Mindstorm Says. To play, draw the programming blocks onto pieces of paper. Tape the paper in different orders to review with the students what each programming block accomplishes. Sample rules are:

    - **Move block:** Walk in place.
        - For each rotation specified the students take 1 step.
        - If the paper says unlimited the students continue to walk in place until told otherwise.
    - **Wait block with touch sensor:** A tap on the head activates the student’s touch sensor. Students will now move on to the next step in the program.
    - **Loop:** Any parts of the program that are between the start and end of loop pages should be repeated until the teacher says to stop.
![](http://uploads.9dots.io/OiQkWO7_md.jpg) 
**In the example above, students would take 2 steps, wait to be tapped on the head, and then repeat that process until they are told the program is finished.**

8. Check for understanding by asking some follow up questions.

	- _How can using the wait block help them to achieve their goal?_
    
	By combining the move block with the wait block, the students can program their robot to move forward indefinitely until the touch sensor is triggered.
![](http://uploads.9dots.io/OiQnPLd_md.jpg) 

	- _How can the loop block be utilized?_
	
    The loop can ensure that their robot continues to bounce off walls continuously without having to restart the program. Anything inside of the loop will be repeated forever (or until the ‘stop’ button is pushed on the robot).
![](http://uploads.9dots.io/OiQnT0b_md.jpg) 

## Elaborate
This time will be used to program the robot and add final touches to the touch sensor attachment that is connected to the robot.

1. Each group now has 35 minutes to finish building an attachment and program the robot to bounce off as many walls as possible in 1 minute. 

2. Students can test their robots at any point during the building time.
	- After each attempt, students should write down what worked and what they should change using the iteration log handout. 

## Evaluate
Students will test their programs by competing in a game of Mindstorm Pinball (the rules are listed below). When they have finished, students will discuss their engineering designs and fill out the robotics wrap-up handout.

1. At the end of the allotted time, students will test their robots by playing a game of Mindstorm Pinball.  To play, create a square playing area with walls on all four sides.  Place the robot in the center and set a timer for 1 minute. Points will be awarded for each wall that the robot can touch within that time limit.
  - 1st time bouncing off of a wall: 10 points
  - 2nd time bouncing off of the same wall:  5 points
  - 3rd + time bouncing off of the same wall: 1 point
  - 50 bonus point each time all four walls are hit

2. Discuss with students, "_How important was the placement of the touch sensor?_"
	The placement of the the touch sensor is very important because if it is not in a place where it will get bumped, the robot will not be successful.

3. Students will fill in the robotics wrap-up handout.
