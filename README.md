# SP26_HAP455_Week2
Assignment 2.1
## Introduction to Python for Health Applications  
## Collaborative GitHub Programming Assignment

This assignment teaches:
- Basic Python programming
- Writing and calling functions
- GitHub collaboration (branches, commits, pull requests, merging)

You will work in a **shared GitHub repository**, similar to real-world health tech projects.

---

## Assignment Objective

Each student must:
- Add ONE Python function named using `lastname_firstname`
- Print health-related information
- Commit and push changes
- Create a Pull Request (PR)
- Merge into `main` without conflicts

---

## Required Software

- Python 3.x
- Git
- GitHub account

## Check Git installation:
```
git --version

git clone https://github.com/PulseInProd/SP26_HAP455_Week2
cd SP26_HAP455_Week2

git checkout main
git pull origin main

git checkout -b lastname_firstname

git branch

```

## Edit the Python File
     1. Creates ONE function
     2. Names it lastname_firstname
     3. Prints a health-related message or data
     4. *** DOES NOT modify other student functions ****
     5. Save the file

## Run the Program
```
   python assignment.py

   Confirm:

        Your function runs

        Output prints correctly

        No errors occur
```
## Save, Commit, and Push Changes

After editing `assignment2.py`, save the file in your editor.

Check the status of your changes:
```
git add -A

git commit -m "Add health function for lastname_firstname"

git push origin lastname_firstname

```

Merge the Changes

```
git status

git checkout main

git pull origin main

git checkout lastname_firstname

git merge main

```

Fix Conflicts Locally (if Any)

```
git add health_app.py
git commit -m "Resolve merge conflicts"
git push origin lastname_firstname

```

Merge Into main

```
Once GitHub.com if no conflicts:

Click Merge Pull Request

Click Confirm Merge

```

> ⚠️ **IMPORTANT NOTE**
>
> - **Do NOT overwrite, modify, or delete any other student’s function**
> - Only add **your own function** using your assigned name
> - Editing someone else’s code may cause merge conflicts and will result in point deductions
