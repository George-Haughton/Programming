# Programming mapping documents

## 1. Algorithm
An Algorithm is a formula that solves a problem, based on completing/conducting a sequence of outlined actions. Firstly, there are 5 important stages of building an App. The first stage is the Pre-production stage, where you will brainstorm and document every aspect of how your app works. The ideas you will brainstorm will consist of what is your expected users, what experience you would like your users to have and what the overall outcomes you expect from the user using the app. Secondly we have stage 2 which is about ‘telling your story’, after we have a basic idea of what we want the app to consist of we now need to make a low-fidelity storyboard detailing scene by scene of the app. This stage will not look aesthetically good, but it will outline the key points of the app, such as the flow of it, how it works, the logic behind the app and will give you a good idea of what the app actually is. This stage is very important and should not be rushed as it is the base foundations of your app and should be looked at it high detail, involving as many people as you can. Thirdly, the visual design stage. This is where you will create the look and feel of your app. For example, creating the UI (user interface) elements (how the user will navigate their way around your app), the transitions between scenes, the design of each page (how the text it positioned, what colours are you going to use and what images) and finally what interactive component are going to be used on each page, but we do not make any code all we are doing is building an idea of how the app works and how it’s going to look. The fourth stage is the coding/programming of the app which is arguably the most important stage, when coding an app, you will need to choose a preferred platform you would like the app to start on then after you have perfected the first platform you can move onto others. This is a good way of keeping the job easy for yourself as trying to get an app up and running on both platforms at the same time can be a difficult task. During this process you will be constantly adjusting the code to make sure no bugs develop and to make sure the code works completely without any mishaps. With this stage it can take longer than intended because of the bugs and things of this nature stopping the app from progressing. Finally, we have the launch stage where we will have to speak to companies about putting the app on their platforms and prices and things of this nature. As with any app the general public might find bugs and problems with the app you and your company did not consider or find, and this is where the continuous running of the app, and continuous updates will need to keep happening to make sure the app is always at a standard the users are happy with and they are not any problems that stop the users using the app in its intended way.

## 2 Paradigms 

### 2.1 Procedural
Procedural language uses programming languages like Pascal, C++, Fortran and C; these are very detailed and will take up alot of time when writing them. Procedural language is a list of instructions that tell the computer exactly what to do. This language will make sure the computer knows step-by-step exactly what to do and how to perform each line of code until the code is finished. It relies on the programmer to do a lot of the work and the programmer will need to provide a solution to a problem or to proivde an answer to a question. It keeps the code as short as possible and somewhere in the code it will contain a sequence of steps that it needs to carry out. Additionally, it does not allow the programmer to copy and paste the code onto another program. Lastly, it can be very difficult to learn because it can take time getting used to.

#### Characteristics
* Puts important issues at the top of the to do list
* bringing change can be difficult and time consuming 
* data moves around freely from function to function
* large problems are divided into smaller problems which are called functions
* it employs and uses a top down approach within the program design

### 2.2 Object Orientated
Object Orientated programming is a language model based around objects instead of 'actions' and instead of logic it uses data. Additioanlly, instead of writing an algorithm it breaks down the problem of elements into classes. It uses objects that consist of data fields and methods to create applications and computer programs. A few examples of common programming laguages that use some techniques from the Object orientated language, are Java, Microsoft Visual Basic .NET, Microsoft C# and C++. Finally, the programmers are able to edit the code without any errors appearing and unlike the Procedural language the programmer can copy and paste the code into other problems if they need to.

#### Characteristics 
* new data and funtions can be added easily at any point
* programs are diided into entities know as objects
* there is an emphasis on data rather than the procedure
* follows bottom up design in program design

### 2.3  Event Driven
This type of paradigm is determined by events or user actions for example mouse clicks, or keyboard presses. It can only be used alongside using a graphical user interface which is one of its main features. This program is not complex and does not need a huge amount of experience to use correctly. When making a program certain languages will only allow the programmer/user to save every property of the program one after the other; whereas with Event Driven programming the programmer can easily develop a program and save all of the properties at the same time saving a huge amount of time and effort.

### Characteristics
* does not slow down the computer as it uses very little processing power
* designed to run a specific action when a specific event is triggered
* trigger functions are mechanisms that decide what code to run when a specific event occurs

### Relationships
The relationship between Event Driven and Procedural are is that they both are methods of structured programming where the code is split into routines and functions. Both are able to take input from the user or from within the program and make calls to the various functions within the program based on the information it recieves. Additionally, early versions of the Object orientated Programming included Event Driven systems such as simulations and graphical user interfaces. Lastly, each Paradigm is trying to find a solution to a problem but the difference is how they use their solution to solve the problem.

## Algorithm with an IDE
I wrote a set of code that when opened within a browser will create a black canvas. I will be using the canvas to help me create my Project 1. Which is a game that will consist of a player controlling a small square by moving his or her mouse. There will be an NPC (Non-Playable Character) chasing the players mouse and will attempt to touch the players mouse/square with its own square. The player will have 3 lives and will need to run away from the NPC for as long as possible but as soon as the players is touched 3 times the game will end. The two screenshots below are the code i used which was written in Notepad++, and the black canvas the code creates when opened in a browser.

