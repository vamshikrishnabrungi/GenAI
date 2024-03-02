# GenAI
This project explores the capabilities of generative AI models, specifically focusing on OpenAI's GPT (davinci-002 model), to automate the generation of code from natural language descriptions. Inspired by the recent surge in generative AI's popularity, this repository documents our journey through various experiments, from simple functions to more complex object-oriented programming tasks.

Project Overview
The goal of this project is to understand and showcase how generative AI can be leveraged to improve software development workflows, potentially reducing the time spent on routine coding tasks and allowing developers to focus on more complex problem-solving. Our experiments include generating Python code for mathematical operations and creating a Python class to represent a bank account, demonstrating the model's versatility and potential.

Getting Started
Prerequisites
Python 3.x
Access to OpenAI's API (requires an API key)
Installation

To run the experiments and generate code using OpenAI's model, follow these steps:

Save your OpenAI API key in a text file within a secure location.
Update the api_key_path variable in the script to point to your API key file.
Run the script with a desired prompt to generate code:
css
Copy code
python generate_code.py "Write a Python function to add two numbers."
Examples
Here are some examples of prompts used and the code generated by the model:

Prompt: "Write a Python function to add two numbers."

Generated Code:
python
Copy code
def add(a, b):
    return a + b
Prompt: "Create a Python class to represent a bank account. It should support deposit, withdrawal, and balance check methods, with an initial balance provided at the time of account creation."

Generated Code:
python
Copy code
class BankAccount:
    def __init__(self, initial_balance=0):
        self.balance = initial_balance
    
    def deposit(self, amount):
        self.balance += amount
    
    def withdraw(self, amount):
        self.balance -= amount

    
    def get_balance(self):
        return self.balance
Contributing
Contributions are welcome! If you have suggestions for improving the experiments or extending the project, please feel free to fork the repository, make your changes, and submit a pull request.



License
This project is licensed under the MIT License - see the LICENSE file for details.
