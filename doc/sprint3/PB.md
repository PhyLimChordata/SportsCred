===========================================================================================================
Open Court
===========================================================================================================
Priority: Medium
Point Estimate: 

As a [casual user/enthusiast], I want to interact with others through posts so that I can stay up to date about the sports community and make more accurate predictions.

Given a post, when pressed on then display comments and then give options for liking and commenting.
	should be able to create (initial post) & comment (create follow-on post)
	should be able to like & dislike
	Should be to share to other platforms
-----------------------------------------------------------------------------------------------------------
Priority: Medium
Point Estimate: 

As a [moderator], I want to moderate discussions and remove posts if they pose a threat to the community so that the community feels safe and well informed on sports and topics.

Given a reported post, when the “remove” button is clicked then the post is no longer visible and all parties involved are notified of the resolution. 
------------------------------------------------------------------------------------------------------------
Priority: Lowest
Point Estimate: 

As a [enthusiast], I want to be able to report posts so that [moderators] can remove the post and keep the community safe.

Given a post and it’s report button, when clicked, then give reasoning for why the post needs to be reported and submit a report. 


============================================================================================================
Trivia
============================================================================================================
Priority: Medium
Point Estimate: 

As a [enthusiast], I want to play trivia sololy, so that I can test my own knowledge.

Given a solo trivia mode, when a [casual user/enthusiast] chooses an answer, then the system awards points to the player for being correct or punishes for being incorrect. 
------------------------------------------------------------------------------------------------------------
Priority: Medium
Point Estimate: 

As a [enthusiast], I want to play trivia against others, so that I can see how my knowledge compares to others. 

Given multiplayer trivia mode, when a player correctly answers a question first, then the system goes to award the player and punish other players.
------------------------------------------------------------------------------------------------------------
Priority: Lowest
Point Estimate: 

As a [enthusiast], I want to report questions if they are faulty so that the community has accurate information. 

Given trivia question’s report button, when clicked, then choose report options and send the report.
------------------------------------------------------------------------------------------------------------
Priority: Lower
Point Estimate:

As a [enthusiast], I want to view my past history of trivia, to analyze my trivia skills.

Upon clicking a view for "Match History" it'll provide a list of recent scores. Could include some analysis:
    - Average Points per game
    - # of times they're faster than opponents
    - Genre of difficult questions

============================================================================================================
Debate
============================================================================================================
Priority: Medium
Point Estimate: 

As a [enthusiast], I want to have a debate with another user, so that we could argue around a topic and find out a winner.

Given the [casual user/enthusiast] is in the debate, when that [casual user/enthusiast] initiates a debate invite post with a selected topic, then other users in the same tier can join the invitation to start a debate 
------------------------------------------------------------------------------------------------------------
Priority: Medium
Point Estimate: 

As a [casual user/enthusiast], I want to view outstanding debates, so that I could listen to other people’s ideas.

Given the [casual user/enthusiast] is in the debate page, when the [casual user/enthusiast] clicks on a debate post, then that [casual user/enthusiast] will open the debate details page and view contents 
------------------------------------------------------------------------------------------------------------
Priority: Medium
Point Estimate: 

As a [casual user/enthusiast], I want to  score each side’s arguments in a debate, so that I could participate in the debate as one of the judges.

Given the [casual user/enthusiast] in the debate details page, when the [casual user/enthusiast]  scores two sides’ arguments with rates, then the overall rating of the answers for both debate sides will be updated.


============================================================================================================
Picks & Predictions
============================================================================================================
Priority: Medium
Point Estimate: 

As a [enthusiast], I want to make predictions on players and coaches, so that I can raise my tier and talk with others in higher tier brackets.

Given a category for a prediction, when picks are correctly predicted, then I gain points to raise my tier.


============================================================================================================
Profile
============================================================================================================
Priority: Medium
Point Estimate: 

As a [casual user/enthusiast], I want to view other people’s profiles, so that I can get to know other people better. 

Given a [casual user/enthusiast] is at the open court, trivia, pick & prediction or debate , when the [casual user/enthusiast] clicks another user’s account id or picture, then the [casual user/enthusiast] will see that user’s profile contents.
	contents in the profile: picture, about & interest, status, ACS summary
------------------------------------------------------------------------------------------------------------
Priority: High
Point Estimate: 

As a [casual user/enthusiast]. I want to view my own profiles, so that I can validate my personal information and view my account status

Given a [casual user/enthusiast] is at the home page, when the [casual user/enthusiast] clicks the profile button, the [casual user/enthusiast] will see his/her own user profile contents.
	Contents in the profile: picture, about & interest, status, ACS history, current picks
	Optional contents: pick history & results, friend list
------------------------------------------------------------------------------------------------------------
Priority: High
Point Estimate: 

