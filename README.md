# 100hires-portfolio-project

## Overview
This project documents the setup of AI-assisted development tools using Cursor IDE, Claude Code, and Codex.

The goal is to demonstrate independent learning, problem-solving, and ability to work with AI tools.

---

## Tools Installed
- Cursor IDE
- Claude Code extension
- Codex extension
- Git (with Git Bash)

---

## Steps Completed

1. Installed Cursor IDE to provide a development environment that integrates AI-assisted coding workflows.
2. Installed Claude Code extension to enable AI-assisted coding and reasoning inside the IDE.
3. Encountered Git Bash error → installed Git to satisfy system-level dependency required by Claude Code on Windows.
4. Configured Git (user.name & user.email) to allow proper commit tracking and version control identity.
5. Installed Codex extension to expand AI capabilities and compare outputs across tools.
6. Created GitHub repository to store and version control the project.
7. Initialized project and added README.md to document the process clearly.
8. Committed and pushed to GitHub to complete the full development workflow.

---

## Issues Encountered & Solutions

### 1. Claude Code Error (Git Bash Missing)
- Error: Claude Code requires git-bash
- Solution: Installed Git from official website

**Insight:**  
This issue highlighted that some AI tools depend on underlying system environments, not just installation. Proper environment setup (like Git Bash) is critical for tool functionality.

---

### 2. Git Not Recognized / Not a Repository
- Error: "not a git repository"
- Solution: Navigated to correct project folder and ran `git init`

**Insight:**  
This reinforced the importance of working within the correct directory context when using Git. Version control is tied to project structure, not just commands.

---

### 3. Git Identity Unknown
- Error: Git required user.name and user.email
- Solution:
  - git config --global user.name "azrmkls"
  - git config --global user.email "azrmkls@email.com"

**Insight:**  
This step clarified how Git tracks authorship and why proper configuration is required before committing changes.

---

### 4. Authentication Issue
- Git required browser login
- Completed authentication via GitHub login

**Insight:**  
This showed how Git integrates with remote platforms like GitHub and requires authentication for secure operations such as pushing code.

---

## Key Learnings

- Debugging setup issues independently without step-by-step instructions
- Understanding full Git workflow (init, add, commit, push)
- Recognizing that AI tools require proper environment setup to function correctly
- Using AI tools with manual validation instead of blind reliance
- Identifying root causes of errors instead of just fixing symptoms

---

## Reflection

This project reinforced my ability to:
- Solve technical issues independently by breaking them into smaller problems
- Validate and interpret AI-generated outputs instead of relying on them blindly
- Adapt quickly when encountering unfamiliar tools and environments
- Maintain structured thinking while working through multiple setup issues

---

## What I Would Do Next

- Test Claude Code and Codex on a real-world task (e.g., generating and refining content or analysis workflows)
- Explore ways to automate setup using scripts to improve repeatability
- Build a simple project using these tools to evaluate their strengths and limitations in practical use
