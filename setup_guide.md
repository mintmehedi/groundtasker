# 🚀 GroundTasker – Developer Setup Guide

This guide helps all team members get GroundTasker running locally on their machines.

---

## 🧰 Prerequisites (Install These First)

| Tool           | Mac                                | Windows                             |
|----------------|-------------------------------------|--------------------------------------|
| Node.js        | [Download](https://nodejs.org/)    | [Download](https://nodejs.org/)     |
| Git            | Pre-installed                      | [Git for Windows](https://git-scm.com/download/win) |
| Code Editor    | [VS Code](https://code.visualstudio.com/) | [VS Code](https://code.visualstudio.com/) |

To check if Node and Git are installed, open Terminal/Command Prompt and run:
```bash
node -v
git --version
```

---

## 🗂️ Cloning the Project

### Step 1: Open Terminal (Mac) or Git Bash/Command Prompt (Windows)

Navigate to a folder where you want to keep the project, then run:

```bash
git clone https://github.com/mintmehedi/groundtasker.git
cd groundtasker
```

---

## 📦 Installing Dependencies

Run the following to install all required packages:

```bash
npm install
```

---

## 🧪 Running the App

Start the development server with:

```bash
npm run dev
```

Now open your browser and visit:  
[http://localhost:3000](http://localhost:3000)

---

## 🧑‍💻 Branching and Git Workflow

To work on a new feature:

```bash
git checkout -b feature/your-feature-name
```

After you make changes:

```bash
git add .
git commit -m "Added XYZ feature"
git push origin feature/your-feature-name
```

Then go to GitHub and open a Pull Request.

---

## ❗Common Issues

### ❌ Tailwind or CSS Not Loading?

Make sure you didn’t delete `globals.css` or Tailwind-related setup inside `postcss.config.mjs`.

### ❌ Port 3000 already in use?

Run this to kill the process (Mac/Linux):
```bash
lsof -i :3000
kill -9 [PID]
```

Or just restart your machine.

---

## 🧠 Need Help?

Ping Mehedi on Discord or GitHub if you get stuck!
