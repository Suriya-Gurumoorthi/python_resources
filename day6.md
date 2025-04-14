## 🕹️ Game 1: Guess the Number 🎯

### ✅ Question
Create a game where the computer randomly selects a number between 1 and 100, and the user has to guess it. After each guess, the program tells if the guess is too high, too low, or correct.

### 💡 Hints
- Use random.randint() to pick a number.
- Use while loop to repeat until correct.
- Use if, elif, else to compare guesses.


### 🧾 Procedure
- Import the random module.
- Generate a random number between 1 and 100.
- Use a while loop to repeatedly ask for guesses.
- Compare the guess:
- Too low → print "Too low!"
- Too high → print "Too high!"
- Correct → print success message & break loop


## 🕹️ Game 2: Rock, Paper, Scissors ✊🖐✌️

### ✅ Question
Build a game that lets a user play Rock-Paper-Scissors against the computer. First to score 3 wins is the winner.

### 💡 Hints
- Use random.choice() for computer move.
- Use if-elif to compare user vs computer.
- Keep track of scores using variables.
- Wrap computer choice in a function for better code structure.

### 🧾 Procedure
- Create a function get_computer_choice() that returns random choice.
- Use a while loop until either player reaches score 3.
- Compare moves:
- Rock beats Scissors
- Paper beats Rock
- Scissors beats Paper
- Update scores and print result.


## 🕹️ Game 3: Even or Odd Checker ➗

### ✅ Question
Create a game where the user inputs a number, and the program tells whether it's even or odd. The user can type 'exit' to stop the game.

### 💡 Hints
- Use % operator: if number % 2 == 0 → Even
- Use while True for infinite loop
- Use break to exit when input is 'exit'
- Use .isdigit() to validate input

### 🧾 Procedure
- Define a function check_even_odd() to return "Even" or "Odd".
- Use a loop to ask the user for input continuously.
- If input is 'exit', stop the game.
- If input is a number, check if it is even or odd.
- Print the result.
