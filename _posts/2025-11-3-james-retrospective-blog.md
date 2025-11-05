---
layout: post
title: James Blazek Retrospective
description: This is my learnings from Computer Sci Trimester 1
categories: ['Retrospective']
permalink: /retrospective
toc: True
comments: True
---

# James Blazek Retrospective


## Learnings from Computer Science

### Comparision to Beginning of the year
Through this trimester I have learned many things about coding and effective ways to use it. These strategies range from variables to kanban boards. In the beginning I was clueless of how computer science worked and struggled with getting my passwords set up. Now I have improved to the points where I can create many different lines of code. In this Blog I will show you some of the many things I have learned this trimester. 

### Sprint 1: Machine Setup and Basic Fundamentals

To begin I will start off with getting your machine setup. 

1. First I had to make a github account in order to gain access to repositories. Repositories are where all your code goes. You can make many different repositories which git hub helps keep you organized with.

2. Once I had my account I had to open Kali Linux through Kasm. By doing this I could finally access vscode where I could do all of my work. 

3. First when you enter Kali Linux you need to get into a repo so you can change the code. You first need to git clone a repository in order for you to make changes to it.

4. You do this by going in to the console and typing:

`git clone https://github.com/username/repository.git`

An example of me doing this is:

`Git clone https://github.com/1j-bla1/portfolio.git`

After git cloning you finally get the code to your local machine. Following my example you can then access the repo through typing:

`cd portfolio`

`code .`

Now you can make change to your code in the repo.

You then must learn to navigate through the folders of your new repo. Once you enter a file you want to make changes to you can change the code that is written there. Make sure to press control + s to save the changes you made.

Finally once you made your changes you can commit them to github. By committing your changes it will change your code in your repo allowing you to access and see your changes in a website. Once you click commit it will ask you to log in. Finally press sync changes and all of you coding changes will appear in your browser once the file uploads.

### Make Command

The make command is a simple but important tool when coding. By going to the console and typing make it will make a version of your project without actually committing it. This will allow you to see if you changes to the code worked before you commit the changes.

Simply type:

`Make`

Into the console log for it to work
### Problems I experianced with Engine and Files

Throughtout this trimester I had to solve many problems with my engine. Here are some of my struggles with my Kasm and Kali Linux

1. Kali Linux crashes. This happened when my Kali Linux crashed causing my session to be broken. I was then no longer able to access the file and it would never delete. I solved this problem by swapping to Ubunto Mobile while waiting for my session to be fixed.

Image of Kasm glitch:

![Alt text]({{site.baseurl}}/images/blogImages/KasmBreakPicture.png "Image of Broken Kasm")

2. A more recenent problem I expierenced was my make not working. The problem was caused by a juypter notebook file that had a space after the title. This goes to show how precise you have to be when coding because a little error like that can ruin your code.

### Snake Game and Word Game Hack

After we had all our machines set up and prepared we moved on to a new project. This project required us to make changes to already existing hacks and make it better

### Snake Game Hack

For our snake game we made many different changes to the game. We made the looks of the game more visually appealing and added many different gamemodes for more fun. We changed the color of the snake to blue and the different gamemodes make changes to the snakes speed. We also added different backgrounds for different looks to our game.

Link to Updated Snake Game:

https://compsciteam.github.io/student/snake/

Updated Snake Game:


![Alt text]({{site.baseurl}}/images/blogImages/Updated_Snake.png "Image of Updated Snake")

![Alt text]({{site.baseurl}}/images/blogImages/SnakeMenu.png "Image of Updated Snake Menu")

### Word Game Hack 

For our word game we made a very large update to the game to make it more fun and enjoyable. I first added a updated finish screen since the old finish screen used to be a tiny text bubble that appeared. We then updated it to where the letters lined up better.

Link to updated Word Game:

https://compsciteam.github.io/student/wordgame

![Alt text]({{site.baseurl}}/images/blogImages/WordGameUpdate.png "Image of Updated Word Game Typing")

![Alt text]({{site.baseurl}}/images/blogImages/WordGameMenu.png "Image of Updated Word Game Menu")

### Sprint 2: Coding Concepts and Homework

During this project we had to work as a team in order to create a functioning lesson that taught a concept of coding. I was involved in creating the variable and functions lesson. For this project we split our team up into two sub groups. I was apart of subteam 1 and we created the variables and functions lesson. By going through all the different groups lessons and homework I was able to gain a undertstanding on many different coding concepts.

