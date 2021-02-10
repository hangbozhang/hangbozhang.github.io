---
layout: essay
type: essay
published: true
title: walking on the ruler
# All dates must be YYYY-MM-DD format!
date: 2021-02-10
labels:
  - coding standards
  - JavaScript 
  - ESLint
---

<img class="ui image" src="../images/ruler.jpg">

Let me start with asking a simple question: what takes least time to walk from location A to location B regardless any obstacles? The answer will be the straight line connects location A and B basic math concept. While we draw that straight line, we will need the tool ruler to help as straight line is not part of human natural. Same applies to the walking problem. Ideally, we will need a huge ruler that can connect A and B to walk on, so we do not get off route. 

The coding standards are just like ruler mentioned above. It served the same purpose of helping lead from point A (the intention of the code) to point B (the completion of the code) without detours. 

Indent, the most common coding standard, is not only for the appearance of the code but also for the easy understanding of the code. It can tell you which statement that line of code belongs to without digging into the code. So it will be easier for you to find where you want to change or debug.
While using ESLint with IntelliJ, I have seen another coding standard which is called prefer-const. It happened when I declare a variable that I am not changing later on with “let”. After reviewing the documentation, I found it is best to use “const” since that is the reference I do not want to reassign. The “const” will prevent me reassign that reference variable which minimize the possibility of running into bugs that I accidentally reassign it in the later code. In this sense, the coding standard “prefer-const” put me on the right track.

The other coding standard I have encountered is “no-unused-vars”. It happens whenever you declared a variable or function but never used.  This will be very useful when you have a big project that maybe has hundreds of lines of code. You might already forget what variables or functions you already declared since there are so many of them. This coding standard will identify it and help you either use those or just get rid of those as you changed your code that don’t need them anymore. Therefore, the “no-unused-vars” will help you make full usage of all the variables or functions you made or delete them to save the time and space your program will need.
There are more coding standards out there. All these coding standards are intended to help you improve the equity of your code and archive the purpose of the code. Following the coding standards just like walking on the ruler  which will provide you the right direction, shortest time or distance and without most common mistakes.
