# Exercise 0: Environment and Libraries

## Objective
Set up the environment for Python development.

---

## Task 1: Install Python

### Check if Python is already installed

Open your terminal and run:
```bash
python --version
```

or

```bash
python3 --version
```

### My Python version:
<!-- TODO: Write your Python version here. Example:
Python 3.11.5
-->

### Is Python installed?
<!-- TODO: Check one:
☐ Yes, Python is installed
☐ No, I need to install it
-->

---

### If Python is NOT installed:

**For macOS:**
```bash
brew install python3
```

**For Linux (Ubuntu/Debian):**
```bash
sudo apt update
sudo apt install python3
```

**For Linux (Fedora/RedHat):**
```bash
sudo yum install python3
```

**For Windows:**
Download from: https://www.python.org/downloads/
- Make sure to check "Add Python to PATH" during installation

---

## Task 2: Write and Execute a "Hello, World!" Program

### Step 1: Create a Python file

Create a file named `hello.py` in your prompt-basics folder.

### Step 2: Write the code

```python
# hello.py
print("Hello, World!")
```

### Step 3: Run the program

In your terminal, navigate to the prompt-basics folder and run:
```bash
python hello.py
```

or

```bash
python3 hello.py
```

### What I saw when I ran it:
<!-- TODO: Paste the output. Example:
Hello, World!
-->

### Did it work?
<!-- TODO: Check one:
☐ Yes, I see "Hello, World!" in the terminal
☐ No, I got an error (paste the error below)
-->

### If you got an error, paste it here:
<!-- TODO: Example:
python: command not found
OR
SyntaxError: invalid syntax
-->

---

## Task 3: Verify Your Setup is Complete

### Checklist:
- ☐ Python 3.9+ is installed
- ☐ I can run `python --version` or `python3 --version` successfully
- ☐ I created and ran hello.py successfully
- ☐ I saw "Hello, World!" printed in my terminal

---

## Optional: Set Up a Virtual Environment

Virtual environments help keep your Python projects isolated and organized.

### Create a virtual environment:
```bash
python3 -m venv venv
```

### Activate it:

**On macOS/Linux:**
```bash
source venv/bin/activate
```

**On Windows:**
```bash
venv\Scripts\activate
```

### You'll know it's activated when you see `(venv)` before your terminal prompt.

### To deactivate later:
```bash
deactivate
```

### Did you set up a virtual environment?
<!-- TODO: Check one:
☐ Yes, I created and activated a virtual environment
☐ No, I skipped this (that's okay for now)
-->

---

## Notes and Observations

<!-- TODO: Write any issues you faced or questions you have. Example:
- Had trouble finding where Python was installed
- Got a "command not found" error at first but fixed it by using python3 instead of python
- Virtual environment worked but not sure when I should use it
-->

---

## Completion Checklist

Before moving to Exercise 1, make sure:
- ✅ Python is installed and working
- ✅ You can run Python files from terminal
- ✅ You understand how to write and execute basic Python code

**Date completed:** _______________

**Ready for Exercise 1:** ☐ Yes ☐ No
