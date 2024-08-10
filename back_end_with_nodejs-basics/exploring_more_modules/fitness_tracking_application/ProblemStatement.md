Problem statement
Participate in developing a fitness tracking application, emphasizing progress tracking, event emission, and sending congratulatory messages upon achieving fitness goals. This task offers hands-on experience in building interactive features and understanding parameters related to fitness progress.

Objectives

i) Implement the addExercise function to update the progress.
ii) Emit a goalReached event when the user reaches their fitness goal.
iii) Set up a listener to send a congratulatory message when the goal is reached.

Notes:
The variables used in the program are as follows:
progress: Represents the current amount of calories the user has burned through exercise.
goal: Denotes the total amount of calories the user aims to burn.
tracker: An instance of the FitnessTracker class, used to manage and track user's exercise progress towards the goal.
The addExercise method is expected to take an exercise object as a parameter with the following structure:
name: a string representing the name of the exercise
caloriesBurned: a number representing the amount of calories burned during the exercise
Research how to emit events in your chosen programming language.
Explore examples of sending messages to users to understand the required implementation.