As a [casual user/enthusiast], I want to edit my own profiles, so that I can update my personal information

Given a [casual user/enthusiast] is in his/her user profile, when the [casual user/enthusiast] clicks the edit option, then the [casual user/enthusiast] will be able to update picture, about & interest, and status.
Should see the update as soon as the changes submitted
------------------------------------------------------------------------------------------------------------
Priority: Lowest
Point Estimate: 

As a [casual user/enthusiast], I want to have the add friend option in other people’s profiles, so that I can add other people to my friend list

Given the [casual user/enthusiast] is in another user’s profile page, when the [casual user/enthusiast] clicks the add friend button, then that user will be added to the [casual user/enthusiast]’s friend list.
	For user that already in the friend list, this option should be unavailable
------------------------------------------------------------------------------------------------------------
Priority: Lowest
Point Estimate: 

As a [casual user/enthusiast], I want to have the delete friend option in my profile’s friend list, so that I can remove some of my friends from my list.

Given the [casual user/enthusiast] is in the friend list, when the [casual user/enthusiast] clicks the delete friend button, then that friend will be deleted from the friend list
	Confirmation message box pops up to double check user’s decision


============================================================================================================
Sign Up
============================================================================================================
Priority: Highest
Point Estimate: 

As a [casual user/enthusiast], I want to sign up with my personal information, so that I can create my sportcred account

Given the [casual user/enthusiast] in the sign up page, when the [casual user/enthusiast] fills in all basic information and six questions, then an sportcred account will be created for the [casual user/enthusiast]
	Basic information required to sign up:
		Email address
		Phone number
		Name
		Password
		confirm password input box (optional)
	Six questions
-------------------------------------------------------------------------------------------------------------
Priority Lowest
Point Estimate:

As a [casual user/enthusiast], upon signing up, I want to recieve an email to confirm my signup in order to confirm my signup actually worked.

On signup the [casual user/enthusiast] should recieve an email and allow them to confirm

=============================================================================================================
Login
=============================================================================================================
Priority: Highest
Point Estimate: 

As a [casual user/enthusiast], I want to sign in my account, so that I can log into the app to enjoy its contents

Given the [casual user/enthusiast] is at the login page, when the [casual user/enthusiast] enters his/her account identification and password, then the [casual user/enthusiast] will log into the account if the account identification matches with the password. Otherwise, the login failure message will pop up.
Two input required: account identification and password
	Account identification can be one of these:
		Email address
		Phone number
	optional: remember me option, forget password option & google, facebook, linkedin login option

-------------------------------------------------------------------------------------------------------------
Priority: Lowest
Point Estimate: 

As a [casual user/enthusiast], I want to be request for an email to reset my password, so if I forget it I can still login.

Once the user clicks the button, an email should be sent to the user with a randomized password to login with.
Users should also be able to change their password upon log in with the new randomized password.

=============================================================================================================
Notification
=============================================================================================================
Priority: Low
Point Estimate: 

As a [casual user/enthusiast], I want to get notifications about messages, games and others so that I stay up to date in real time.

Given a notification, when clicked, then go to the layout related to the notification and clear alert. 


=============================================================================================================
The Zone
=============================================================================================================
Priority: Low
Point Estimate: 

As a [casual user/enthusiast], I want to access and view the "Setting page" so that I can be personlized the app settings.

Given the user is in “The Zone”, when the user clicks on the gear then the user will be navigated to “Settings” page and start update app settings.
-------------------------------------------------------------------------------------------------------------
Priority: Low
Point Estimate: 

As a [casual user/enthusiast], I want to access and view the "Tutorials page" so that I learn how to use the app without other people's support.

Given the user is in “The Zone”, when the user clicks on the question mark then the user will be navigated to “Tutorials” page and watch tutorial videos/slides.
-------------------------------------------------------------------------------------------------------------
Priority: Medium
Point Estimate: 

As a [casual user/enthusiast], I want to see real time game results, so that I can know the state of the game.

Given a game is currently live, when the app is opened, then I can see the real time game results on the score ticker at the top of the app.
-------------------------------------------------------------------------------------------------------------
Priority: Lowest
Point Estimate: 

As a [casual user/enthusiast], I want to see past scores and statistics, so that I can study and get better with trivia and make better predictions.

Given a game is over, when the score ticker is clicked, then I can see results of past games.
-------------------------------------------------------------------------------------------------------------
Priority: Low
Point Estimate:

As a [casual user/enthusiast] I want to view the posts in pages/sorted differently, so that I can view posts that aren't just new but popular.

On the Zone, there should be an option to view posts as based off:
    - Popularity
    - Recency
    - Focused
Upon selection, it the posts should reorder themselves