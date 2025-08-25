# Geekhaven FOSS Recruitment Task

Welcome to the Geekhaven FOSS recruitment challenge! We're excited to see how you tackle the tasks and demonstrate your GitHub, SSH, and scripting skills. Read carefully and execute your tasks with precision.

---

## 📚 **Task Overview**

Your goal is to:

- Manage GitHub repositories and permissions.
- Utilize Git hooks to validate commits.
- Override commit authorship.
- Test your tasks with Bash scripts.
- As a bonus, integrate GitHub Actions to automate workflow tasks.

---

## 🚀 **Task Steps**

### Step 1: Repository Setup (5 points)

1. **Create a private repository** on GitHub.
2. Add the following GitHub IDs as collaborators:
   - `Shivg2901`
   - `Gamin8ing`
3. Perform **a couple of commits** by pushing any of your previous project files to this new repository under the main branch.

### Step 2: Utilize Git hooks (20 points)

1. Create a **pre-commit hook** that logs the last 5 commands you run in a file named `task_commands.sh` in the repository.
2. Make sure this file is **not tracked** by Git.
3. Push this hook to the repository under the folder `hooks` and try it out.
4. Create a **post-commit hook** that logs the commit message and author details in a file named `commit_details.txt` in the repository.
5. Make sure this file is **not tracked** by Git.
6. Push this hook to the repository under the folder `hooks`.
7. At the end of the task,remove these hooks & commit these two files created by hooks inside the `hooks` folder.

### Step 3: Override Commits on a Different Branch (10 points)

1. Create a **new branch** and switch to it.
2. Override some previous commits by **changing the author name** and email (use any desired nickname and alternate email).
3. Push these changes back to your **private repository** under this new branch.

### Step 4: Write a Testing Bash Script (40 points)

Create another **Bash script** that tests whether the tasks perfornmed above are successfully executed. Make sure include **fun and colorful outputs** using **ANSI color codes**:

- Use **blue** for informational messages.
- Use **yellow** for warnings.
- Use **green** for success messages.
- Use **red** for errors.

## Bonus Tasks (Optional)

### Set Up GitHub Actions (15 points)

**Configure a simple GitHub Actions workflow** in your private repository. This workflow should use linting tools like `shellcheck` to check for errors in your scripts & set conditions to only run on desired branch.

### Step 5: Submit Your Work

Create a **JSON file** containing your details. The JSON file should include:

- Your Name
- Your Roll Number
- Your Email
- The link to your private GitHub repository

Also, push an image to your repository where all the tasks have been verified by your tester bash script.

---

## 📂 **File Naming and Submission Format**

1. Name your files as follows:
   - The script where commands were being logged: `task_commands.sh`
   - The testing script: `task_tester.sh`
   - The information JSON file: `info.json`
   - The GitHub Actions workflow file: `.github/workflows/task_workflow.yml`
   - The image file: `result.png`.
   - Public key: `deploy_key.pub`
   - Private key: `deploy_key`

2. **Create a pull request** on this repository on the main branch where you must make a folder with name as your *Enrollment Number*. Under that, there should be your `info.json` file.

Make sure your submission is neat and follows the required file names and structure. Any deviation might cost you valuable points in this competitive task!

---

## 🎯 **Submission Guidelines**

- Your private repository should have **proper collaborator permissions** for the IDs mentioned above.
- Make sure your Bash script runs seamlessly on any standard Linux/Unix environment.
- Pay attention to detail and ensure everything is automated as per the requirements.
- Do not use AI tools for completion of this task. We are looking for your skills and not the AI's. We know most of you might not have heard some of these tooling before, but that's the point of this task. To learn and implement new things. Learn concepts (here your AI might help you) and implement them on your own.

---

We’re looking forward to seeing your submissions! Best of luck and have fun with this challenge. 👾
Shall you have any doubts, feel free to contact either of the organizers to resolve them. Irrelevant doubts will not be entertained/will be ignored. You should try resolving them on your own first, and only if the solution is not immediately obvious or found to you, only then contact us. ([@Shivg2901](https://github.com/Shivg2901/) , [@Gamin8ing](https://github.com/Gamin8ing/)).

