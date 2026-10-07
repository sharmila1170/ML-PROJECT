# Gamified Learning Platform for Rural Education

A beginner-friendly ML-powered web platform for learning C, C++, Java, JavaScript and Python.

## Features
- Student registration/login
- Language and topic learning
- MCQ quizzes
- Coding practice
- XP, levels, badges and streaks
- Progress dashboard
- Weak-topic detection
- ML-based next-topic recommendation
- Performance prediction
- SQLite database

## Run
1. Install Python 3.11+.
2. Open this folder in terminal.
3. `pip install -r requirements.txt`
4. `python ml/train_model.py`
5. `python app.py`
6. Open `http://127.0.0.1:5000`

This is an academic prototype. Coding answers are stored and scored using simple rule-based checks; the ML component is used for learning analytics and recommendations.


## LeetCode-style Coding Section

Open `/coding` for the new coding area. It includes a problems list, search and filters, Easy/Medium difficulty, a split problem/editor workspace, Monaco editor, Run and Submit, visible and hidden tests, result statuses, solved state, XP reward, and submission history. Python is the working execution language in this first version; Java/C/C++/JavaScript are shown in the UI as planned language options.

Run with `pip install -r requirements.txt` then `python app.py`.

Security: the included judge is intended for local/demo use. A public deployment should replace it with a hardened container/VM sandbox with CPU, memory, process, filesystem and network restrictions.
