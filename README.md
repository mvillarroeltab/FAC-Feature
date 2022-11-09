# FAC-Feature
A feature to include into my FAC application

## Introduction

I have decided that out of the three examples in the FAC promp that can be converted into features, I want to do something that will make sense and integrate seamlessly with my application webpage. My application webpage is a portfolio of sorts with the twist that, instead of showcasing exclusively my projects it is meant to showcase myself, helping the people at FAC to get to know me a bit better, and explaining my reasons for joining FAC and my progress so far. As someone used to laying out a page and designing, my application webpage is meant to be an exercise of order, which will showcase my (for now) limited talents in web design and combine it with an accessible, readable and hopefully beautiful design.

## Planning

While prompts such as 'a tortoise race' or 'a fortune teller' definitely spike my interest as a javascript challenge (for the fortune teller it comes to mind using a javascript object with different keys which would contain information about the fortune of each of the different cards); they do not seem to have a lot to do with my application webpage. A carousel has potential since one of the main and most important parts of my application web is the top image grid, which is meant to showcase me as a person, my likes and dislikes.

A carousel would give me the opportunity to showcase each of these images independently, and use javascript to bring the attention of the user to it. I would like it to be interactive as well, so the user has an opportunity to discover more about me from each image.

### *The bones and basic functionality*

In the first instance, I want my carousel to replace the image grid that is at the top of the page. I also want the page to redirect the user automatically to it once a set amount of time has passed in the webpage. I will use 'setTimeout()' method for a function to be triggered once the set amount of time has passed. The function will use the classList property of the grid element to hide it, and again use the classList property of the carousel to show it (carousel will be hidden by default).

The carousel basic structure will be:
  1.`<div>` containing other `<div>`s with the image slides.
  2.`<div>` containing the bottom 'dots' to indicate the navigation of each image.


## Building

## De-bugging
