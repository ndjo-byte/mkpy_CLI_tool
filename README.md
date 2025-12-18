# mkpy

A lightweight CLI tool to bootstrap Python projects with:
- virtual environments
- git
- GitHub repo creation via SSH
- sensible defaults

## Features

- One-command Python project setup
- Automatic git initialisation
- Optional GitHub repo creation via gh CLI
- SSH-based workflow
- Zero dependencies beyond Python and git

## Requirements

- macOS or Linux
- Python 3
- git
- GitHub CLI (`gh`) for remote creation (optional)

## Installation

```bash
git clone https://github.com/yourusername/mkpy.git
cd mkpy
chmod +x mkpy
mv mkpy ~/bin/
```

## Usage 

````bash
mkpy my_project
cd my_project
source venv/bin/activate
```

## Why this exists
I wanted a lean, transparent CLI tool that automates the creation of my Python projects. It optimises my agility and efficiency by reducing the delay between a project's inception and its implementation.
