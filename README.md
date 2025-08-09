---

# HabitPy

**Track your habits, analyze your progress, and stay motivated—all from your terminal!**

## Features

- 📅 **Daily & Weekly Tracking:** Log your habits (only numbers)
- ✏️ **Custom Habits:** Add, show, or delete any habit you want to track.
- 📈 **Visualize Progress:** Instantly generate beautiful graphs (with dark mode!) for your week, month, or year.
- 🎉 **Motivational Cheers:** Get random motivational messages to keep you going.
- 📤 **Export Data:** Export all your habit data to CSV for use in Excel, Sheets, or anywhere else.
- 🛠️ **Easy Reset:** Reset your data and start fresh anytime.

---

## Installation

### 🔧 Prerequisites

Before building or running HabitPy, create a virtual environment and install dependencies:

```bash
# Clone the repo
git clone https://github.com/asuntx/habitpy.git
cd habitpy

# Create and activate virtual environment
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# Install dependencies
pip install .
```

---

### 🚀 Option 1: Build and Install from Source (Recommended)

note: \* is the version and name it might change so just copy the name of the whl file

```bash
# Build the distribution
python -m build

# Install the built package globally
pip install dist/habitpy-*.whl
```

---

### ⚡ Option 2: Use pipx (Recommended for CLI tools)

```bash
# Build the distribution
python -m build

# Install with pipx (ensures global availability)
pipx install dist/habitpy-*.whl
```

---

### 🧪 Option 3: Development Installation

#### With pip (editable mode)

```bash
# Already inside .venv
pip install -e .
```

#### With uv

```bash
uv sync
uv run habitpy setup
```

#### With pipx (editable mode)

```bash
pipx install -e .
```

---

## 🕹️ Usage

First, set up your tracker:

```bash
habitpy setup
```

Then, use the commands:

- `habitpy track <habit_name[optional]>` — Log today’s habits
- `habitpy create <habit_name>` — Add a new habit
- `habitpy show` — List all habits
- `habitpy delete <habit_name>` — Remove a habit
- `habitpy graph week|month|year` — Visualize progress
- `habitpy export` — Export data to CSV
- `habitpy reset` — Delete all data and start over

---

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/W7W318WNN8)

---
