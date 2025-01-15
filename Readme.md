# ChatBot Application

## Description
This project is a simple command-line chatbot application implemented in Python. The chatbot, named "Sam3oul," interacts with users by responding to their inputs based on predefined rules and random responses for unrecognized inputs.

## Features
- **Greetings**: Responds to "hello" and "bye" inputs.
- **Age Inquiry**: Shares the bot's age when asked "how old are you."
- **Time Inquiry**: Provides the current time when asked "what time is it."
- **General Inquiry**: Responds to "how are you."
- **Fallback Responses**: Offers random responses for unrecognized inputs.
- **Exit Command**: Type `exit` to end the chat session.

## Requirements
- Python 3.7 or higher

## How to Run
1. Clone the repository or copy the code to your local machine.
2. Open a terminal and navigate to the directory containing the `main.py` file.
3. Run the application using the command:
   ```bash
   python main.py
   ```
4. Interact with the chatbot by typing your inputs in the terminal.

## Example Interaction
```
Sam3oul is a bot who is 22 years old.
You: Hello
Sam3oul: Hey there!
You: How old are you?
Sam3oul: I'm 22 years old!!!
You: What time is it?
Sam3oul: The current time is 14:30:15.
You: Bye
Sam3oul: See ya!!!
You: Exit
Thank you for chatting with Sam3oul. Goodbye!
```

## Code Structure
### `ChatBot` Class
- **Attributes**:
  - `name` (str): The name of the chatbot.
  - `age` (int): The age of the chatbot.
- **Methods**:
  - `description()`: Returns a description of the chatbot.
  - `get_response(text)`: Analyzes user input and returns an appropriate response.
  - `run()`: Starts the chatbot interaction loop.

### `main` Function
- Creates an instance of the `ChatBot` class.
- Prints the bot's description.
- Starts the chatbot interaction.

## License
This project is open-source and available for personal and educational use. Feel free to modify and expand its functionality!

