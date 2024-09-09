

### **Introduction:**

If you’ve ever wondered how developers keep track of their code, collaborate on projects, or revert to previous versions, then this video is for you!

By the end of this session, you’ll know:
- What Git and GitHub are.
- How they work together.
- Some basic commands to get started.

Let’s dive right in!

---

### **1. What is Git?**

So, what is **Git**? Git is a **version control system**. That might sound complicated, but it’s pretty simple. Imagine you’re working on a project and want to save your progress at different points, like creating checkpoints in a video game. Git helps you do just that! It keeps track of every change you make to your code, so you can **revert to older versions**, **collaborate** with others, and even **experiment** without worrying about breaking everything.

Git runs on your **local machine**. You can use it even without an internet connection to track changes to your project files.

---

### **2. What is GitHub?**

Now that you know what Git is, let’s talk about **GitHub**. GitHub is a **cloud-based platform** that lets you store your Git repositories online. Think of it as a remote backup for your code that also allows you to **collaborate** with others from anywhere in the world. 

GitHub is like social media for your code:
- You can **share** your projects with others.
- **Contribute** to open-source projects.
- **Collaborate** with teammates on the same project.

---

### **3. How do Git and GitHub work together?**

Git and GitHub work hand-in-hand:
- **Git** manages the versions of your project on your local machine.
- **GitHub** helps you back it up online and collaborate with others.

Think of Git as your personal version control tool and GitHub as the online hub where you can showcase, share, and collaborate on projects with others.

---

### **4. Git Basics:**

Now, let’s get hands-on with some basic Git commands. You can use these commands to manage your projects locally with Git.

#### **1. `git init`**
The first command you’ll use is:
```bash
git init
```
This initializes Git in your project folder, meaning Git will start tracking the changes you make.

#### **2. `git add`**
Once you’ve made changes to your files, you need to tell Git which changes you want to track. This is done using:
```bash
git add <filename>
```
Or, to add all files:
```bash
git add .
```

#### **3. `git commit`**
After staging your changes with `git add`, you need to save them in Git’s history. This is called committing:
```bash
git commit -m "Write a commit message here"
```
The message helps you describe what changes you’ve made.

#### **4. `git status`**
Want to see what changes have been made or what files are being tracked? Use:
```bash
git status
```
This will give you an overview of your current project state.

---

### **5. Pushing to GitHub:**

After working with Git locally, the next step is to push your code to **GitHub** so it’s backed up and others can see or contribute.

Here’s how to do it:

#### **1. Create a Repository on GitHub:**
- Go to GitHub and click on "New Repository."
- Give your repository a name, and click "Create Repository."

#### **2. Link Your Local Project to GitHub:**
To link your local project to your GitHub repository, use the following command:
```bash
git remote add origin https://github.com/your-username/your-repo-name.git
```

#### **3. Push Your Code:**
To push your local changes to GitHub, run:
```bash
git push -u origin master
```
Now, your code is available online!

---

### **6. When to Use Git and GitHub:**

So, when should you use Git and GitHub?

- **Working on Personal Projects:** Git helps you keep track of your code, and GitHub serves as a backup.
- **Collaborating with Others:** Whether you're working with a team or contributing to an open-source project, GitHub is a great way to manage changes.
- **Experimenting Safely:** With Git, you can create separate branches for experiments and merge them back into the main project only when you're happy with the results.

