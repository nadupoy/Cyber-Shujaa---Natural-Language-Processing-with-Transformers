# 🕸️ Cyber Shujaa - Natural Language Processing with Transformers 🚀

This is my solution to the week 11 assignment in the Cyber Shujaa program for the **Data and AI Specialist** track.

## 🧭 Table of contents

- [🌟 Overview](#🌟-overview)
  - [The assignment 🎯](#the-assignment-🎯)
  - [Links 🔗](#links-🔗)
- [🛠️ My process](#🛠️-my-process)
  - [Built with 🧱](#built-with-🧱)
  - [What I learned 🧠](#what-i-learned-🧠)
  - [Continued development 🌱](#continued-development-🌱)
  - [Useful resources 📚](#useful-resources-📚)
- [👩🏽‍💻 Author](#👩🏽‍💻-author)

## 🌟 Overview

### The assignment 🎯

In this assignment, we were to apply our understanding of Natural Language Processing, demonstrating key concepts covered in class:

- Applying a pre-trained BERT model for sentence encoding using Hugging Face Transformers.
- Extracting token-level contextual embeddings.
- Demonstrating how BERT captures word meaning based on context (polysemy).
- Computing and interpreting cosine similarity between token embeddings.
- Explaining the importance of contextual embeddings in contrast to static word vectors.

We were to complete the following tasks:

1. We were given 5 sentence pairs. Add 5 new sentence pairs of our own to total 10.
2. For each pair, compute the cosine similarity using BERT embeddings.
3. Define a threshold of 0.7:
    - If similarity > 0.7 → predict the sentences are similar (label: 1)
    - If similarity is ≤ 0.7 predict not similar (label:0)
4. After computing predictions for all 10 pairs, calculate the accuracy based on your own manually assigned ground truth labels (1 for similar, 0 for not similar).
5. In our reports or notebooks, briefly explain:
    - How does BERT differ from traditional NLP approaches like Bag of Words or TF-IDF?
    - What is the role of the encoder in the BERT model, and how is it used in this assignment?
    - What are contextual embeddings? How are they generated and used in this code?
    - Why is the [CLS] token used for sentence similarity in this code?
    - What is cosine similarity, and why is it useful in comparing embeddings?

### Links 🔗

## 🛠️ My process

### Built with 🧱

### What I learned 🧠

**1. Creating a `python` `venv` on MacOS**

Modern macOS systems often use `python3` instead of just `python`.

Running the code below as in Windows OS resulted in a `python: command not found` error in the terminal:

```python
python -m venv natural_language_processing
```

The solution was to run the command using `python3` instead of just `python`:

```python
python3 -m venv natural_language_processing
```

### Continued development 🌱

### Useful resources 📚

## 👩🏽‍💻 Author

- LinkedIn - [Grace Sampao](https://www.linkedin.com/in/grace-sampao)
- GitHub - [@nadupoy](https://github.com/nadupoy)
- X - [@grace_sampao](https://x.com/grace_sampao)
- [Blog](https://nadupoy.github.io/)