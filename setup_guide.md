# 🚀 GroundTasker – Developer Setup Guide

This guide helps all team members get GroundTasker running locally on their machines.

---
We will use Next.js for the frontend and Tailwind CSS for styling. The backend will be handled by a separate API, which you can set up as per your requirements.
Note "" React JS and Next JS are different things, Next JS is a framework built on top of React JS.""
For more information on Next.js, check out the [Next.js Documentation](https://nextjs.org/docs/getting-started).

### First thing to do!!

- try to work on the vscode project directory terminal it will help you from directory conflict 
- Install Next Js while installing the next js select y for the src and tailwind css
- you will gonna work on the src folder we will later create and separate folder for the components & other pages
- you can use the tailwind css classes in the components and pages
- then run the project using npm run dev
- here if you face any issue just copy the error and paste it on the chat gpt before explaining the issue state about your system and what you are trying to do
- then again npm run dev and check the localhost:3000 or next js port 
- then install git in your system globaly
- clone the repo 
- add some changes in the read me for testing purpose or add something in the src folder
- then good to go for anyhing or issues use chat gpt is highly recommended 

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
