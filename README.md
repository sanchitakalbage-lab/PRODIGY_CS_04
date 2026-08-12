# Keylogger Demonstration - Task 04

## Prodigy InfoTech Cyber Security Internship

### Objective
Create a basic keylogging demonstration that records user-entered text and saves it to a file.

### Features
- Records text entered by the user
- Saves the recorded input to a text file
- Allows the user to stop logging using the `EXIT` command
- Displays the recorded input
- Allows the log file to be downloaded

### Technologies Used
- Python
- Google Colab

### How It Works
The program accepts text directly from the user and records each entry into a file named `keylog.txt`.

The user can type `EXIT` to stop the logging process. The saved file can then be viewed or downloaded.

### Ethical Considerations
Keylogging can be used for legitimate security testing but can also violate privacy when performed without permission.

This project is designed only for educational purposes. It records text entered directly by the user and does not monitor or capture keystrokes from other applications.

Always obtain explicit user consent before collecting or logging keystrokes.

### How to Run
1. Open the notebook in Google Colab.
2. Run the code.
3. Enter text when prompted.
4. Type `EXIT` to stop logging.
5. View or download the generated `keylog.txt` file.

### Sample Output

```text
=== Keylogger Demonstration ===
This program logs only the text you enter below.
Type 'EXIT' to stop logging.

Enter text: Hello
Enter text: Testing my project
Enter text: EXIT

Logging stopped.
Keystrokes saved to: keylog.txt
