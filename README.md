# Learning Programming Languages

I enjoy learning new things and programming languages is one of those things. I've found that to learn programming and programming languages, it is easiest if you have a project to work on.

There are a few difficulties with this approach:
1. You need to actually have an idea to work on, which aren't always the easiest to come by 🤔
2. Your project may not give you a well rounded experiences with all the features of the language 😫

## A Standardized Approach
So, when learning a new programming language, I create a program that runs various other programs. The user interacts with a simple prompt where they type the number of the program they want to run, then interact with the prompt until the program is finished when they are redirected to the main prompt again.

With this approach, we can create any dumb program to cover various aspects of each language:
- printing to the console ✅
- accepting user intput from the console ✅
- basic programming constructs (control flow, variables, etc) ✅
- advanced language concepts (inheritence, modules, monads, ect...) ✅
- fetching data from a remote source (usually through REST) ✅
- advanced data manipulation (usually the data we pulled from a remote source) ✅
- error handling ✅
- and much more... ✅

## General pattern
Each language will have a different program built for it but each main console will follow the same general pattern:
- 0 to exit
- select a number that runs a program with error handling for when the user selects a number without a program
- returns to main menu when program is finished running or errors
