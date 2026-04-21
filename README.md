# Git for Beginners: Student Practice Repo
 
Welcome! This repo is part of the **Git & GitHub for Beginners** course. It's a safe space to practise the full fork and pull request workflow on a real GitHub repo.
 
## What you're doing
 
Inside this repo there's a `students/` folder. Your job is to add a single markdown file to that folder with a short "about me" style introduction. That's it.
 
Once your PR is merged, your file lives alongside everyone else's in the students folder and you'll have a real contribution to a public repo on your GitHub profile.
 
## The workflow
 
### 1. Fork this repo
 
Click the **Fork** button at the top right of this page. This creates your own copy of the repo under your GitHub account.
 
### 2. Clone your fork
 
On your forked repo, click the green **Code** button and copy the URL. Then in your terminal:
 
```bash
git clone <your-fork-url>
cd Git-for-Beginners-Students
```
 
### 3. Create a new branch
 
Don't work directly on `main`. Create a branch for your changes:
 
```bash
git checkout -b add-<your-name>
```
 
For example: `git checkout -b add-malvik`
 
### 4. Add your markdown file
 
Inside the `students/` folder, create a new file named after yourself (if you're name is already taken add a numerical suffix to ensure the file is unique):
 
```
students/<your-full-name>.md
```
 
For example: `students/malvik_vaghadia.md`
 
Fill it with whatever you like. A suggested template is below, but feel free to make it your own.
 
### 5. Commit and push
 
```bash
git add students/<your-name>.md
git commit -m "Add <your name> to students folder"
git push origin add-<your-name>
```
 
### 6. Open a pull request
 
Head to your fork on GitHub. You should see a prompt to open a pull request against the original repo. Click through, give it a short title, and submit.
 
Once I review and merge it, your file is live.
 
## Suggested markdown template
 
Copy this into your file and edit as you like:
 
```markdown
# About <Your Name>
 
## Where I'm from
A sentence or two about where you live or where you're from.
 
## What I do
What you do for work, study, or a hobby you're proud of.
 
## Why I'm learning Git
A line on what brought you to the course and what you're hoping to build.
 
## An interest outside of tech
Something non technical. Food, sport, music, travel, whatever you like.
```
 
## Ground rules
 
- **One file per student**, placed in the `students/` folder.
- **Keep it appropriate.** No spam, no promotional content, no offensive material.
- **Only edit your own file.** Don't touch other students' submissions or files outside `students/`.
- **Use a branch**, not `main`. This is part of the practice.
 
