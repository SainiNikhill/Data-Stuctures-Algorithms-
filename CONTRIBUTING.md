# ✨ Contributing Guidelines - DSA

Welcome to our collaborative DSA (Data Structures & Algorithms) practice repository! This guide explains how to contribute, update trackers, submit solutions, and maintain consistency.

---

## 🧩 Folder Structure
## 🧱 Project Structure
- --------tracker/
- --------Solutions/
-                  jt/
-                  nikhil/
-                  mayank/
- --------Topics/
- --------Resources/
- --------readme.md
- --------CONTRIBUTING.md


Each person should use their **own folder** to submit solutions.

---

## 🧠 How to Contribute

### 1. 🚀 Choose a Problem
- Pick a problem from `tracker.csv` or add a new one
- Update its **status**, **assigned to**, and **notes** in the CSV

### 2. 💡 Solve the Problem
- Create the solution in your own folder (e.g., `solutions/nikhil/`)
- Name the file clearly (e.g., `two-sum.java`, `valid-parentheses.py`)

### 3. 📈 Update the Tracker
- Open `tracker.csv`
- Update your row:
  - ✅ for Done
  - ❌ for Pending
  - 🔄 for In Progress
- Add notes if helpful (e.g., “used HashMap”)

### 4. 🔧 Commit and Push

```bash
# Always pull latest code first
git pull origin main

# Stage changes
git add .

# Commit message format:
# <your-name>: solved <problem-name>
git commit -m "nikhil: solved two sum"

# Push to main or create PR
git push origin main

###🗃️ File Naming Rules
Use lowercase with hyphens: kth-largest-element.py

Prefer camelCase inside code for variables/functions

Include comments in code if needed
