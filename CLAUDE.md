# CLAUDE.md

## Project
Coursework for the Microsoft Python Development Professional Certificate (Coursera).
Six courses, one directory each, numbered in program order:
01-python-fundamentals, 02-data-analysis-visualization, 03-automation-scripting,
04-web-development, 05-advanced-python, 06-project-development.

## Environment
- Python 3.14.6, managed via a project-local venv at ./venv (Homebrew Python, not system Python)
- Activate with: source venv/bin/activate
- Never run pip or python from outside the venv for this project

## Conventions
- One Jupyter notebook per course chapter/lesson
- Markdown cells carry narrative explanation; `#` comments handle line-level detail in code cells
- New chapter subdirectories get created inside the relevant course folder as coursework progresses

## Dependencies
- requirements.txt is generated via `./venv/bin/pip freeze > requirements.txt`
- Regenerate it after installing anything new; don't hand-edit version pins

## Do not
- Do not edit or commit anything under venv/ (gitignored)
- Do not delete or reorganize existing course folders without asking first
