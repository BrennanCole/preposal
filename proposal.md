# Proposal

## What will (likely) be the title of your project?

Sign Language to Text using Mediapipe and Machine Learning Algorithms

## In just a sentence or two, summarize your project. (E.g., "A website that lets you buy and sell stocks.")

A small program that takes input via the webcam and uses motion capture to determine signs and turns them into text.

## In a paragraph or more, detail your project. What will your software do? What features will it have? How will it be executed?

This software takes a video input using pythons cv2 module, then takes that video input and uses mediapipe's motion capture software to translate movements into verticies and points. These points will then be fed into a machine learning module that will attempt to translate them using a specially made dataset into asl phrases. From here this data will be output into a text box, that should run along side the program in a specifically made UI. If everything goes according to plan,
this program should be able to be exectued as a .exe file that can be delivered. I also hope to add a settings menu that will change the video feed according to need, a developer mode where the vectors and machine learing guesses are displayed for easy trouble shooting. It's pretty simple in theory but in practice the main issue has been working with the data. 

## If planning to combine 1051's final project with another course's final project, with which other course? And which aspect(s) of your proposed project would relate to 1051, and which aspect(s) would relate to the other course?

N/A

## If planning to collaborate with 1 or 2 classmates for the final project, list their names, email addresses, and the names of their assigned TAs below.

Andrew Tran,tuo19727@temple.edu, Zhenyu Zhao

Ryan Elizabeth Stanton,tuo53772@temple.edu ,Zhenyu Zhao

## In the world of software, most everything takes longer to implement than you expect. And so it's not uncommon to accomplish less in a fixed amount of time than you hope.

### In a sentence (or list of features), define a GOOD outcome for your final project. I.e., what WILL you accomplish no matter what?

A simple program with a basic UI that functions a solid 75% of the time. Basic text output.

### In a sentence (or list of features), define a BETTER outcome for your final project. I.e., what do you THINK you can accomplish before the final project's deadline?

Functions 95% of the time, UI is slightly more ironed out, more functions availible for input.

### In a sentence (or list of features), define a BEST outcome for your final project. I.e., what do you HOPE to accomplish before the final project's deadline?

Fully indepent program with flushed UI, settings menus. Functions 99% of the time. Full library of asl gestures availible for input.

## In a paragraph or more, outline your next steps. What new skills will you need to acquire? What topics will you need to research? If working with one of two classmates, who will do what?

I will be researching machine learning models, how to process data using the cv2 module, building a functional UI in python, and any other various modules and processes that come up during the course of designing and building this program. We've decided after building the base model, I will be focusing on the machine learning module, and making it as effective and efficient as possible. Ryan will be focusing on building the UI, using PySimpleGUI, and Andrew will focus on data collection and management. The next step in my case is figuring out the best machine learning model and processes to get the program functioning at full efficacy.
