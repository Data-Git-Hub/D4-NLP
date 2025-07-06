# D4: Natural Language Processing (NLP) & Engage

[D4: Natural Language Processing (NLP) & Engage](https://github.com/Data-Git-Hub/D4-NLP)

## Introduction
In this project, I explore the fundamentals of Natural Language Processing (NLP) with a focus on sentiment analysis using Python libraries such as spaCy, spacytextblob, and requests. Sentiment analysis is a powerful technique used to extract subjective information from text, helping organizations interpret public opinion, customer satisfaction, and emotional tone at scale. The assignment involves setting up a clean Python environment, ensuring all dependencies are correctly installed, and verifying the ability to load and apply NLP tools. This foundational work prepares the environment for deeper text analysis tasks in future modules and introduces essential skills in handling real-world, language-based data in Python.

## Task

## Windows Setup Instructions

Open a PowerShell terminal in VS Code. 
Create local project virtual environment, activate it, and install packages. 
When asked to use the new .venv click yes. 

```shell
py -m venv .venv
.\.venv\Scripts\activate
py -m pip install --upgrade pip setuptools wheel
py -m pip install -r requirements.txt
```

---

## macOS/Linux Setup Instructions

Open a default terminal in VS Code. 
Create local project virtual environment, activate it, and install packages. 

```zsh
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install --upgrade pip setuptools wheel
python3 -m pip install -r requirements.txt
```

---

## Tell VS Code to use .venv

Open the Command Palette: Press Ctrl + Shift + P (Windows) or Cmd + Shift + P (Mac/Linux)
Then type: Python: Select Interpreter
Press Enter.

Look for the interpreter with .venv in the path.
Click on that interpreter to select it.
Confirm it's selected: You should see the Python version and .venv path in the lower-left status bar of VS Code.

---

## Working on the Project

Open the .ipynb Jupyter notebook file in VS Code. 
Run the entire notebook before you start to edit. 
As you make progress, use Git to add, commit, and push your work to your GitHub repo.

```shell
git add .
git commit -m "describe the change here"
git push -u origin main
```

---

## Authors

Contributors names and contact info <br>
@github.com/Data-Git-Hub <br>

---

## Version History
- D4 Init - 0.0 - Create D4-NLP.ipynb, requirements.txt; Modify README.md
## Test History