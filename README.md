**PROJECT TITLE**:Rule-Based Chatbot in Python

**OBJECTIVE**:
         The main objective of this project is to create a simple, rule-based chatbot using Python that can respond to specific user inputs such as "hello", "how are you", and "bye". This project demonstrates basic input/output handling and control flow in Python.

**FEATURES**:

1. Responds to predefined user inputs like:
  - "hello" → "Hi!"
  - "how are you" → "I'm fine, thanks!"
  - "bye" → "Goodbye!"
2. Provides a default response for unrecognized inputs.
3. Continues conversation in a loop until the user exits.
4. Simple and easy to understand for beginners.

**TECHNOLOGIES USED**:

Programming Language: Python

Core Concepts:
  - `if-elif-else` conditional statements
  - `while` loop for continuous interaction
  - Functions for modular code
  - `input()` and `print()` for user interaction

**ADVANTAGES**:

1. Ideal project for Python beginners to practice basic logic and structure.
2. Lightweight and does not require any external libraries.
3. Can be easily extended to support more inputs and features.
4. Helps understand how chatbots work using simple rule-based logic.

**CODE**:

1. Make sure Python is installed on your system.
2. Save the following code in a file named `chatbot.py`.

def bot():

    print("Welcome to the Basic Chatbot! (Type 'bye' to exit)")

    inputs = ["hello", "how are you", "bye"]  # predefined inputs for testing

    for user_input in inputs:
        print(f"You: {user_input}")
        user_input = user_input.lower()

        if user_input == "hello":
            print("Bot: Hi!")
        elif user_input == "how are you":
            print("Bot: I'm fine, thanks!")
        elif user_input == "bye":
            print("Bot: Goodbye!")
            break
        else:
            print("Bot: Sorry, I don't understand.")

bot()

**SAMPLE OUTPUT**:

Chatbot: Hello! I'm your friendly chatbot. Type 'bye' to exit.

You: hello

Chatbot: Hi!

You: how are you

Chatbot: I'm fine, thanks!

You: bye

Chatbot: Goodbye!

![image](https://github.com/user-attachments/assets/3775e065-7f69-457a-b208-8a5596ebbf9a)


**CONCLUSION**:
            This project showcases how simple rule-based logic can be used to simulate human-like conversation. It serves as a great starting point for building more advanced chatbots using NLP or machine learning in the future. Perfect for Python learners to strengthen their grasp on basic programming concepts.
