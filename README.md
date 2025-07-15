# Codera.

What are our motivations for creating *Codera*?
In a world where technology is ever evolving, it has never been so vital for edtech to be widely accessible and engaging given its importance in everyday life. We asked ourselves; how can we ensure that everyone – regardless of their abilities or circumstances – has equal access to this education? We realized that, while there are several resources available, there did not seem to be a comprehensive solution that is truly engaging and accommodating for different accessibility requirements.
 
Considering this, we decided to create Codera, an AI-powered edtech platform designed to make learning not just more personalized and effective, but also inclusive and accessible for everyone. 
 
What is *Codera*?
Codera is an edtech platform, with three major sections ‘Home’, ‘Learning’, ‘Play’, which allows you to learn to code and optimise your learning through the availability of accessibility features. Codera turns this learning process into a fun and interactive activity using the incentive of an in-game currency (coins) which is used to compete against others in the leaderboard, a subsection of ‘Home’. There are two different ways to earn coins, one of which is a reward system whereby after having learnt the relevant content, each correctly answered subsequent question in ‘Learning’ rewards the user with a fixed number of coins. The other method is by heading over to the ‘Play’ section where, once an individual is feeling particularly confident with a topic, the user can decide to input how many coins they are willing to risk for the chance to increase this number. The game presents a question with a 3x3 grid (mines) displayed below, where each square has an answer, and it is up to the user to select the answer they believe is correct. If their answer is wrong then the game ends and they lose all the coins they risked, otherwise, a correct answer increases the user’s coins which increases by a greater amount for a longer streak – until the user decides to ‘cash out’ or gets an answer wrong. This creates an interesting way for the user to test their knowledge and compete against friends and others.
 
Beyond this, we have made the learning process engaging by introducing a scrolling flashcards system where the user is presented with a bite-sized subtopic, related to the chosen topic. Once this subtopic has been understood, the card can be tapped to reveal a related question to test the user knowledge before they can move onto the next card. This interactive method of scrolling creates a fun and interesting way for the user to understand and apply their knowledge. 
 
How did we build *Codera*?
Regarding AI, the ‘Learn’ section, Codera utilises LLM to analyse resources on the language you wish to learn, which is then retrieved and used to teach bite sized topics and formulate questions based on what you have learnt. This implementation of RAG allows for a more accurate and personalised user experience.
 
The frontend was built on the Flutter framework using Dart. This was particularly useful because of its cross-platform development which meant that we only had to create one piece of software that could be ran on multiple different operating systems such as Android, iOS, and Windows. In turn, it saved us from having to write different software for the same functionality but on different OS. 
 
For our backend, we have used Firebase to store user data and login information. This allows for users to compete against each other in the leaderboard and view public player names so that they know who they are against and to identify their friends. Using Firebase to store login information also means that should a user become unable to access their device, they are still able to log in to their original account without having to restart and lose their progress/coins.
 
How to start
-------------------------------------------------------------------
1) Download Flutter and Dart.
2) Replace OpenAI API key with your own.
3) Run the app by typing 'flutter run' in terminal.
4) The app should now work.
