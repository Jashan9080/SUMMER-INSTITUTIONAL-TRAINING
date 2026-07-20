# DAY-13 
Git & GitHub Basics | Git Bash Commands
##  Date
18 July 2026
### Objective
The objective of today's training was to understand the fundamentals of **Git** and **GitHub**, learn the purpose of version control, configure Git using Git Bash, and perform basic repository operations using commonly used Git commands.
### Topics Covered
### 1. What is Git?
Git is a **distributed version control system (DVCS)** used to track changes in source code during software development. It allows developers to manage different versions of files, collaborate with teams, and restore previous versions whenever required.
### 2. What is GitHub?
GitHub is a **cloud-based platform** that hosts Git repositories online. It provides features such as repository hosting, collaboration, issue tracking, pull requests, and project management.
### 3. Difference Between Git and GitHub
- Git is a version control software.
- GitHub is an online hosting platform for Git repositories.
- Git works locally on the computer.
- GitHub stores repositories on the cloud.
### 4. Version Control System (VCS)
A Version Control System helps developers:
- Track changes made to files.
- Restore previous versions.
- Collaborate with multiple developers.
- Maintain project history.
- Prevent accidental loss of code.
### 5. Git Repository
A Git repository is a folder where Git stores all project files and tracks every change made to them.
### 6. Local Repository vs Remote Repository
- **Local Repository:** Stored on the user's computer.
- **Remote Repository:** Stored on GitHub and accessible over the internet.
### 7. Git Bash
Git Bash is a command-line terminal for Windows that allows users to execute Git commands and manage repositories efficiently.
### 8. Git Configuration
Configured Git by setting:
- Username
- Email Address
These details are attached to every commit made by the user.
### Practical Performed
During today's practical session:
- Opened Git Bash.
- Configured Git username and email.
- Checked Git configuration.
- Created a new folder for Git practice.
- Initialized a Git repository.
- Created a sample text file.
- Checked repository status.
- Learned how files move from Untracked → Staged → Committed state.
- Understood cloning repositories from GitHub.
- Learned the basic concept of branches and merging.
### Git Commands Practiced
### Configure Username
```bash
git config --global user.name "Your Name"
```
### Configure Email
```bash
git config --global user.email "your@email.com"
```
### View Git Configuration
```bash
git config --list
```
### Initialize Repository
```bash
git init
```
### Check Repository Status
```bash
git status
```
### Clone Repository
```bash
git clone <repository-url>
```
### Stage Files
```bash
git add .
```
### Commit Changes
```bash
git commit -m "Initial Commit"
```
### View Commit History
```bash
git log
```
### Create New Branch
```bash
git branch branch-name
```
### Switch Branch
```bash
git checkout branch-name
```
### Merge Branch
```bash
git merge branch-name
```
### Concepts Learned
- Version Control
- Git Repository
- GitHub Repository
- Local vs Remote Repository
- Git Bash
- Repository Initialization
- Git Configuration
- Git Status
- Staging Area
- Commit
- Clone
- Branch
- Merge
- Commit History
### Learning Outcome
By the end of today's session, I was able to:
- Understand the purpose of Git and GitHub.
- Configure Git using username and email.
- Create and initialize a Git repository.
- Check repository status using Git Bash.
- Understand the Git workflow (Working Directory → Staging Area → Repository).
- Learn the purpose of cloning repositories.
- Understand basic branching and merging concepts.
- Perform basic Git operations through command-line interface.
### Conclusion
Today's training provided a strong foundation in Git and GitHub. I learned how version control helps developers manage projects efficiently and how Git Bash is used to perform repository operations. I also practiced essential Git commands such as initialization, configuration, status checking, cloning, staging, committing, and understood the concepts of branching and merging, which are important for collaborative software development.
