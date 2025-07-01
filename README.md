![Developer at work](https://media.giphy.com/media/26tn33aiTi1jkl6H6/giphy.gif)

## Hi there 👋

Welcome to my GitHub profile! 🚀

I'm Heru Hendri, a passionate developer who loves building fun and useful projects.  
Check out my repositories for full project examples, including web apps, APIs, and more.

---

### 🎮 Play a Game: Guess the Number

![GitHub Snake](https://github.com/heruhendri/heruhendri/blob/output/github-contribution-grid-snake.gif?raw=true)

You can play a simple number guessing game right here in your browser!  
[Play the Game Online](https://heruhendri.github.io/guess-the-number/)  
Or try the code below in your terminal:

```python
import random

print("Welcome to Guess the Number!")
number = random.randint(1, 100)
attempts = 0

while True:
    guess = int(input("Guess a number between 1 and 100: "))
    attempts += 1
    if guess < number:
        print("Too low!")
    elif guess > number:
        print("Too high!")
    else:
        print(f"Congratulations! You guessed it in {attempts} tries.")
        break
```

---

### 📂 Featured Projects

- [Full Stack Web App](https://github.com/heruhendri/fullstack-webapp)  
  Modern web application with React and Node.js.

- [REST API Example](https://github.com/heruhendri/rest-api-example)  
  Simple and clean RESTful API with documentation.

- [Game Projects](https://github.com/heruhendri/game-projects)  
  Explore more games and interactive projects.

---

Feel free to connect or collaborate!  
📫 **Contact:** heruhendri@gmail.com  
😄 **Pronouns:** he/him  
⚡ **Fun fact:** I love learning new programming languages and frameworks!