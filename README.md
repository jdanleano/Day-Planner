# Day Planner - Module 05 Challenge

## Mock Up

![This is a screenshot of my planner](./Assets/screenshot.jpg)

This is my completed code for the Module 05 challenge this week. We were given a task this week to make a calendar application that allows the user to save events for each working hour of the day using HTML and CSS powered by jQuery.

## User Story

```
AS AN employee with a busy schedule
I WANT to add important events to a daily planner
SO THAT I can manage my time effectively
```

The Acceptance Criteria is as follows:

## Acceptance Criteria

```
GIVEN I am using a daily planner to create a schedule
WHEN I open the planner
THEN the current day is displayed at the top of the calendar
WHEN I scroll down
THEN I am presented with time blocks for standard business hours
WHEN I view the time blocks for that day
THEN each time block is color-coded to indicate whether it is in the past, present, or future
WHEN I click into a time block
THEN I can enter an event
WHEN I click the save button for that time block
THEN the text for that event is saved in local storage
WHEN I refresh the page
THEN the saved events persist
```

What I did to complete this challenge is take each individual criteria one at a time, while also trying to minimize repetativeness in the code. I started with adding an input group and a button per timeblock. I then went on to start setting my classes and ids in order to link them to the values in the given CSS and my created JS file.

After I finished adding all the bootstrap components, I went on to add the variables and functions to the JS file. I started with linking Moment in the JS file, then made sure it displayed in the given jumbotron in the HTML. Then I added the variables to display the time in all the timeblocks. I then went to add the function to change the color of the timeblock based on the current time. Lastly I added the functions to save the input to localStorage, and sort the information to it's respective timeslot.


## Please see attached links to Repository and Deployed Page:
### https://github.com/jdanleano/Day-Planner
### https://jdanleano.github.io/Day-Planner/
