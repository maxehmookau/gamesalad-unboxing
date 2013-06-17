# Unboxing GameSalad

## What is it?
GameSalad is a game-development platform for OS X and Windows aimed at younger and inexperienced developers. It features an innovative drag-and-drop interface allowing even the newest of developers or those with no previous coding experience to make games for iOS, Android and even HTML5 applications that can run in a browser.

## Use in education
GameSalad is used in education by Box UK, schools across Wales and the rest of the UK. It's intuitive interface allows children to quickly and easily learn the concepts behind object-orientated programming such as objects, classes and control flow. But it stops short of expecting children to write code. 

Box UK is using GameSalad as part of the Technocamps projects to develop a learning application with children to be deployed in schools throughout Wales.

## Getting to grips
As an iOS developer used to working with applications at a code level, I initially found working with GameSalad a confusing experience. It encourages a totally new way of thinking about application development that doesn't support object-orientation in a way I've become accustomed to in most modern programming languages. However, it is this simplicity that makes it such a powerful learning tool and perfect for introducing young children to coding.

## Getting down to business
GameSalad has four main entities to wrap you head around:

1. Actors
2. Behaviours
3. Scenes
4. Tables

### Actors
Actors are objects; Things; **Classes**.  It could be a car, a timer, a banana, a box containing the current score or, as requested by the kids we worked with, a bagel. They are 'actors' because they are the objects that perform on scenes. All actors have attributes and behaviours. They all come with some default attributes such as size, rotation etc. but all support custom attributes too of varying data types.

![](https://www.evernote.com/shard/s10/sh/43f58b9f-7755-49b1-994b-748a7c2ca5c3/6f03db15824900d4f99abea3319b1c1e/deep/0/Screenshot%2017/06/2013%2009:32.png)

### Behaviours
Actors have **behaviours** attached to them. These can be executed on a number of triggers. Either when they are spawned, when they are tapped, clicked, triggered by a keystroke or after a timer is run. 
Behaviours and attributes can be attached to objects both at a 'prototype' level or an 'actor' level. Think of prototype behaviours and attributes as class methods and actor attributes and behaviours as instance methods and variables. Personally, I found drawing comparisons such as this very helpful when getting to grips with GameSalad.

![](https://www.evernote.com/shard/s10/sh/093d63e3-73fd-4225-8220-076250911fee/7653f24af19fba0830679ccd7c41abb5/deep/0/Screenshot%2017/06/2013%2009:35.png)

### Scenes
Scenes are where it all comes together. In a traditional [MVC](http://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller) app, this would be the 'view' of your application. Scenes themselves can't have behaviours, they simply spawn actors which then act on the scene. Scenes can however, have attributes which persist for as long as the scene exists. Handy for keeping track of the score or the attributes of actors if they need to be readable or writable by other actors in the same scene.

### Tables
Tables are where Gamesalad gets its power. Tables allow you to store arbitrary data in a spreadsheet form. Because each cell in the spreadsheet can be accessed from its (x,y) position on the table, we can store information to be accessed algorithmically.
For example, it's perfect for storing the questions and answers in a simple quiz game. Each question would consist of a single row in the table. The first column could be the question, the second would be the correct answer followed by a number of incorrect answers. By saving a 'current_question' attribute in the game, each time a question is answered, we can easily move on to the next question by referencing the next row in the questions table.
[screenshot example]

### Should I?
I'm still of the opinion that real production-level game development should be done using more professional tools. Even 2D game design is probably better suited to a specialised library such as cocos2d. But if you're just starting out in the world of programming and making a game is your dream, GameSalad is an excellent place to start. The entry-level version contains almost all of the features and is completely free. A pro version is available for USD$299 and includes opportunities for revenue generation and support for Apple's Game Centre.

At Box UK, we have found it an incredibly powerful tool for teaching young people about the principles of programming. The children involved in the project have all been incredibly enthusiastic, often spending time outside of our sessions playing with GameSalad on their own.
