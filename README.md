#  Team Intro — Git & GitHub Practice Repo

> A hands-on exercise for team members to learn the real-world GitHub collaboration workflow.

---

##  What is This?

This repository is a **practice ground** for learning Git and GitHub.  
Your task is simple — add your details to a shared file by following the proper GitHub workflow.

No shortcuts. No web editor. Just real Git commands, the way it's done professionally.

---

## 📋 Your Task

Add your details to [`team-members.txt`](./team-members.txt) by following the steps below.

---

## 🚀 Steps to Complete the Task

### 1. Install Git
Download from: https://git-scm.com/downloads  
Verify it works:
```bash
git --version
```

### 2. Configure Git *(one time only)*
```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

### 3. Clone This Repository
```bash
git clone https://github.com/<your-org>/team-intro.git
cd team-intro
```

### 4. Create Your Branch
```bash
git checkout -b member/<your-name>
```
**Examples:**
```
member/alice
member/rahul
member/rahul-sharma
```

### 5. Add Your Details
Open `team-members.txt` and add your details in the format shown in the file.  
Follow the exact format — do not change anyone else's entry.

### 6. Stage & Commit
```bash
git add team-members.txt
git commit -m "Add <your-name> details"
```

### 7. Push Your Branch
```bash
git push origin member/<your-name>
```

### 8. Raise a Pull Request
- Go to this repo on GitHub in your browser
- Click **"Compare & pull request"**
- Title your PR: `Add <Your Name> to team members`
- Click **"Create Pull Request"**
- Wait for the team lead to review and merge ✅

### 9. Sync After All Merges
Once everyone's PR is merged, run:
```bash
git checkout main
git pull origin main
```
You'll now see everyone's details in the file! 🎉

---

## ⚠️ Rules

| ✅ Do | ❌ Don't |
|---|---|
| Create a branch named `member/<your-name>` | Push directly to `main` |
| Follow the details format exactly | Edit anyone else's entry |
| Use Git commands in the terminal | Use the GitHub web editor (pencil icon) |
| Raise a Pull Request | Merge your own PR |
| Pull `main` after everyone merges | Skip the final sync step |

---

## 📁 File Structure

```
team-intro/
│
├── README.md          ← You are here
└── team-members.txt   ← Add your details here
```

---

## 💡 Why Are We Doing This?

| Step You Do | Concept You Learn |
|---|---|
| `git clone` | Getting a repo locally |
| `git checkout -b` | Branching |
| Edit the file | Making changes |
| `git add` + `git commit` | Staging & committing |
| `git push` | Pushing to remote |
| Raise a PR | Pull request workflow |
| `git pull` at the end | Syncing with the team |

This is the **exact same workflow** used by developers at companies worldwide. Master this, and you're ready for real projects.

---

## 🙋 Need Help?

Reach out to your team lead or post in the group chat.  
Remember — **every developer struggled with Git at first.** You've got this! 💪
