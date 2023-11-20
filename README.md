Problem Generation (problem_gen function):

Randomly selects two operands (left and right) and an operator (+, -, or *).
Creates a string expr representing the mathematical expression.
Evaluates the expression to get the correct answer using eval.
Returns a tuple containing the expression and the correct answer.
Game Execution:

Asks the user to press Enter to start the game.
Displays a message reminding the user that it's a timed quiz.
Main Loop:

Measures the start time.
Iterates through a loop for a total of total_problems (in this case, 15).
For each iteration, generates a new problem using the problem_gen function.
Asks the user to input their guess for the solution.
Checks if the user's guess matches the correct answer. If not, increments the wrong counter and continues to prompt the user until they provide the correct answer.
End of Game:

Measures the end time.
Calculates the total time taken to complete the quiz.
Prints a summary of the user's performance:
If no wrong answers, prints "EXCELLENT JOB!, YOU HAD 0 WRONG QUESTIONS."
If 1 to 3 wrong answers, prints "VERY GOOD JOB! YOU HAD X WRONG QUESTION/S" (where X is the number of wrong answers).
If more than 3 wrong answers, prints "GOOD JOB, CAN DO BETTER, YOU GOT A TOTAL OF X WRONG QUESTIONS."
Displays the total time taken to finish the quiz in seconds.
This code provides a simple and interactive way for users to practice solving basic math problems within a time constraint.
