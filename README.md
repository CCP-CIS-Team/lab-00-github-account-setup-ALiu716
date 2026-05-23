# Lab 00 — GitHub Account Setup & Your First Commit
### CIS 288: Cloud Computing | CCP-CIS-Team | Summer 2026
**Professor Sonny J. Chang** | schang@ccp.edu | CBI C3-1V | 215-751-8747

---

## Why This Lab Matters

GitHub is the professional standard for showcasing your work. Every lab you complete this semester lives here — and when you finish CIS 288, you will have a real cloud portfolio that employers can see.

This lab gets you set up. It is the only one with this many steps. After this, every lab is just 4 commands.

**Estimated time:** 20-30 minutes (first-timers) | 10 minutes (if you have used Git before)

---

## Step 1 — Create Your GitHub Account

Already have a GitHub account? Skip to Step 2.

1. Go to https://github.com
2. Click Sign up
3. Use your CCP email (@myCCP.edu) — this matters for GitHub Education benefits
4. Choose a username that looks professional (e.g., firstname-lastname or flastname)
5. Verify your email address

Screenshot required: Your GitHub profile page (github.com/YOUR-USERNAME) showing you are logged in.

---

## Step 2 — Claim Your Free GitHub Education Benefits

1. Go to https://education.github.com/students
2. Click Get Student Benefits
3. Use your CCP email to verify student status
4. This unlocks GitHub Pro for free — private repos, extra storage, and more

This step can take 24-48 hours to approve. Start it now and keep moving.

---

## Step 3 — Install Git on Your Computer

Windows:
1. Download from https://git-scm.com/download/win
2. Run the installer — accept all defaults
3. Open Command Prompt or Git Bash and confirm:

    git --version

You should see something like: git version 2.x.x

Mac:
    git --version

If not installed, macOS will prompt you to install it automatically.

---

## Step 4 — Configure Git With Your Identity

Open Command Prompt, Git Bash, or Terminal and run these two commands:

    git config --global user.name "Your Full Name"
    git config --global user.email "your-email@myCCP.edu"

Confirm it saved:
    git config --list

---

## Step 5 — Accept This Assignment and Clone Your Repo

You already accepted this assignment (that is how you got here). Now clone it to your computer:

1. Click the green Code button at the top of this page
2. Copy the HTTPS URL
3. In your terminal:

    git clone https://github.com/CCP-CIS-Team/YOUR-REPO-NAME
    cd YOUR-REPO-NAME

---

## Step 6 — Fill In Your Info Below

Edit this README.md file and complete the table:

| Field | Your Answer |
|---|---|
| Full Name | Andy Liu |
| GitHub Username | ALiu716 |
| CCP Email | aliu18@student.ccp.edu |
| Operating System (Windows/Mac/Linux) | Windows |
| Date Completed | 05/23/2026 |

---

## Step 7 — Answer These Questions

Q1: In your own words, what is GitHub and why do developers use it?

    [ Github is a platform built around git which allows developers to store and manage projects. 
    It also acts as a version control system that can track changes in files.
    Developers use it because of the version control system and the ease of collaborating on projects. ]

Q2: What is the difference between Git and GitHub?

    [ The difference is that Git is just a tool to track changes in code locally. 
    However, Github differs because it is a cloud based platform that allows users to share their code with others. ]

Q3: Why would a future employer look at your GitHub profile?

    [ A future employer might look through a Github profile be cause it also can act as a portfolio. 
    They can see the projects that you've worked on and decide if you're a good fit for the job. ]

---

## Step 8 — Your First Commit and Push

Once you have filled in Steps 6 and 7, save the file and run:

    git add .
    git commit -m "lab00 complete - Your Full Name"
    git push

Then go to your repo on github.com and confirm your answers are visible. If you can see them — you are done.

---

## Screenshots to Attach

Drag these image files into your repo folder, then write the filename next to each item:

| Screenshot | Filename |
|---|---|
| Your GitHub profile page (logged in) | profile.png |
| git --version output in terminal | version.png |
| git config --list showing your name and email | config.png |
| Your repo on github.com after pushing | repo.png |

---

## Grading — 20 Points Total

| Item | Points |
|---|---|
| Info table completed | 4 pts |
| All 3 questions answered thoughtfully | 6 pts |
| At least 3 screenshots attached | 6 pts |
| Committed and pushed successfully | 4 pts |

Due: Before Week 2 class session.

---

## Troubleshooting

| Problem | Fix |
|---|---|
| git command not found | Install Git from git-scm.com first (Step 3) |
| Permission denied publickey | Use the HTTPS URL not SSH — see Step 5 |
| fatal not a git repository | Make sure you cloned first — see Step 5 |
| Push asks for username/password | Use your GitHub username + a Personal Access Token as the password. Go to GitHub Settings > Developer Settings > Personal Access Tokens |
| Cannot find your repo URL | Check your email for the GitHub Classroom invite or ask Professor Chang |

Still stuck? Email schang@ccp.edu with a screenshot of your error. Include CIS 288 Lab 00 in the subject line.

---

CIS 288 Cloud Computing — Summer 2026 | Community College of Philadelphia
