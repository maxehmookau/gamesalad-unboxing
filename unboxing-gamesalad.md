# Unboxing GameSalad

## What is it?
GameSalad is a game-development platform for OS X and Windows aimed at younger and inexperienced developers. It features an innovative drag-and-drop interface allowing even the newest of developers or those with no previous coding experience to make games for iOS, Android and even HTML5 applications that can run in a browser.

## Use in education
GameSalad is used in education by Box UK and by schools across Wales and the rest of the UK. It's intutative interface allows children to quickly and easily learn the concepts behind object-orientated programming such as objects, classes and control flow. But it stops shorts of expecting children to write code. Box UK is using GameSalad as part of the Technocamps projects to develop a learning application with children to be deployed in schools throughout Wales.

## Getting to grips
As an iOS developer more used to working with applications at a code level, I initially found working with GameSalad a confusing experience. It encourages a totally new way of thinking about application development which doesn't support object-orientation in a way I've become accustomed to in most modern languages. However, it is this simplicity that makes it such a powerful learning tool.

## Getting down to business
GameSalad has four main entities to wrap you head around:
1. Actors
2. Behaviours
3. Scenes
4. Tables

### Actors
Actors are objects. Things. **Classes**.  It could be a car, a timer, a banana, a box containing the current score or, as asked for by the kids we worked with, a bagel. They are 'actors' because they are the objects that perform on scenes. All actors have attributes and behaviours. They all come with some default attributes such as size, rotation etc. but all support custom attributes too of varying data types.

[Image of Actors Screen]

### Behaviours
Actors have **behaviours** attached to them. These can be executed on a number of triggers. Either when they are spawned, when they are tapped, clicked, triggered by a keystroke or after a timer is run. 
Behaviours and attributes can be attached to objects both at a 'prototype' level or an 'actor' level. Think of prototype behaviours and attributes as class methods and actor attributes and behaviours as instance methods and variables. Personally, I found drawing comparisons such as this very helpful when learning the basics of GameSalad.

[Some example behaviours]

### Scenes
Scenes are where it all happens. The 'view' of your application. 