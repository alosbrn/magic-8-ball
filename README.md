# Magic 8 Ball

A simple Python program that simulates the behavior of a Magic 8 Ball. The user asks a yes-or-no question, and the program responds with a randomly selected answer from a list of twenty possible responses.

## Features

* Prompts the user to ask a question.
* Randomly selects one of twenty Magic 8 Ball responses.
* Includes affirmative, non-committal, and negative answers.
* Validates user input to prevent empty questions.
* Uses Python's built-in `random` module.

## Requirements

* Python 3.x

No additional libraries are required.

## Usage

1. Open the file 'magic-8-ball.ipynb' in Jupyter Notebook.
2. Run all cells.
3. Enter a yes-or-no question when prompted:

```text
Ask the Magic 8 Ball a yes or no question: Will I pass my exam?
```

4. Receive a random response:

```text
Most likely.
```

If no question is entered, the program will display:

```text
Try asking a question next time!
```

## Example Responses

| Affirmative         | Non-committal              | Negative             |
| ------------------- | -------------------------- | -------------------- |
| It is certain.      | Reply hazy, try again.     | Don't count on it.   |
| It is decidedly so. | Ask again later.           | My reply is no.      |
| Without a doubt.    | Better not tell you now.   | My sources say no.   |
| Yes definitely.     | Cannot predict now.        | Outlook not so good. |
| You may rely on it. | Concentrate and ask again. | Very doubtful.       |
| As I see it, yes.   |                            |                      |
| Most likely.        |                            |                      |
| Outlook good.       |                            |                      |
| Yes.                |                            |                      |
| Signs point to yes. |                            |                      |


## Learning Objectives

This project demonstrates:

* Creating and using Python lists
* Generating random numbers
* Accessing list elements by index
* Accepting user input
* Using conditional statements (`if` / `else`)
* Basic input validation

## Disclaimer

This README file has been generated using the help of an LLM. All code contained within this repository is my own.