Link to the Variable Lesson:

https://compsciteam.github.io/student/javascript/variables/tinkerers-lesson

Link to Function Lesson:

https://compsciteam.github.io/student/javascript/functions/tinkerers-lesson

### Coding Concepts from Lessons

### Variables:
Variables are one of the most important concepts of coding. Variables are storages that keep track of values. Image it as a box. You can put a dollar inside the box. The box would then equal 1 dollar. It is the same for variables. You give the variables a value are you can use them throughout your 

You can make a variable in Javascript by typing let const or var. Var is not recommended. Var and const are different since a const value is never allowed to change.

Example of a Variable:

`let name=”James”;`

`const name=”James”;`

### Functions:

Functions are another extremely useful piece of code. Functions are a reusable piece of code that you can use over and over again. Imagine it like a box. If you put code in the box it will be in the function. You can then use that box over and over again with the items inside it. It is the same with functions. You put code in the function and can call it over and over again to resuse the code

Example of a Function:

`function greet(myname, myage){`

 `message = "Hello, " + myname + " (" + myage + ")!";`

 `document.getElementById("output2").innerText += "\n" + message;`

   ` }`

`greet("James", 14);`

This creates a function called greet. It then takes parameters when it is called. In this case when greet is called James and 14 are the parameters. It then prints this to the console log. You can call this function over and over again which makes them extremely useful.

### Arrays:
Arrays are another important concept in our game. Arrays are a list of multiple different values which can then be called. Imagine you put multiple different fruits in a box. You then can take 1 or as many fruits as you want out of the box. This is similar to how an array works.

Example of an Array:

`let fruits = ["Apple", "Banana", "Orange, "Pear"] `

### Booleans: 
Booleans are a more simple concept. Booleans are things that can be true or false. To make a boolean you must first make a variable then make it equal true or false here's an example:

`Let Correct_Password= false;`

`Let Username = true;`

### Mathematical Expressions:
Mathematical expressions are basically just math. In Javascript it follows the same rules as the math you do in school but has different signs then you would normally use.

Basic Operators:

`Addition: Use a plus sign (+)`

`Subtraction: Use the minus sign (-)`

`Multiplication= Use an asterisk (*)`

`Division= Use a slash for division (/)`

#### Complex Operators:

Modulo:
Modulo is a more complex type of math. When doing modulo you use the % symbol. When you do this it will look at your first number and then see how many times the second number can go into the first number. The amount left over from the second number is your answer.

Example:

`let first_number= 15 % 6;`

In this example 6 goes into 15 twice. 15 - 12= 3. 3 is then remaining and is the answer.

Exponents:
To create an exponent instead of multiplying with one asterisk * you add 2 asterisks. This makes an exponent.

Example:

`let second_number: 5 ** 2;`

This is read as 5 to the power of 2 which would get you 25.


## Sprint 3: Mansion Game

The mansion game was by far my biggest challenge. For this game we had to work together as a team to create our level. My team consisting of Anish, Samarath, Vihaan, Krish, and Pranay we decided that we were going to back a boss fight for the final level. This means that we had to put a lot of effort into this in order to make the game look good and to be fun for players.

There were many different concepts that we had to use in order to make our game in an effective manner. I will tell you our plan and concepts that we used to finish our game

Link to our Level 6 Game:

https://compsciteam.github.io/testpages/gamify/mansion6

### Plan for the Mansion Game
Our plan for the Mansion game was to make a final boss fight to escape the mansion. This was the final level for the mansion and needed to be a fun and intresting way to finish the game. We decided on a boss named the Reaper to be the final boss.

### Pre-Boss Fight Room
In the pre-boss fight you find two zombie zpcs that will tell you different things. One talks about code while the other talks about the boss. The room also plays music which I added to the game. This makes the game more immersive. When you enter the double doors it will take you to the boss room. 

![Alt text]({{site.baseurl}}/images/blogImages/Pre-BossRoom.png "Image of Pre Boss Room")

#### How pre Boss Room Works
Our pre boss room works by doing using lots of collions. When you collide with the zombies and press e it will take you to dialouge. When you collide with the door and press e it brings you to the next room. My main contributions to this room was adding the music and adding a invisible sprite. This invisible sprite is what you collide with to get to the next room.

