# ESC-101L Internet & Web Basics Lab

This folder contains the Q1 Git/GitHub workflow notes, a semantic resume/portfolio page, and a native-validated student registration form.

## Files

- `index.html` — responsive personal resume and portfolio with all six required sections.
- `registration.html` — student registration form with labels, appropriate input types, meaningful `name` values, and browser validation.
- `styles.css` — shared responsive styling.

## Q1: Set up Git and GitHub; create, commit, and push a webpage

1. Install Git from [git-scm.com](https://git-scm.com/downloads), then confirm it is available with `git --version`.
2. Set the author name and email used on commits: `git config --global user.name "Your Name"` and `git config --global user.email "you@example.com"`.
3. Create a repository on GitHub with a meaningful project name such as `esc-101l-web-basics-lab`. Choose public or private as appropriate, and add a README if starting online.
4. Clone the repository with `git clone https://github.com/your-username/esc-101l-web-basics-lab.git`, then enter it with `cd esc-101l-web-basics-lab`. If starting locally instead, run `git init` and add the GitHub remote with `git remote add origin https://github.com/your-username/esc-101l-web-basics-lab.git`.
5. Create meaningful files such as `index.html`, `registration.html`, and `styles.css`. Preview the HTML pages in a browser and check the form labels and required fields.
6. Review the working tree with `git status`, stage the assignment with `git add index.html registration.html styles.css README.md`, and make a descriptive commit with `git commit -m "Add student portfolio and registration form"`.
7. Push the branch to GitHub with `git push -u origin main` (or substitute the branch name you are using). For later changes, stage, commit with a specific message, and push again.
8. Refresh the GitHub repository page and confirm the files and latest commit are visible.

## Personalize before submission

Public profile information confirms the name Yashasvi Sarswat and the XPlore group project. Other personal details are marked in brackets or with editable sample text. Replace those with accurate details before submitting. The registration form is a static HTML exercise: its GET submission demonstrates native validation and does not store records.
