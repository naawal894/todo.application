📝 Simple CLI Todo App:
A lightweight, efficient Command Line Interface (CLI) utility built with Python. This tool helps you manage your daily productivity directly from your terminal.
✨ FeaturesAdd Tasks: 
Quickly log new entries.
View Tasks:
List all your current "To-Do" items.
Complete/Delete: Remove tasks once they are finished.
🛠️ PrerequisitesPython 3.
xClick Library: This app uses the Click framework for a better CLI experience.Bashpip install click
🚀 How to Use:
Running the AppYou can run the script using your favorite IDE (like VS Code) or directly via theterminal:
Bashpython todo.py [command]
Available CommandsCommandDescriptionaddAdds a new task. The app will prompt you to enter the text.tasksDisplays a list of all your current tasks with their IDs.
DoneMarks a task as complete and removes it. 
Prompts for the Task ID.
Pro Tip:If you want to see all available options at any time, just type:
Bashpython todo.py --help
