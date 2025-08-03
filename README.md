# Real-Work Coding Assessment

Welcome! You’ve been invited to complete a short, real-world coding challenge designed to reflect the kind of work you might actually do on the job.

This assessment is being delivered through Foretoken AI, a platform trusted by hiring teams to run realistic, AI-enhanced coding evaluations.

---

## 📋 What You Need to Know

- Your **screen and audio recording** has already started (via your browser).
- Please **do not close or refresh the assessment tab** — doing so will stop the recording and may void your submission.
- You may use **any AI tools** (e.g. ChatGPT, GitHub Copilot, etc.)
- This is a **solo** exercise — no pair programming or external help allowed.

If you encounter issues, contact our team at **[assessment@foretokenai.com](mailto:assessment@foretokenai.com)** immediately.

---

## 💻 What You’ll Work On

You’ll be working inside a small, realistic codebase in Node.js/Express. The goal is not to finish everything, but to make strong, thoughtful progress.

You’ll be working on the following 4 tasks — complete as many as you can within the time limit:

1. **Fix a Bug**  
   `GET /users/:id` currently returns a `404 Not Found` for all invalid user IDs.  
   Your task is to fix this behavior:
   - If the `id` is not in a valid [UUID v4 format](https://en.wikipedia.org/wiki/Universally_unique_identifier#Version_4_(random)), return a **400 Bad Request**
   - If the format is valid but the user doesn't exist, return **404 Not Found**
   - If the user exists, return the user
   Note: The users.json file is expected to contain valid UUID v4 IDs. Ensure your solution handles this expectation.

2. **Extend an API**  
   Add support for query filtering: `/users?status=active&team=marketing`

3. **Build a Feature**  
   Add `GET /users/inactive` to return users with no login activity in the last 30+ days.

4. **Write Tests**  
   Add integration tests for any endpoint.

---

## 📦 What to Submit

After the timer ends, the platform will ask you to:

1. 📁 Upload your modified project as a `.zip`
2. 🎤 Record a **short reflection video** (up to 2 minutes) in your browser

---

## 💡 What We’re Evaluating

We’re not just looking for perfect code. We’re looking at:
- Your ability to navigate a real codebase
- Your problem solving skills
- Coding skills as well as documentation clarity

---
Important Note on Documentation: This repository contains a wiki.md file. Please be aware that some information in wiki.md may be intentionally outdated or contradictory to simulate real-world scenarios where documentation might not always be synchronized with current requirements. Your ability to identify and navigate such discrepancies is part of the assessment.

Good luck — we’re excited to see your thinking and approach!