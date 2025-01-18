# Collaborative Project: GitHub Workflow

Welcome to the Collaborative Project! This assignment is designed to help you practice using GitHub collaboratively as a team. You will learn to work on branches, create pull requests, and merge changes into the main branch.

---

## **Learning Objectives**
1. Understand how to collaborate using Git and GitHub.
2. Learn to manage branches and resolve conflicts.
3. Practice creating and reviewing pull requests.
4. Work as a team to complete a project.

---

## **Project Overview**
For this project, your team will collaboratively develop a simple application (e.g., a calculator, to-do list, or mini-game). Each member will contribute to specific features and follow GitHub best practices.

---

## **Instructions**

### **Part 1: Setting Up**
1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   ```
2. **Assign Roles:** Decide team roles (e.g., Project Lead, Feature Developers, Tester). Document roles in the `docs/team-roles.md` file.
3. **Create Your Branch:**
   - Each member should create a branch for their assigned feature.
   ```bash
   git checkout -b <feature-name>
   ```

---

### **Part 2: Development**
1. **Feature Implementation:**
   - Complete your assigned task in your branch. Use the provided files in the `src/` directory as a starting point.
2. **Commit Changes:**
   - Regularly commit your changes with meaningful messages:
     ```bash
     git add .
     git commit -m "Implemented <feature-name>"
     ```
3. **Push Your Branch:**
   - Push your branch to the remote repository:
     ```bash
     git push origin <feature-name>
     ```

---

### **Part 3: Collaboration**
1. **Pull Requests:**
   - Create a pull request (PR) to merge your branch into the `main` branch.
   - Provide a detailed description of your changes.
2. **Code Review:**
   - Review at least one teammate's PR and provide constructive feedback.
3. **Conflict Resolution:**
   - If merge conflicts occur, resolve them as a team before merging.
4. **Merge Changes:**
   - Once approved, merge your branch into `main`.

---

### **Part 4: Documentation**
1. Update the `docs/project-summary.md` file with:
   - An overview of the project.
   - Features implemented by each member.
   - Any challenges faced and how they were resolved.
2. Include screenshots or GIFs of the final application in the `docs/` folder.

---

## **Submission Guidelines**
1. Ensure all changes are merged into the `main` branch.
2. Verify that the repository includes:
   - A completed `src/` directory with the working application.
   - Updated documentation in the `docs/` folder.
3. No additional submissions are needed; all contributions will be tracked via GitHub.

---

## **Grading Criteria**
| Task                               | Points |
|------------------------------------|--------|
| Branch creation and usage          |   10   |
| Feature implementation             |   30   |
| Code review and conflict resolution|   30   |
| Documentation                      |   20   |
| **Total**                          | **100**|

---

## **Folder Structure**
```
collaborative-project-template/
├── README.md
├── .gitignore
├── src/
│   ├── main.py        # Starter script
│   ├── utils.py       # Helper functions
├── docs/
│   ├── team-roles.md  # Team roles and responsibilities
│   ├── project-summary.md  # Project overview and documentation
```

---

## **Help & Resources**
- [Git Branching Basics](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging)
- [GitHub Pull Requests](https://docs.github.com/en/pull-requests)
- Reach out to your instructor for assistance.

---

Happy Collaborating! 🚀
