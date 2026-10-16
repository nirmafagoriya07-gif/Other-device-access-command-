# Other-device-access-command-🎤 Voice Command Assistant using Python

📌 About the Project

This is a beginner-friendly Python project that works as a simple command-based assistant. It allows users to open YouTube and Google by entering commands through the keyboard.

The project uses Python's built-in "webbrowser" module to open websites in the default browser.

✨ Features

- Open YouTube using a command.
- Open Google using a command.
- Exit the assistant using the "exit" command.
- Simple and beginner-friendly Python code.

🛠️ Technologies Used

- Python
- "webbrowser" module

💻 How to Run the Project

1. Install Python or open Pydroid 3 on Android.
2. Copy the Python code into a new file.
3. Save the file as "voice_assistant.py".
4. Run the program.
5. Enter one of the following commands.

🎯 Available Commands

Command| Action
"youtube"| Opens YouTube
"google"| Opens Google
"exit"| Closes the assistant

🧑‍💻 Code

import webbrowser

print("🎤 Voice Command Assistant")
print("Keyboard microphone se bolo:")
print("YouTube, Google ya Exit")

while True:
    command = input("Command bolo: ").lower().strip()

    if "youtube" in command:
        print("YouTube khol raha hoon...")
        webbrowser.open("https://www.youtube.com")

    elif "google" in command:
        print("Google khol raha hoon...")
        webbrowser.open("https://www.google.com")

    elif "exit" in command:
        print("Assistant band ho gaya.")
        break

    else:
        print("Command samajh nahi aayi.")

📚 What I Learned

- Python loops ("while").
- Conditional statements ("if", "elif", "else").
- Taking user input with "input()".
- String methods such as "lower()" and "strip()".
- Opening websites using Python's "webbrowser" module.

🚀 Future Improvements

- Add real voice recognition using a microphone.
- Add more website commands.
- Explore voice-controlled app launching.

👩‍💻 Author

Created as a beginner Python project to practice programming and automation.

---

Note: This version accepts commands through keyboard input. It does not yet recognize spoken commands through the microphone.# Other-device-access-command-
