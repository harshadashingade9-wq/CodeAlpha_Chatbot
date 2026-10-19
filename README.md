# CodeAlpha_Chatbot

A simple rule-based chatbot built in Python as part of my CodeAlpha Python Programming Internship (Task 4).

## About the Project
The chatbot reads the user's message and replies using predefined rules. It keeps running in a loop until the user says goodbye.

## Features
- Replies to `hello`, `how are you` and `bye`
- Ignores capital letters and punctuation (`HI!!` works)
- Remembers the user's name (`my name is ...`)
- Tells the current time and date
- Tells random programming jokes
- `help` command shows what the bot understands
- Handles empty and unknown messages without crashing

## Concepts Used
- `if-elif` chains
- Functions
- `while` loop
- Input/output
- Strings and dictionaries
- `random` and `datetime` modules

## How to Run
1. Make sure Python 3 is installed.
2. Download or clone this repository.
3. Run:

```
python chatbot.py
```

## Sample Conversation
```
=== CodeBot ===
Type 'help' to see what I can do, or 'bye' to exit.

You: hello
CodeBot: Hi!

You: how are you
CodeBot: I'm fine, thanks! How about you?

You: my name is harshada
CodeBot: Nice to meet you, Harshada!

You: hello
CodeBot: Hi, Harshada!

You: bye
CodeBot: Goodbye!
```

## Author
Harshada Shingade
Python Programming Intern at CodeAlpha
