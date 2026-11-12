# Experiment 3: Practice Source Code Management on GitHub

## Aim
To push and manage source code using GitHub.

## Project file
- `registration.html` — a simple user registration form.

## Procedure
1. Create a GitHub account and a repository named `Experiment-3`.
2. Install Git and open Git Bash.
3. Configure Git:
   ```bash
   git config --global user.name "Your Name"
   git config --global user.email "your-email@example.com"
   ```
4. Clone the repository (replace USERNAME with your GitHub username):
   ```bash
   git clone https://github.com/USERNAME/Experiment-3.git
   cd Experiment-3
   ```
5. Copy `registration.html` into the repository folder.
6. Stage, commit, and push:
   ```bash
   git add registration.html README.md
   git commit -m "Add user registration form"
   git branch -M main
   git push -u origin main
   ```
7. Open `https://github.com/USERNAME/Experiment-3` and verify that the files appear.

## Result
The source code is prepared for version control. After the commands above are run successfully, the files will be committed locally and pushed to the GitHub repository.

## Note
This folder is a prepared project, not proof of a completed GitHub upload. The push must be performed while authenticated to the student's GitHub account.
