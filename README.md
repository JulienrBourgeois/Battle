# Battle

This was my third ever project after UNO and Connect Four. I did this in the app lab on code.org during about a five day span and submitted it for the 2021 Congressional App Challenge. Although I placed 2nd in the contest, I am very happy that I made this app as it is a tribute to my Paw Paw. We used to play Battle all the time when I was a little kid and to be able to digitize the game really hit a soft spot of mine.

This app consists of a user vs computer, similar to my UNO and Connect Four games. However, there is so much more complications that have to go into this game to make it function properly. I was also able to take some of my past mistakes in UNO and Connect Four and fix them with this app! For example, I separated alot of my code with comments, named my variables accordingly and even made optimal methods for certain program executions!

To start the game, the user enters their name and hits begin. We also have options for the user to turn off the audio and view the rules. I also made several cool designs and color schemes within this app that I liked a lot! After the user hits play, they are presented with a top down view of the game. On the top of the screen is the computer's card and card count. At the bottom of the screen, is the player's card and card count. On the left, their is a button to play a single turn. On the right, their is a one time button to shuffle the cards if the user is struggling. 

When the play turn button is clicked, the results are shown and the screen returns. If the results are a battle, a new screen pops up allowing for the battle phase to commence. Once the player or computer runs out of all their cards, the game is over. If the player wins, they have the option to add their score to a leaderbooard. This was a major turning point in my high school programming career as I had finally figured out how to save data in the app lab. I was able to save player ID's and their time to completion as well as amount of turns.

That's the basic rundown of Battle. Now, let's get down to the code!

To start off my program, I made tons of variables on top. Any variable I could have possibly needed to write this app was placed on the top of my code. I had player lists, computer lists, card designs, card numbers etc. After this process was complete, I began to create the User Interface of my app. 
Through several hours of screen making and action outleting, I finally had a working interface with 200-300 lines of code to it that controlled hover overs, clicks and more!

Now, all there was left to do was to write the actual functionality of my program. I knew I needed these methods: A start method, A turn method, A battle method, A shuffle method, An end method and A leaderboard method. The start method was written so that I could fill the lists of the player and the computer once the start game button had been clicked. This took 20 random cards out of the pre-existing data sets and placed them in the two separate hands, preparing them for battle (no pun intended). 

After the start method, came the turn method. This method was called each time the player had clicked to play. This would handle this interactions between the two hands and also update the UI. For example, if the player won the round, the card would have to be removed from the computer hand and placed in the player hand. 

After the turn method, I wrote the battle method. During my turn method, if the cards were the same, I would break that execution and call battle method. This method extracted 2 more cards from each deck and the last one was compared. This method was similar to the turn except I had to account for 3 cards not 1 when exchanging them between decks. 

After the battle method, I wrote the shuffle method. When the shuffle method was clicked, it would go away, ensuring its one time usage. Then, both decks would be scrambled in order. This was pretty easy using a randomizer a class.

Finally, I had the end and leaderboard methods. The end method simply checked for a winner. Then it logged the win and removed all the cards from the decks and returned them to the core datasets. If the player won, it then commenced the leaderboard function which iterated through a data system and checked to see if the player's time was fast enough to make it. For example, if the player placed 6th out of 10 on the leaderboard, the players from 6 and on would move down a slot. 


Battle was a huge project that I completed in only 5 days! It was truly an experience as I even made a promotional video and an application for it. I had such a blast with this and it is definetly a major contirbuter to my love for programming to this day😁!



