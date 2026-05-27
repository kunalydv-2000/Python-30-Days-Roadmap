# 30 Days of Python Roadmap

A practical, GitHub-friendly **30-day Python learning roadmap** designed for beginners who want structure, daily momentum, and a small but real portfolio outcome at the end.

By the end of this roadmap, you will:
- understand core Python syntax and problem-solving patterns
- write functions, use files, handle errors, and organize code into modules
- work with environments, packages, tests, and project structure
- build a **mini project: Task Tracker CLI**
- maintain progress in a repository with one README per day

---

## Repository Structure

```text
python-30-days-roadmap/
├── README.md
├── day-01/README.md
├── day-02/README.md
├── ...
├── day-30/README.md
└── mini-project/
    └── task-tracker-cli/
        └── README.md
```

---

## Who This Is For

This roadmap is for you if you:
- are new to Python
- want a daily plan instead of random tutorials
- learn best by doing small exercises every day
- want a mini project you can showcase on GitHub

---

## How To Use This Roadmap

1. Create a GitHub repository.
2. Copy this folder structure into the repo.
3. Complete one day at a time.
4. Commit your notes, exercises, and code every day.
5. Update progress checkboxes as you finish each day.
6. Push your final mini project with screenshots or terminal examples.

---

## Recommended Daily Routine

- **15 min** review previous concepts
- **30-45 min** learn new material
- **30-60 min** code exercises
- **10 min** write notes in the day's README
- **5 min** commit changes to GitHub

---

## Weekly Milestones

### Week 1 — Python Foundations
Focus on syntax, variables, conditionals, loops, strings, and core collections.

### Week 2 — Functions, Files, and Structure
Learn functions, modules, errors, files, comprehensions, and object-oriented basics.

### Week 3 — Tooling and Intermediate Python
Use virtual environments, pip, testing with pytest, generators, standard library tools, and JSON/APIs.

### Week 4 — Mini Project Build
Plan, build, test, refactor, document, and publish a **Task Tracker CLI**.

---

## 30-Day Progress Tracker

- [ ] Day 01 — Setup, Python install, first script
- [ ] Day 02 — Variables, data types, input/output
- [ ] Day 03 — Operators and conditionals
- [ ] Day 04 — Loops and iteration
- [ ] Day 05 — Strings and string methods
- [ ] Day 06 — Lists and tuples
- [ ] Day 07 — Dictionaries, sets, weekly review
- [ ] Day 08 — Functions and parameters
- [ ] Day 09 — Modules, imports, reusable code
- [ ] Day 10 — Errors, exceptions, debugging
- [ ] Day 11 — File handling and context managers
- [ ] Day 12 — Comprehensions and cleaner code
- [ ] Day 13 — OOP basics: classes and objects
- [ ] Day 14 — OOP practice and dataclasses
- [ ] Day 15 — Virtual environments and pip
- [ ] Day 16 — Project structure and packaging mindset
- [ ] Day 17 — Testing with pytest
- [ ] Day 18 — Iterators and generators
- [ ] Day 19 — Useful standard library modules
- [ ] Day 20 — JSON and working with APIs
- [ ] Day 21 — Mini project planning and feature scope
- [ ] Day 22 — Project scaffold and data model
- [ ] Day 23 — CRUD operations in memory
- [ ] Day 24 — Save and load tasks with JSON
- [ ] Day 25 — CLI menu and user interaction
- [ ] Day 26 — Refactor into modules and classes
- [ ] Day 27 — Validation and error handling
- [ ] Day 28 — Tests and documentation polish
- [ ] Day 29 — Extra features and final cleanup
- [ ] Day 30 — Release, publish, and retrospective

---

## Mini Project: Task Tracker CLI

Build a command-line application that lets a user:
- add tasks
- list tasks
- mark tasks as complete
- delete tasks
- save tasks to a JSON file
- load tasks when the program starts
- optionally filter tasks by status or priority

### Suggested Final Features
- add a task with title and optional due date
- view all tasks
- view completed vs pending tasks
- update task status
- delete a task
- persist data in `tasks.json`
- basic test coverage for core functions

### Suggested Folder Structure for the Mini Project

```text
mini-project/task-tracker-cli/
├── README.md
├── main.py
├── task_tracker/
│   ├── __init__.py
│   ├── models.py
│   ├── storage.py
│   ├── services.py
│   └── cli.py
├── tests/
│   └── test_services.py
└── data/
    └── tasks.json
```

---

## GitHub Documentation Tips

To keep this repository strong for recruiters and future-you:
- write what you learned each day
- include code snippets and command examples
- link related files with relative Markdown links
- use task lists to track progress
- keep commits small and meaningful

Example commit messages:
- `day 05: practiced string slicing and formatting`
- `day 17: added first pytest tests`
- `day 24: persisted task tracker data with json`

---

## Setup Commands

### Create a virtual environment
```bash
python -m venv .venv
```

### Activate it
**macOS/Linux**
```bash
source .venv/bin/activate
```

**Windows**
```powershell
.venv\Scripts\activate
```

### Install pytest
```bash
python -m pip install -U pytest
```

---

## Suggested Rules for Yourself

- code every day, even if only for 20 minutes
- never skip documentation
- write at least one example per topic
- review weekly before moving ahead
- prefer small working programs over long passive study sessions

---

## Official References

- Python Tutorial: https://docs.python.org/3/tutorial/index.html
- Python Standard Library: https://docs.python.org/3/library/
- Virtual Environments: https://docs.python.org/3/tutorial/venv.html
- pip + virtual environments guide: https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/
- pytest getting started: https://docs.pytest.org/en/stable/getting-started.html
- GitHub Markdown basics: https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

---

## Completion Outcome

When you finish this roadmap, your GitHub repository should clearly show:
- 30 days of consistent learning
- documented progress
- practical Python exercises
- one completed beginner-friendly CLI project

That combination is enough to demonstrate discipline, growth, and hands-on Python practice.
