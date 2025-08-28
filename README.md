<div align="center" style="background-color:black; padding:20px; color:white; font-size:28px; font-weight:bold;">
FREE DevOps for Beginners Cohort with Pravin Mishra – Week 2: Learning Git & GitHub
</div>

---

## Introduction  

When I look back at my journey into tech, I can honestly say it hasn’t been easy. Coming from a background with **no IT knowledge**, every step has been both a challenge and a breakthrough. Many times I felt stuck, but I kept pushing, knowing that perseverance is the only way forward.  

That’s why I feel deeply grateful to have been selected for the **FREE DevOps for Beginners Cohort with Pravin Mishra**. Spending eight hours on a Saturday Zoom session learning Git and GitHub under his guidance felt like a real gift.  

Pravin is one of those rare teachers who not only explains concepts but also empowers you to *execute them with confidence*. His Udemy course is the foundation of our learning, and the way he breaks things down makes even complex topics feel achievable.  

This week’s session focused on **Git and GitHub** — tools that every developer and DevOps engineer simply cannot do without.  

---

## What is Git?  

Git is like a **time machine for your code**. Imagine you’re writing an essay: instead of erasing mistakes, Git saves every version. You can go back to an earlier version anytime, see what changed, and even undo mistakes.  

Here’s what I learned Git helps us do:  

- **Track changes in code over time**  
  You never lose your progress. Every save is recorded, so even if you mess up, you can go back.  

- **Work on separate branches without disturbing the main project**  
  Think of branches as *drafts*. You can try out new ideas without breaking the original work.  

- **Merge changes back together once features are tested**  
  After finishing your “draft,” you can combine it safely with the main version.  

- **Maintain a complete history of every change**  
  Nothing is lost. You can always check who did what, when, and why.  

---

## What is GitHub?  

If Git is the time machine, then GitHub is like the **museum where all the time machines live**. It’s an online platform where we can keep our Git projects safe, share them with others, and collaborate.  

GitHub provides:  

- **A cloud-based hosting service for Git repositories**  
  Instead of keeping your code only on your laptop, you store it online so you can access it anywhere.  

- **Collaboration features like pull requests, code reviews, and issue tracking**  
  This is how teams work together, suggest changes, and keep quality high.  

- **Integrations with CI/CD pipelines**  
  This means code can automatically be tested and deployed straight from GitHub — a big deal in DevOps.  

---

## Git vs GitHub – The Difference  

- **Git** → A tool you install on your computer to track and manage code.  
- **GitHub** → A website where Git repositories are stored, shared, and collaborated on.  

They’re like **pen and paper (Git)** vs **Google Docs (GitHub)**. One works offline, the other makes collaboration possible.  

---

## What I Learned About Git & GitHub  

This part was very hands-on for me, and I’ll try to explain it the way I understood it — as if I’m telling my 9-year-old cousin.  

### Installing Git  

- On **Linux** → `sudo apt-get install git`  
- On **Windows** → Download from [git-scm.com](https://git-scm.com)  
- Git Bash → A tool that makes Windows feel like Linux when using Git commands.  

It’s like setting up your tools before building something.  

---

### Git Configuration  

Before using Git, you introduce yourself so Git knows who is making changes.  

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"

Then you can check settings with:

git config --list


This step felt like putting my name tag on before entering class.

Initializing a Repository

To start tracking a project with Git:

git init


This creates a hidden folder called .git that stores everything. It’s like the project’s “memory card.”

Types of Git Repositories

Local Repository → Lives on your laptop. Only you can see it.

Remote Repository → Lives on GitHub. The world can see it (if you want).

For me, it’s like writing a story in my diary (local) vs publishing it online (remote).

Git Commands I Practiced

git status → Tells you what’s happening in your repo.

git add . → Prepares files to be saved.

git commit -m "message" → Takes a snapshot of your work.

git log → Shows history of all commits.

git push → Uploads changes to GitHub.

git pull → Brings updates from GitHub into your laptop.

Every one of these commands felt like unlocking a new tool in a game.

GitHub Features

On GitHub, I practiced:

Creating a repository.

Connecting my local repo to GitHub with git remote add origin.

Using HTTPS and SSH for authentication.

Opening pull requests, merging changes, and collaborating.

Code Tracking & .gitignore

Git tracks everything — but sometimes you don’t want it to. For example, private keys or unnecessary files.

That’s where .gitignore comes in. You tell Git what not to remember.

Example:

touch .gitignore


Inside, you can list files/folders Git should ignore.

Git with VS Code

Using Git inside VS Code made everything easier:

I could see changes visually.

I staged and committed files with just a click.

I managed branches without leaving the editor.

Extensions like GitHub Pull Requests and Issues even allow full collaboration from inside VS Code.

Why Git & GitHub Matter in DevOps

Without Git and GitHub, modern software development would collapse. They bring:

Version Control → No work is ever lost.

Branching & Merging → Try new ideas without risk.

Collaboration → Teams can work together from anywhere.

Code Reviews → Keeps quality high.

CI/CD Integration → Automates testing and deployments.

This showed me that Git and GitHub are not “extra tools” — they’re the foundation of DevOps.

Reflection

This week’s session was a turning point for me.

I went from struggling to even understand Git, to actually using commands, pushing code, and connecting with GitHub. More than just the “how,” I also learned the “why”: why version control matters, why GitHub is essential for collaboration, and how these tools fit into the bigger DevOps picture.

I’m humbled and grateful for the opportunity to learn from Pravin Mishra and our co-mentors. His patience, clarity, and gift for teaching inspire me to keep going.

The fact that there’s even a full session recording available on YouTube (https://lnkd.in/gfv6RJRa
) shows how much value he provides.

This is only Week 2 of the cohort, yet I already see how powerful these tools are. If learning Git and GitHub was this exciting, I can’t wait to see what we’ll explore in Week 3.
