(See a completed example of this repository [right here](https://github.com/elewa-student/simple-elevator))

# [Reversed Strings](https://www.codewars.com/kata/reversed-strings)

Explain the challenge as completely & clearly as you can.

_function name_: Function
* Args: (2

  i. Number: the floor the elevator is on - (0 <= floor <= 3)
  ii. String: the floor the elevator should go to - ["0","1","2","3"]
  
* Return: Number --> -3 <= n <= 3
  * Return value indicates how many floors the elevator has traveled
* Behavior: This function will move from it's starting location to it's finishing location, returning the number of floors moved. It is a safe elevator. In case any argument is invalid, it will stay in place to avoid injuring the occupants.

'''
function simple_elevator(floor, button) {
 let returner = 0;
 let floor_is_valid = false;
 let button_is_valid = false;
  
 let possible_floors = [0, 1, 2, 3];
 for (let valid_floor of possible_floors) {
   if (floor === valid_floor) {
     floor_is_valid = true;
   }
 }

 
 let possible_buttons = ["0", "1", "2", "3"];
 for (let valid_button of possible_buttons) {
   if (button === valid_button) {
     button_is_valid = true;
   }
 }

 if (button_is_valid && floor_is_valid) {
    returner = Number(button) - floor;
 }
  
 return returner;
}
'''


### Index
* [Input Analysis](#input-analysis)
* [Solution Explanation](#solution-explanation)
* [Constraints](#constraints)
* [Resource Estimation](#resource-estimation)
* [Scaffolding](#scaffolding)
* [Language Features](#language-features)
* [Bugs & Challenges](#bugs-challenges) 
* [Use Cases](#use-cases)
* [Learning Journal](#learning-journal)

---

## Input Analysis

What characteristics of your inputs are important for your solution?  

What groupings will you have to consider when building your solution?  

How did you use this information to select your test cases?


[TOP](#index)

___

## Solution Explanation

Explain your solution in detail, however works for you.  Perhaps by using a specific input to illustrate, by describing your strategy, or by including a diagram [directly from Sketchboard.io](https://sketchboard.io/blog/2014/03/06/github-sketchboard.html).

[TOP](#index)

---

## Constraints

What constraints did you place on yourself, and why?  Did they end up being helpful or not?

[TOP](#index)

___


## Resource Estimation

Estimate how what resources you will require, and how much of each.  


[TOP](#index)

___

## Scaffolding

Provide a link to Gist you used to construct your solution's scaffolding.  What difficulties did you have making it?  How helpful was it in coming up with your finished solution?

[TOP](#index)

___


## Language Features

List the language features used in your solution.

The focus of these exercises are to strengthen you problem solving skills, not to learn the newest ES6 tricks. When you have the choice between to different language features it is better to choose the option that is easiest to read, most common, or most consistent with the rest of your solution.  

Keeping track of the language features you use will enable you separate the problem solving strategy from the implementation.  Being aware of this difference will be an asset later on when you're faced with larger applications and popular frameworks.

[TOP](#index)

---

## Challenges & Bugs

What particular challenges & bugs did you come across when you were filling in your scaffolding?

Were they logic bugs? Language bugs? 

Did you have trouble keeping track of which part of the challenge you were solving?

[TOP](#index)

___

## Use Cases

List 5+ use cases for your solution.  They can be stand-alone, part of an application, or impractical.  Your use cases can be overly complicated, or very basic. What's important is that you come up with as many and as diverse use cases as possible.


[TOP](#index)

---

## Learning Journal

Things I learned studying this problem:


New vocabulary:


Things I struggled with:


Lessons to apply for next time:



[TOP](#index)

___
___
### <a href="http://elewa.education/blog" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/34921062-506450ae-f97d-11e7-875f-6feeb26ad72d.png" width="100" height="40"/></a>

