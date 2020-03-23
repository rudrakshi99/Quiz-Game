# Quiz-Game
This is a Quiz Game Mini Project in C designed as a simple console application. In this project, a number of questions are asked and questions are chosen in such a way that they cover all fields of a typical quiz contest. The user’s general knowledge is tested with quiz questions regarding science, technology, movies, sports, general health, geography and many more.

The source code is to be compiled in Code::Blocks with gcc compiler. This quiz game in C is not designed to run on the Turbo C versions. 

# Quiz Game in C – Project Introduction:
I have divided this mini project into many functions, and listed below are some of those which may help you understand the project better.

edit_score() – adds the current scores to previous one upon giving the right answer to a question

help() – help menu with game summary and rules

reset_score() – to reset the highest score to default

show_record() – shows the highest score of a particular user

show_score() – to view the highest score

In this quiz game mini project, you can store the user name, view the highest score secured by a user, and even reset the score. Additionally, to make the game look a little more interesting, it is divided into two rounds; user must pass the first round to reach the second one.

Of the 2 rounds I mentioned above, the first is called the Warm-up Round; the second is the Challenge round. In the warm-up round, the user is asked a total of three simple questions and they must be able to answer at least two of them correctly to enter the next round. If the user is not capable of doing that, he is not permitted to proceed further.

In the second and more interesting round of this quiz game in C, the user will be asked questions continuously, and for each right answer given, they will earn 100 marks.

For each question asked, there are 4 options, namely A, B, C and D. There is no negative markings.

