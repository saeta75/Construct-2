Construct-2-Templates
=====================

Construct 2 Templates

All of these templates are free and available to use for anyone interested in making games in Construct 2.  The idea here is to take one of these templates, tweek and customize some of the details to then be able to create a game quickly.  Why rewrite logic for a game, when someone has already done it, right?  That's the point.  I encourage and challenge you to leverage what I or others have already worked on so that the process will be that much easier you.  WHy reinvent the wheel.

Two of the templates that i have spent the most with are the Game-Template and the Trivia-Template.  

The Game Template

The game template is, as it sounds, a template for any generic game.  It adds a Home Page, an About Page, a Game Page, and an End Page.  The logic there is pretty simple, you start at the Home Page, press play, and you are taken to the Game Page. When you lose or time expires, you are taken to the End Page where you high score is disabled.  From the End page, you have the option of restarting the game or going back to the home page.  This templates takes care of displaying the name of you game, keeping track of and displaying time and score including a high score in permanent storage.  This means that when a user plays your game, sets a high score, closes the game, then comes back...the score is still there!

So what do we change in this template?

The main thing you need to change is this template is the actual game play.  The template just includes a countdown timer in the Game Page and goes to the End Page when time epires when the timer reaches 0.  So, you can just go in there to add the game play.  Additionally, any variables that need updating will have a note like so, "**UPDATE**".  Lastly, you want to change the look and feel of your game.  You can change the background, the fonts that are used, the size of text, etc. to customize the game to fit your needs!

The Trivia Template

The Trivia Template is biult on top of the Game Template mentioned above, so it includes all of the above logic.  As you can guess, this template is made for creating a Trivia game.  I have already taken care of the logic to read in questions from a text file, whether it be local or on a sever, and store those questions in an array.  From there, each time the user starts a game, they will be presented with a series of randomly selected questions from that array.  Here are some variables that you can update.

Game Name- The name of your game
questions_file_name- The name of the file to read the questions from
point_bonus- How many points the user earns per right answer
timer- Duration of game in seconds.
number_of_questions-The number of questions to be read in from the file

The biggest thing to know here is how to format you questions in the text file.  Feel free to simply edit the "questions.txt" file that is already there.  Here is an example.

Question;
Answer Choice 1;
Answer Choice 2;
Answer Choice 3;
Answer Choice 4;
Correct Answer;
|

It is very important that your questions fit this format.  Notice that each line ends with a semicolon.  Additionally, each set of questions ends with a "|".  Lastly, the Correct Answer will be the exact same as one of the answer choices.

So, feel free to open this template up, put in some new questions, and go from there!

Email me, james.q.quick@outlook.com, or Follow me on Twitter, @jquickwit, for any questions, comments, or concerns.

