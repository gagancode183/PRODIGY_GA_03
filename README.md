PRODIGY_GA_03
Markov Chain Text Generator
A simple text generation tool using Markov chains.
This project demonstrates how to build a statistical model that predicts the next word or character based on the previous one(s), and then uses this model to generate random text that mimics the style of the input.

📌 Features
✅ Build a Markov chain model from input text

✅ Generate random text of arbitrary length based on the model

✅ Configurable order (i.e., how many previous words/characters are considered)

✅ Clean and beginner-friendly implementation in Python

✅ Interactive UI using Gradio

🛠️ How It Works
🎯 Training Phase
The input text is split into words or characters.

A dictionary (Markov chain) is built where:

Each key is a state (e.g., one word or a pair of words).

Each value is a list of possible next words or characters.

🧠 Generation Phase
Start with a random key from the chain.

Randomly select the next token from the list of possible continuations.

Continue the process for a specified number of steps to generate text.

🚀 Usage Instructions
🖥️ Run in Google Colab
Paste the full code from main.ipynb into a Colab notebook

Run all cells to launch the Gradio UI

Enter any sample text and generate results using:

Word-level mode

