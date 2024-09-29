## CODSOFT INTERNSHIP TASK 1
## NUMBER GAME

*NAME*    :    ARUN KUMAR M

*COMPANY*  :  CODSOFT INFOTECH

*DOMAIN*  :  JAVA PROGRAMMING

*DURATION*  :  01 SEPTEMBER TO 30 SEPTEMBER 2024

## Number Guessing Game in Java

**Project Overview**

This Java project is a simple console-based number guessing game. The user tries to guess a randomly generated number within a specified range. The game provides feedback on whether the guess is too high, too low, or correct.

**Features**

1.Generates a random number between 1 and 100.

2.Prompts the user to guess the number.

3.Provides feedback on each guess (too high, too low, or correct).

4.Tracks the number of attempts.

5.Allows the user to play multiple rounds.

**Class Details**

*1. NumberGuessingGame Class*

*Attributes:*

*private int numberToGuess:* The number the user needs to guess.

*private int numberOfAttempts:* The number of attempts made by the user.

*private Scanner scanner:* Handles user input.

**Constructor:**

*public NumberGuessingGame():* Initializes the game by generating a random number and setting the number of attempts to zero.

**Methods:**

*1.public void play():* Starts the game and handles the main game loop.

*2.private void generateRandomNumber():* Generates a random number between 1 and 100.

*3.private void checkGuess(int guess):* Checks the user’s guess and provides feedback.

**2. Main Class:**

*Methods:*

public static void main(String[] args): Entry point of the program. Creates an instance of NumberGuessingGame and starts the game.

**Usage Instructions:**

**Clone the Repository:**

git clone https://github.com/yourusername/NumberGuessingGame.git
cd NumberGuessingGame

*Compile and Run:* Use a Java IDE (Eclipse, IntelliJ) or compile from the command line. Run the Main class to start the game.

*Follow Console Instructions:* Enter your guesses when prompted and receive feedback until you guess the correct number.

**Project Structure:**

NumberGuessingGame/

├── src/

│   ├── NumberGuessingGame.java

│   └── Main.java

└── README.md
