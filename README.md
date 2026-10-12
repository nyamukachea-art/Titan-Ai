# Titan AI 🤖

### A Lightweight Python AI Assistant

Titan AI is a simple, rule-based conversational assistant built with Python. It is designed to demonstrate fundamental programming concepts while providing basic interactive features such as answering greetings, remembering a user's name during a session, displaying the current date and time, and performing mathematical calculations.

## ✨ Features

- **Conversational greetings:** Responds to greetings with randomized messages.
- **Name memory:** Remembers the name provided by the user during the current session.
- **Time and date:** Displays the current time and date.
- **Calculator:** Evaluates basic mathematical expressions.
- **Python information:** Provides a short introduction to Python.
- **Help command:** Lists the available commands.
- **Conversation history:** Stores user messages and AI responses in memory during execution.
- **Exit command:** Allows the user to end the program.

## 🛠️ Technologies Used

- Python 3
- `datetime` — retrieves the current date and time.
- `random` — selects randomized greeting responses.
- `re` — validates mathematical expressions.

## 🚀 Getting Started

### Requirements

- Python 3 installed on your computer or compatible device.
- A terminal or Python-compatible environment, such as Pydroid 3 on Android.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/titan-ai.git
   ```

2. Enter the project directory:

   ```bash
   cd titan-ai
   ```

3. Run the program:

   ```bash
   python titan_ai.py
   ```

Replace `YOUR-USERNAME` with your GitHub username. Save the Python source code as `titan_ai.py`, or change the command to match your filename.

## 💬 Example Usage

```text
========================================
        MINI AI ASSISTANT
========================================
Type 'help' to see what I can do.
Type 'exit' to close the program.

You: hello
Titan: Hello! How can I help you?

You: my name is Alex
Titan: Nice to meet you, Alex!

You: what is my name
Titan: Your name is Alex.

You: calculate 25 * 4
Titan: The answer is 100

You: exit
Titan: Goodbye!
```

## 📚 Available Commands

| Command | Description |
|---|---|
| `hello` | Displays a greeting |
| `my name is Alex` | Saves your name for the session |
| `what is my name` | Recalls your name |
| `time` | Displays the current time |
| `date` | Displays today's date |
| `calculate 25 * 4` | Calculates an expression |
| `python` | Provides information about Python |
| `help` | Lists available features |
| `exit` | Closes the assistant |

## 🧠 How It Works

Titan AI uses rule-based logic to interpret user input. It converts messages to lowercase, checks for specific keywords and phrases, and selects an appropriate response.

The project uses Python functions, conditional statements, lists, exception handling, regular expressions, and global variables to implement its features.

**Note:** Titan AI is a rule-based assistant, not a trained machine-learning model or a large language model. Its responses are limited to the patterns programmed into it.

## 🔮 Future Improvements

- Add a graphical user interface (GUI).
- Improve natural-language understanding.
- Save conversation history between sessions.
- Add more mathematical operations.
- Integrate a language model API for more flexible responses.
- Add unit tests and improved input validation.

## 🔒 Security Note

This project is intended for learning and experimentation. The calculator uses Python's `eval()` function after validating input. Although built-ins are restricted, this approach should not be considered a secure sandbox for untrusted input. A safer future implementation could use a dedicated mathematical expression parser.

## 🎯 Project Goal

The goal of Titan AI is to build programming skills and create a foundation for a more capable personal AI assistant.

## 👨‍💻 Author

Created as a personal Python learning project.

## 📄 License

This project is available for educational and personal experimentation. Add a license file if you want to specify permissions for reuse and distribution.
# Titan-Ai