![](https://gyazo.com/58783da1508384532159059bccfa12a7.png)

![](https://gyazo.com/10bee2ce980a90efe0e280f2fefa2fa7.png)



## Debugging
Debugging is the process of finding and removing existing and potential errors also referred to as 'bugs'. Debugging is used to get rid of these 'bugs' in software code that could cause the system to act incorrectly, crash, or not work at all. Additionally, when various subsystems or modules are tightly packed it makes debugging a lot harder as when one bug ix fixed it can cause another bug to occur. In some occasions it takes more time to debug a program than it does to code it. The debugging process can be a time consuming job but it has to be done. The first step of the debugging process is to Reproduce the bug/problem, it is very important you reproduce the bug to make sure you know what you're dealing with, if you cant reproduce the bug get someone else to. Secondly, describe the bug, try to get as much information/input from the user to get the exact reason. Thirdly, capture a program snapshot when the bug appears, to get to as much information on the bug, all the variable values and the state of the program at the time of the bug occuring. Fourthly, take a look at the screenshot in depth, does anything look out of place or different? Analyse the screenshot based on the state and action. Based on all this try to find the causes of the bug.Finally, the most important phase, fix the bug. Erase the bug as best you can to make sure your program runs as smoothly as possible, but make sure when fixing this bug it does not create another, somewhere else in the code.

Within most IDE's there is tool called a debugger. Some IDE's do not have an debugger, and this can be troublesome when it comes to the debugging process. A debugger within IDE are completely integrated with the other workbench tools, this gives the user the flexibility they need to adress the problems at hand. A debugger is essential to ensuring there is no way the bug will survive. There are other softwares that can be used but none of them give the user the power like a debugger does. Firstly, one feature within the debugger that is very useful is the fact that it can display complete data structuresm full runtime stacks and multi-threaded environments easily and in a more readable way. The debugger offers several ways to reduce the time, and the repetitive work that comes with debugging. Additionally, a visual debugger integrated into an IDE gives the user access to smart editing and all of the other features of the IDE, in an 'Integrated Development Environment' which is also what IDE stands for, hence the name. Finally, unlike manual debuggers, debuggers within an IDE can attach to a running process or a crash dump; whereass in a manual debugger 'steps to reproduce' a defect are necessary.

## Coding Standards
Coding standards are a set of guidlines that should be followed when it comes to writing code for any program. Within the code i will be writing for my i will be making sure every 8 lines of code i go back and proof check my code to make sure there are no mistakes within them to decrease the chance of any bugs forming. Additionally, from this i will be making sure i indent my code properly to make it easier to read, understand and modify this will make the debugging process a lot easier as my code will be set out neatly. As well as indenting i will be limiting the amount of magic numbers i use within my code, this will make it a lot easier to read; and if i have to look back at the code and alter it.

## Writing code to execution
Firstly, is the most imporant phase and that is meeting with the new client that is hiring you. They will tell you what they would like, when they would like it by and any other important information that they would like you to know. You will ask any questions you might have and give them some ideas, suggestion or reccomendations you may have that would be beneficial to their task/project.

Secondly, you will look at the task/project you have been hired to complete in more detail and will decide what language you feel will be the most appropriate for this task. Every language is different with their own pros and cocs and you will need to think hard about which one to pick. A long with a language you will want to pick an IDE to use which is where you will be writing the code. For example 'NotePad' or 'repl.it'.

Thirdly, we have the design phase. This will be when you start to design the program from the ground up. When it comes to designing a program you will need to think of how the program will look, play out, and feel for the user; you may have examples from the client of how they might want the program to look. Additionally, you will need to create some for of design document which will help you proceed with the project. A few things in this document would be Storyboards, this will help you put your ideas into perspective and actual visable designs; another would be a flow chart of a step by step guide on how the code works to help you and the client understand it. Also if you need to clarify anything you should speak to client and ask them any questions you may have.

Fourthly, is the coding stage. This is where you will start to use the IDE you chose and the program you chose to start bringing the program to life line by line. At this stage you should know everything the client wants and make sure everything you're going to do the client like and approves it. Additionally, you will look back at your flow chart to make sure you are following the correct order.

Next is the testing phase. Throughout the programming stage you will need to build prototypes and test them constantly to make sure the code you have written is correct and work, some IDE's will have a feature where it will notify you when it detects a mistake within your code. If your IDE does not have this feature you will need to find other ways on testing the code, for instance you can put the code through your browser and see if it works or using a third party software.

Second to last we have the Document and maintain phase. Throughout the project you will need to be documenting everything you do no matter how small. This will be helpful with future projects to be able to look back on what you did but most importantly it proves to your client what you have been doing, how hard you have been working and how much time you spent working on the project.

Lastly, is the shipping stage where the product will be given back to the client. Once you think all of the previous stages are fully complete this is when you will be able to send or give back the program you have been making. Hopefully you have given it back on time or ahead of schedule the client will pay you if they havent already and this project will be done.


























