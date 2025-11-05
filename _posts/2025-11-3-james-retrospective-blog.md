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

2. A more recenent problem I expierenced was my make not working. The problem was caused by a juypter notebook file that had a space after the title. This goes to show how precise you have to be when coding because a little error like that can ruin your code.

## Sprint 2: Snake Game and Word Game Hack

After we had all our machines set up and prepared we moved on to a new project. This project required us to make changes to already existing hacks and make it better

#### Snake Game Hack

For our snake game we made many different changes to the game. We made the looks of the game more visually appealing and added many different gamemodes for more fun.

Link to Updated Snake Game:

https://compsciteam.github.io/student/snake/


### Word Game Hack 

For our word game we made a very large update to the game to make it more fun and enjoyable. I first added a updated finish screen since the old finish screen used to be a tiny text bubble that appaered.

Link to updated Word Game:

https://compsciteam.github.io/student/wordgame

## Sprint 3: Mansion Game

The mansion game was by far my biggest challenge. For this game we had to work together as a team to create our level. My team consisting of Anish, Samarath, Vihaan, Krish, and Pranay we decided that we were going to back a boss fight for the final level. This means that we had to put a lot of effort into this in order to make the game look good and to be fun for players.

There were many different concepts that we had to use in order to make our game in an effective manner. I will tell you our plan and concepts that we used to finish our game

### Plan for the Mansion Game
Our plan for the Mansion game was to make a final boss fight to escape the mansion. This was the final level for the mansion and needed to be a fun and intresting way to finish the game. We decided on a boss named the Reaper to be the final boss.

### Pre-Boss Fight Room
In the pre-boss fight you find two zombie zpcs that will tell you different things. One talks about code while the other talks about the boss. The room also plays music which I added to the game. This makes the game more immersive. When you enter the double doors it will take you to the boss room. 

#### How pre Boss Room Works
Our pre boss room works by doing using lots of collions. When you collide with the zombies and press e it will take you to dialouge. When you collide with the door and press e it brings you to the next room. My main contributions to this room was adding the music and adding a invisible sprite. This invisible sprite is what you collide with to get to the next room.

###  💀 Boss Room  💀
Once you enter the boss room it takes you to a boss fight. There is a boss called the repear who you will fight. There is also a change in music, and 2 health bards, 1 for the player and 1 for the boss. I added the boss health bar which changes color based on how low the boss health is. The player can attack the boss which causes his health to go down.

#### How Boss Room works
The boss room works by using lots of collions. When you press space bar the player will shoot a arrow. If this arrow collides with the boss it will cause his health to go down. The health bar then moves since it is equivalent to the health of the boss. If the Reaper's attacks collides with the player then it will lower the players health and the his health bar will update.

#### Reaper Boss
The Reaper is a skeleton, armed with many different attacks. First he shoots arrows and fireballs into the direction of the player. If they collide with the player then the player will lose health. If the player collides with the main body of the boss then the player will automatically die and be respawned. He takes damage from the player's arrows. When his health equals zero the game ends and the victory screen appears.

###  🏆 Victory Screen 🏆

After the Reaper health is equal to 0 the victory screen finally appears. It shows that you have finally beat the game and the music changes. I added this music to the final screen.
### Kanbans and Issues

Kanban boards are an effective and helpful tool for keeping your group on track when working on a project. They work by taking a bunch of issues and splitting them into different sections. Issues are problems or objectives that you need to complete in your code. 

Imagine it like a bunch of sticky notes. Each sticky note has a goal written on it. You then place it onto a board with different sections to show how far the sticky notes are to completion. This is what a kanban board is.

![]({{site.baseurl}}/images/blogImages/KasmBoardImage)

### Biggest Tech Accomplishment

My biggest tech accomplishment that I made in the game was adding the boss bar to the reaper. This was a huge part of the game since it allowed the player to see how much health the final boss had. My code also made it to where the color of the boss bar changed each time it got lower and lower. Each 33 percent decrease in the boss color changed.

### My Favorite Tech Accomplishment

Though I enjoyed creating the boss bar it was not my favorite commit of the game. My favorite addition I made to the game and my favorite addition this entire trimester was adding the music. The music was a very important part of our game as it made the player more immersed in the level. I ended up adding the beginning Legend of Zelda theme to the pre boss fight room and the final music on the victory screen. These changes made the game far more immersive and seeing the music I chose for the game being implemented was really fun.

### Lessons I learned

Throughout this project I learned many important skills when programming. First of all, you need to work effectively as a team. If your team becomes disorganized it will become a lot harder for you to succeed in your project. You need to stay on the same page so you don’t edit the same files at once.

I also learned the importance of debugging in coding. You are never going to be perfect in your coding so you need to debug eros to make your game work correctly. This is important even when using A.I. to help you since you need to direct it to fix your problems. If you don’t give A.I. the correct directions your code will never be fixed.

Lastly I discovered how fun it can be to code a game. Though it is challenging and lots of problems come up, seeing the final result of all your hard work paying off is worth all the time. This project made me discover that coding doesn’t have to be just boring lines, but instead it can be a way to spread your creativity and ideas throughout a game.

