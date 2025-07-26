# PRODIGY_GA_03
Markov Chain Text Generator
A simple text generation tool using Markov chains. This project demonstrates how to build a statistical model that predicts the next word or character based on the previous one(s), and then uses this model to generate random text that mimics the style of the input.

📌 Features
Build a Markov chain model from input text.

Generate random text of arbitrary length based on the model.

Configurable order (i.e., how many previous words/characters are considered).

Clean and beginner-friendly implementation in Python.

🛠️ How It Works
Training phase:

The input text is split into words or characters.

A dictionary (Markov chain) is built where each key is a state (e.g., one word or a pair of words), and the value is a list of possible next words/characters.

Generation phase:

Start with a random key from the chain.

Randomly select the next token from the list of possible continuations.

Continue the process for a specified number of steps.
