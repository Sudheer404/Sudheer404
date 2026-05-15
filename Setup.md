# 🚀 GitHub Profile Portfolio — Complete Setup Guide

---

## 📦 Folder Structure

Your repository should be incredibly simple. You only need these two files at the root level:
```
Sudheer404/                        ← Upload THIS entire folder as your repo
├── README.md                      ← Your profile page (auto-renders on GitHub)
└── SETUP.md                       ← This guide (optional to upload, but good for reference)

```

-----------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------

## ⚡ Step 1 — Create Your Profile Repository

1. Go to **https://github.com/new**
2. Repository name: **`Sudheer404`** ← This MUST match your GitHub username exactly to trigger the special profile feature.
3. Set the repository to **Public**.
4. ✅ Do **NOT** tick "Initialize with README" (we are uploading our own).
5. Click **Create repository**.

-----------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------

## 📤 Step 2 — Upload Files

### Option A — GitHub Web UI (Easiest)
1. After creating the repo, click the link that says **"uploading an existing file"**.
2. Drag and drop your `README.md` file.
3. Click **Commit changes** to the `main` branch.

### Option B — Git CLI
```bash
git init
git remote add origin [](https://github.com/Sudheer404/Sudheer404.git)
git add README.md
git commit -m "🚀 Initial portfolio setup with AI integration"
git branch -M main
git push -u origin main

-----------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------

Widget,Purpose,Update Frequency
Header Banner,Dynamic SVG gradient matching your color palette,Static
Typing Animation,Cycles through your core skills,Static
Working Panda,Replaces the snake; shows you actively seeking opportunities,Static GIF
GitHub Stats Card,"Pulls your commits, PRs, and issues",Auto (Every few hours)
Top Languages,"Shows your most used languages (Python, C#, etc.)",Auto (Every few hours)
Profile Views,Tracks hits to your GitHub page,Real-time


-----------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------

Changing Widget Colors

All widgets use your requested palette. If you want to tweak them, look for these hex codes in the image URLs:

Light Orange: FFB347

Light Blue: 87CEFA

Light Yellow: FFFACD

White: FFFFFF
```
 
## Profile Maintenance Guide

```
🛠️ SETUP.md — Profile Maintenance Guide
This guide makes it simple to manage and update your GitHub profile README.
```

## 🧩 Part 1: Profile Structure
```
The profile is divided into four main visual zones:

The Header: Custom greeting banner with real-time typing text animations.

The Links: Clean badges linking directly to your LinkedIn, GitHub, Email, Portfolio, and Instagram.

The Tech Matrix: A tabular showcase separating your core AI/ML tools from GenAI/Vector DB stacks.

The Code Narrative: An interactive, expandable experience section followed by an OOP Python class summarizing your skills.
```
## ⚙️ Part 2: How to Update Content
```
🔄 1. Changing the Animated Text
The moving text lines are generated via URLs. To update your focus areas, find the typing SVG links and update the lines= parameter:

Separate multiple lines using a semicolon (;).

Replace spaces with %20 or + to prevent URL breaks.

🛠️ 2. Adding New Tech Badges
To add a new tool or language to your tech stack table, insert a new badge image tag using this format:

HTML
<img src="https://img.shields.io/badge/TechName-0D1117?style=for-the-badge&logo=techlogo&logoColor=HEX_COLOR"/>

🐍 3. Updating the Python Class
When your focus shifts or you gain more experience, update the raw strings inside the custom SudheerBandaru Python class at the bottom of the README file.

🚨 Part 3: Layout Guardrails
Keep Tags Closed: Ensure all custom HTML elements like <table>, <tr>, <td>, and <details> are properly closed so the markdown layout doesn't break.
``` 
Mobile Responsiveness: Keep width properties for the header and separation lines at width="100%" so they auto-scale perfectly on mobile screens.