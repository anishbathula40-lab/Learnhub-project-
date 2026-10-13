# LearnHub — Course Enrollment Project

A responsive React + Vite course enrollment website demo.

## Features
- Responsive landing page and course catalog
- Search courses and filter by category
- Course details modal
- Demo sign-up and sign-in UI
- Enroll in courses and prevent duplicate enrollment
- Student dashboard with enrollment and progress tracking
- Mark lessons complete and update progress
- Data persists in browser `localStorage`
- No payment required; all sample courses are free

## Run locally
1. Install Node.js (LTS): https://nodejs.org/
2. Extract this project and open the folder in VS Code or Command Prompt.
3. Run `npm install`
4. Run `npm run dev`
5. Open the local URL shown by Vite, usually `http://localhost:5173`.

## Publish to GitHub
1. Sign in at https://github.com/
2. Click **New repository** and name it `course-enrollment-project`.
3. Create the repository (a README is not needed because this folder already has one).
4. In this folder, open Command Prompt and run:
   ```bash
   git init
   git add .
   git commit -m "Create LearnHub course enrollment project"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/course-enrollment-project.git
   git push -u origin main
   ```
5. Replace `YOUR-USERNAME` with your GitHub username. Your repository link will be:
   `https://github.com/YOUR-USERNAME/course-enrollment-project`

## Important demo limitation
Authentication is a front-end demonstration and is not secure production authentication. User records and enrollment/progress data are stored in this browser only. Before real student use, connect a backend/auth provider such as Supabase or Firebase, enforce server-side authorization, and add appropriate privacy/security controls.
