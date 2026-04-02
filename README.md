## Project Log Assignments
Contributions discussed in voice:
Mason France, 
Kylan Konopaski, 
Christopher Rockwell, 
Rusty Lewis 
# Module Two Team Project Plan
### *Choose a scenario and select the four additional elements you will include.
Scenario 3: Top Down:
- Player Power up
- Player Equipment
- Enemy Stationary
- Obstacles

### Brainstorm on content based on the preferred scenario in the design document.
Updates by Kylan Konopaski:
- Medieval style
- Player Power Ups could give temporary boosts to health or damage
- Player Equipment could be items such as updgraded armor and weapons
- Stationary enemies could be archers or gate guards, etc.
- Obstacles could be spike traps or trapdoors, etc.

### Create a schedule or timeline for developing your game based on due dates outlined within the course.
Refer to timeline word document: https://github.com/mfrance419/GAM-305-Project/blob/master/Top-Down%20Timeline.docx 
### Determine the development goals for the Alpha and Beta Stage submissions (which assets/elements should be in place and what level of functionality you are going to use to track the project progress in the Alpha and Beta stages).
#### Alpha
- Core Player character attacks and movement
- Additional elements finished
#### Beta
- Core level finished
- Character, enemy, and item assets finalized

### Choose preferred communication method(s).
Discord Server. This will allow us to quickly and easily share updates and any important information.

### Choose the frequency of communication (team meeting).
- Daily text chat in Discord
- Thursday afternoon Voice Meeting in Discord
### Choose a method for assigning and reporting on specific task items.
Group VC Democracy. Tasks will be assigned during team dicussions in Discord voice and text channels and we can report on progress each week as well.

Christopher Rockwell - I will work on the pickups this next week

# Module Three Project Log - Team Development: QA and Testing Plan
### Kylan Konopaski
#### How will you test objects, levels, and games during the development cycle? Develop a schedule and include: Play Test: Testing during the preproduction stage, Demo: Testing before marketing will demo the project, Code Release: Checking the code release demo with the test plan
We will test objects, levels, and games personally as we develop them, but also during dedicated play testing sessions. Once we have completed an object/level we will reach out to another member of the team and have them test as well to get another set of eyes on the item (kind of like a code review). Once approved, then we can merge those changes into master. We will utilize the checklist to keep track of what has been tested and what needs to be tested still for each release (alpha, beta, full release).

Test Schedule:
- Module 4 Alpha Playtest (testing powerups, pickups, obstacles, and enemies)
- Module 6 Beta pre Demo release test (testing level walkthrough, win condition, etc.)
- Module 7 Post Code Release test (testing overall functionality and checking edgecases for any unintended behavior)
### Mason France
- What items will be tested? Include a checklist of items to be tested (pass/fail).
- Bugs and features will be tracked through an excel spreadsheet matrix which will be uploaded to the github, after features are discussed they will be added to the matrix, when features are finished they will be marked off, bugs will be added to the bugs section of the feature. Testing Matrix found here https://github.com/mfrance419/GAM-305-Project/blob/master/GAM-305TestingMatrix.xlsx
### Rusty Lewis
#### How will you update the test plan to reflect changes to the game and design document?
- All project test plan updates will be done after any and all changes to the project. In order to keep a clear clean trackrecored of any changes. The team will confirm what updates they will be working on and write out a detailed summary of what was accomplished in the discord. Along with in the test matrix and github, to ensure that there is no confusion among the team. 
### Christopher Rockwell
- How will bugs be reported? The bugs will be reported in the excel spreadsheet and to each other through discord
- How will the bugs and their changes be tracked over time? The bugs and their changes will be tracked in a similar way where we track them through the excel and communicate the changes through discord

# Module Four Project Log - Team Reflection

### Kylan Konopaski
##### What parts of the testing process did the team perceive to go well?
The testing process has gone really well so far throughout development. We typically test our features as we implement them instead of waiting until the end of each stage. This helps us to catch issues early so that they don't compound into bigger issues later. Also, peer reviews have gone really well since we try to get atleast one other person to test any features we implement before merging it into the master branch. This is successful because it allows us to test from different perspectives and possibly uncover issues that we might have not found otherwise. Testing the alpha release also went really well because once we were able to get all of our features merged together we could see how they interact together and there were no major issues. I expect to have a successful testing process during beta development as well.
##### How were bugs identified and corrected?
Bugs were mostly identified through playtesting our own features but also when playtesting other's features too because it's good to find bugs when you don't know how the system works since that is more akin to how a user would experience the game. Once these bugs were indentified, we were either able to fix it on our own or reach out to the team member that has ownership over that feature so they could analyze and update it. We all used a lot of print strings in development because it makes it more clear to see when/where something is going wrong in the execution. For example, I was having issues with collisions and applying damage so I used print strings to determine if the collision was not working or if it was something with my damage method. Once I saw that there was no print string after my mesh collided with the enemy, I knew it was the collision that needed to be fixed. 
##### In terms of the QA and testing process, what would you do differently to improve the process?
One area of the testing process that could be improved would be coordinating our testing and debugging more effectively. For example, the print strings were getting a little out of hand because of how many different situations they were being called. It would be better if we chose a color for each of us and then printed the string in that color in order to differentiate better while testing. I also think it could be beneficial to use our testing matrix that we created earlier in the term. We have struggled to use it, simply because of how fast paced this development is and it can be hard to find time to update that documentation, but I think it would help keep things organized and provide more insight about your feature to the other team members. Another way we could improve our testing process would be to have larger dedicated testing sessions where we are actively trying to produce bugs. This ensures we are perfecting our game and not just seeing if it looks good. 
### Mason France
##### What tools (chosen in Module Two) did you find successful in the development of your Alpha project? Why?
One of the best tools I have found for the Alpha is of course Github, being able to have everything in one place is fantastic along with being able to collaborate using the tool just makes github one of the best tools for any kind of software development. unreal engine also does a lot especially with the blueprints, Unreal was one of the first to really push visual scripting into the mainstream when it came to game development which allows almost anyone to be able to pick up game development and make it more accessible for everyone.
### Rusty Lewis
##### Were there any tools or techniques that you did not find helpful in the success of your project development? Why?
On our project, we did not fine the timeline or the excel sheet to be very helpful in the creation. The team has mainly relied on communcation with each other directly, and completing our sections in our own way. Making sure to let the others know when we are doing work and what work we are getting down. Along with whatever problems we stubble across while reaching our goals. Because of this, the timeline and spreadsheet were not used often during the development of stage Alpha. We have foudn the direct communication with a quick message or two in the group chat worked better for our needs. Allowing us to stay updated quickly and make the changes when they are needed.
### Christopher Rockwell
##### How did the team approach to the initial analysis of the game design document contribute to the decision to use these tools and techniques?
Based on our initial analysis of the game design document we knew we needed to use Github to collaorate on the project, which was necessary to combine the individual work we've done to make the alpha. The other tool we used was Unreal Engine, which despite being the course requirement is still a very good game development tool that allowed us to work on th project both individually and as a team.

# Module Five Project Log - Team Reflection.

### Kylan Konopaski

### Mason France

### Rusty Lewis

### Christopher Rockwell

#### What parts of the plan did the team perceive to go well in relation to the last stage evaluation?
#### What parts of the plan did the team perceive to go wrong in relation to the last stage evaluation?
#### How were the previous evaluations integrated into this latest stage?
#### What would you do differently to improve the collaboration or development process?
#### Were there any tools or techniques that you did not find helpful in the success of your project development? Why?
#### Identify the completed stage of development of the intended Beta and address the project schedule to meet Final Release development deadline.
