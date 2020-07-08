# Practical Scripting with Python
## UNO Summer Techademy

### Join our Repl.it Classroom
If you have not yet done this, follow this link to join our classroom:
[https://repl.it/classroom/invite/s6sFivu](https://repl.it/classroom/invite/s6sFivu)

## Importing from GitHub
- In the top left of Repl.it, select **+ new repl**
- Change tabs to select **Import From GitHub**
- Paste the following URL into the box:
  - ***github.com/UNO-Babb/Python-Summer-02***

### Using Random in Python
There are many packages that other people have made that we can use in our python program. To do this, we just need to import the package.
```
import random
```
This will give us access to the random numbers feature. Here are a few of the built-in random functions that we will use.
**random.random()** - This will give us a random decimal between 0 - 1.
**random.randint(1, 100)** - This will return a random value between 1 and 100. We can change the low and high values.
**random.choice(list)** - This will pick a random value from a list. We need to have a list pre-made.

## DiceRoll.py
Create a program that rolls a 6 sided dice.
---
Extend that program so it rolls 2 dice and gives the total.

## DiceRoll2.py
In this program, we want to ask the user how many sides are on their dice. This allows for multiple sided dice rather than always having a six-sided die.
---
Extend this program to repeat multiple times

### Loops
If we want a program to repeat a task, we can setup a ***while*** loop. This loop will repeat as long as a given condition is True.
With any loop, there are 3 important steps.
- Create and initialize a variable.
- Create a loop condition
- Change the variable so the loop can eventually end.

#### Repeat n times
```
#initalize
count = 1

#test
while count < 10:
  print("Hello")
  #change
  count = count + 1

print("The loop is done")
```

#### Repeat until something happens
```
#initalize
play = "y"

#test
while play == "y":
  print("We are playing")
  #change
  play = input("Play again? (y/n): ")

print("Game over")
```

## Magic8Ball.py
Create a program that will allow the user to ask a question, then provide a random response like a Magic 8 Ball.

- A traditional Magic 8 Ball has 20 possible answers:
- As I see it, yes.
- Ask again later.
- Better not tell you now.
- Cannot predict now.
- Concentrate and ask again.
- Don’t count on it.
- It is certain.
- It is decidedly so.
- Most likely.
- My reply is no.
- My sources say no.
- Outlook not so good.
- Outlook good.
- Reply hazy, try again.
- Signs point to yes.
- Very doubtful.
- Without a doubt.
- Yes.
- Yes – definitely.
- You may rely on it.

You may select to use these or answers you have created. They key is that they are given a random answer to the question they ask.

How to create a list of possible answers:
```
answers = ["thing 1", "thing 2"] # Each item must be in quotes, separated by a comma.
```
Since we imported random at the top of our file, we can use the following code to select a random item from the list.
```
response = random.choice(answers)
```
---
### Until next class
- How could random program make your life easier?
- What else could we do with random and looping?

### Other examples:
https://repl.it/@JulieSunny/guessNumber#main.py
https://repl.it/@JulieSunny/Hangman#main.py 