###  💀 Boss Room  💀
Once you enter the boss room it takes you to a boss fight. There is a boss called the repear who you will fight. There is also a change in music, and 2 health bards, 1 for the player and 1 for the boss. I added the boss health bar which changes color based on how low the boss health is. The player can attack the boss which causes his health to go down.

![Alt text]({{site.baseurl}}/images/blogImages/Boss-Room.png "Image of Boss Room")

#### How Boss Room works
The boss room works by using lots of collions. When you press space bar the player will shoot a arrow. If this arrow collides with the boss it will cause his health to go down. The health bar then moves since it is equivalent to the health of the boss. If the Reaper's attacks collides with the player then it will lower the players health and the his health bar will update.

#### Reaper Boss
The Reaper is a skeleton, armed with many different attacks. First he shoots arrows and fireballs into the direction of the player. If they collide with the player then the player will lose health. If the player collides with the main body of the boss then the player will automatically die and be respawned. He takes damage from the player's arrows. When his health equals zero the game ends and the victory screen appears.

###  🏆 Victory Screen 🏆

After the Reaper health is equal to 0 the victory screen finally appears. It shows that you have finally beat the game and the music changes. I added the music to the final screen. I also made some code that automatically kills the boss when p is pressed so you can skip the boss fight if needed. This was useful when testing to see if the end screen would work.

![Alt text]({{site.baseurl}}/images/blogImages/EndScreen.png "Image of Victory Screen")

### Kanbans and Issues

Kanban boards are an effective and helpful tool for keeping your group on track when working on a project. They work by taking a bunch of issues and splitting them into different sections. Issues are problems or objectives that you need to complete in your code. 

Imagine it like a bunch of sticky notes. Each sticky note has a goal written on it. You then place it onto a board with different sections to show how far the sticky notes are to completion. This is what a kanban board is.

![Alt text]({{site.baseurl}}/images/blogImages/KanbanBoardImage.png "Image of Kanban Board")

### Biggest Tech Accomplishment

My biggest tech accomplishment that I made in the game was adding the boss bar to the reaper. This was a huge part of the game since it allowed the player to see how much health the final boss had. My code also made it to where the color of the boss bar changed each time it got lower and lower. Each 33 percent decrease in the boss color changed.


Different Healthbar Colors:
![Alt text]({{site.baseurl}}/images/blogImages/ReaperHealth1.png "Image of first healthbar")

![Alt text]({{site.baseurl}}/images/blogImages/ReaperHealth2.png "Image of second healthbar")

![Alt text]({{site.baseurl}}/images/blogImages/Reaper3.png "Image of third healthbar")

Proof of my healthbar commits:

![Alt text]({{site.baseurl}}/images/blogImages/Commits.png "Image of healthbar commits")

### My Favorite Tech Accomplishment

Though I enjoyed creating the boss bar it was not my favorite commit of the game. My favorite addition I made to the game and my favorite addition this entire trimester was adding the music. The music was a very important part of our game as it made the player more immersed in the level. I ended up adding the beginning Legend of Zelda theme to the pre boss fight room and the final music on the victory screen. These changes made the game far more immersive and seeing the music I chose for the game being implemented was really fun.

### Lessons I learned

1. Throughout this project I learned many important skills when programming. First of all, you need to work effectively as a team. If your team becomes disorganized it will become a lot harder for you to succeed in your project. You need to stay on the same page so you don’t edit the same files at once.

2. I also learned the importance of debugging in coding. You are never going to be perfect in your coding so you need to debug eros to make your game work correctly. This is important even when using A.I. to help you since you need to direct it to fix your problems. If you don’t give A.I. the correct directions your code will never be fixed.

3. I learned many different coding concepts that are vital when programmin. Without learning concepts such as variables and functions through Sprint 2 it would be very challenging to complete any type of code.

4. Lastly I discovered how fun it can be to code a game. Though it is challenging and lots of problems come up, seeing the final result of all your hard work paying off is worth all the time. This project made me discover that coding doesn’t have to be just boring lines, but instead it can be a way to spread your creativity and ideas throughout a game.


## 🎉 Conclusion 🎉
In conclusion, computer science has been a fun class that has taught me the importance of working as a team, using github, thinking on ways to solve challenging problems(Debugging), and having fun through making games. I am glad that I got the oppurtunity to learn different concepts in code so I can code games. 

