Submit before 25th Mar to earn 100 points
PRO-C33: PLINKO WITH SCORESAssigned
In This Project, You Will Apply What You Have Learned In The Class And Debug The Code And Get The Output.
GOAL OF THE PROJECT:
In Class 33, you have learned the concept of debugging.

In this project, you will apply what you have learned in the class to achieve the following goals.

Main Goal	
Debug the code and get the output.
Additional Goal 1	
Design the game design by adding scoring system text.
Additional Goal 2	
Write code to increment the score
Additional Goal 3	
Add the game end functionality after some turns.
Additional Goal 4	
Write code to increment the scores randomly.

STORY:
Honey has seen the plinko game played by various contestants on the TV.

Plinko is a game played on a nearly vertical board populated with offset rows of pegs. The player chooses one of five slots in the top of the board, drops the chip into it and watches as the chip bounces down the board. Each time the chip encounters a peg, it will either bounce left or right. Now Honey wants to make this game for herself so she can play anytime.

See a video of this in action here



PicPic


*This is just for your reference. We expect you to apply your own creativity in the project.
GETTING STARTED:


Use the template on GitHub, available for download here

Unzip this folder, rename the unzipped folder as Project-33.

Import this folder into VS Code.
Click on file -> Open Folder -> Select the folder that we renamed in the correct location.


Start editing your code in sketch.js.
SPECIFIC TASKS TO ACHIEVE THE MAIN GOAL:
The project template provided to you has a few bugs in it.

Make sure the project works before you submit it


SUBMITTING THE PROJECT:
Upload your completed project to your own github account.

Create a New Repository named “Project 33”.

Upload working code to this GitHub repository.

Enable Github pages for the repository.

Copy the link to the github pages link in the Student Dashboard.
HINTS FOR THE MAIN GOAL:1. Debugging Hints: Check to see if:
files are not included in index.html.
variables are not created.
class is called in a wrong manner.
the function of a class is not called.
ADDITIONAL GOAL 1:Now add score text in the game and create particles on mouse click.
PicPic
SPECIFIC TASKS TO ACHIEVE ADDITIONAL GOAL 1:
Create a variable score and initialize the score to 0.
Because there will always be one particle while calculating the score, we need to create a particle variable (not an array). Pic

Create a variable count and initialize the turn to 0.
The users should get 5 turns to maximise their score.

Display the score at a desired position using text.

Specify the points in between the divisions using text.
The score should get updated with the number of points specified in the division where the ball falls

Create a gamestate as start or play.

Use a mousePressed() function to create a new particle and assign it to the “particle” variable
Pic

Make sure the project works before you submit it.

*SAVE all the changes made to the project and SUBMIT the shareable link in the Student Dashboard Projects panel against the correct class number.
ADDITIONAL GOAL 2:Here, you have to help Honey in incrementing the scores.
PicPic
SPECIFIC TASKS TO ACHIEVE ADDITIONAL GOAL 2:
If the particle has crossed the yellow line (shown in the image below), you will know that the particle will now fall inside one of the buckets.
Pic

Once the particle crosses the yellow line, to determine in which division the particle is, add the code for the following logic:
If the particle's x position is less than 300 then the score is 500 points.
If the particle's x position is more than 301 and less than 600 then the score is 100 points.
If the particle's x position is more than 601 and less than 900 then the score is 200 points.
Here you see a sample code for the first condition.


Pic

Once the score is calculated, make sure you set the particle variable to null.

Make sure the project works before you submit it.


*SAVE all the changes made to the project and SUBMIT the shareable link in the Student Dashboard Projects panel against the correct class number.
ADDITIONAL GOAL 3:Now, add the game end functionality, when the player’s turn crosses 5 count.
PicPic
SPECIFIC TASKS TO ACHIEVE ADDITIONAL GOAL 3:
For every turn played, increase the count variable by 1.
If the player has played 5 times:
The game is over
gameState is END.
Show that the game has ended.

Pic
Make sure the project works before you submit it
*SAVE all the changes made to the project and SUBMIT the shareable link in the Student Dashboard Projects panel against the correct class number.
ADDITIONAL GOAL 4:You can add the code to increment the score randomly
SPECIFIC TASKS TO ACHIEVE ADDITIONAL GOAL 4:
Randomly assign scoring values to the divisions in multiples of 50.
Use an array to keep track of each division’s X and Y values
Use the array and the score value of a division, to calculate the user’s score value.
Make sure the project works before you submit it.


*SAVE all the changes made to the project and SUBMIT the shareable link in the Student Dashboard Projects panel against the correct class number
ADDITIONAL GOAL 3tasks
After 5 turns is the game ending?
10 pts
Add the game end functionality after some turns.

ADDITIONAL GOAL 4tasks
Are the scores getting incremented by random numbers?
10 pts
Write code to increment the scores randomly.

ADDITIONAL GOAL 1tasks
Is the score text added by the kids between the divisions?
10 pts
Design the game design by adding scoring system text.

ADDITIONAL GOAL 2tasks
Are the scores getting incremented as per the divisions?
10 pts
Write code to increment the score.
