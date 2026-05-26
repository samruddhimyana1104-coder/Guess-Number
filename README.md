Guess The Number Game 🎯

A simple Python-based number guessing game where the computer generates a random number between 1 and 100, and the player tries to guess it correctly.

📌 Features
Random number generation
User input handling
Hint system (Higher/Lower)
Attempt counter
Beginner-friendly Python project

🛠️ Technologies Used
Python
Random Module

💻 Code
import random

n = random.randint(1,100)
a = -1
guesses = 0

while(a != n):
    guesses += 1
    a = int(input("Guess the Number: "))

    if(a > n):
        print("Lower number please")

    else:
        print("Greater number Please")

print(f"You have guessed the number correctly in {guesses} attempt")
🚀 How to Run
1️⃣ Clone the Repository
git clone https://github.com/your-username/guess-the-number.git
2️⃣ Open the Project Folder
cd guess-the-number
3️⃣ Run the Program
python guess.py

🎮 Example Output
Guess the Number: 50
Lower number please

Guess the Number: 25
Greater number Please

Guess the Number: 37
You have guessed the number correctly in 3 attempt

📂 Project Structure
guess-the-number/
│── guess.py
│── README.md

📖 Learning Outcomes
This project helps beginners understand:

While loops
Conditional statements
User input handling
Random number generation
Basic game logic in Python

🤝 Contributing
Contributions are welcome! Feel free to fork this repository and improve the project.
