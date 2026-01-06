# Assignment Completion Instructions

## 📋 What You Need to Fill In

This document outlines all the placeholders you need to replace with actual information before submitting your assignment.

---

## 🔴 CRITICAL: Information You MUST Provide

### 1. Group Information

#### In `README.md`:
- `[ENTER_PROGRAMME_NAME]` → Your programme name (e.g., "ISM-02")
- `[ENTER_GROUP_NUMBER]` → Your group number (e.g., "01", "02", etc.)
- `[MEMBER_NAME]` → Replace with actual team member names (appears 4 times)
- `[REG_NUMBER]` → Replace with actual registration numbers (appears 4 times)
- `[GITHUB_USERNAME]` → Replace with actual GitHub usernames (appears 4 times)

#### In `scrum-overview.md`:
- `[YOUR_NAME]` → Replace with actual names in the Scrum Roles table (4 instances)
- `[REG_NUMBER]` → Replace with actual registration numbers (4 instances)
- `[TIME, e.g., 9:00 AM]` → Replace with your actual Daily Scrum time

#### In `sprint-plan.md`:
- `[ENTER_START_DATE]` → Sprint start date (e.g., "2025-01-01")
- `[ENTER_END_DATE]` → Sprint end date (e.g., "2025-01-15")
- `[Developer 1]` → Replace with actual developer name (appears in Sprint Backlog table)
- `[Developer 2]` → Replace with actual developer name (appears in Sprint Backlog table)
- `[ENTER_TEAM_CAPACITY]` → Total team capacity in hours (optional but recommended)

---

## 📝 Step-by-Step Completion Guide

### Step 1: Gather Information
Before starting, collect:
- ✅ All team member names
- ✅ All registration numbers
- ✅ All GitHub usernames
- ✅ Programme name
- ✅ Group number
- ✅ Sprint dates (if known)

### Step 2: Update Files
1. Open `README.md`
   - Find and replace all placeholders in the Group Information section
   - Update repository structure path if needed

2. Open `scrum-overview.md`
   - Fill in the Scrum Roles table with real names and registration numbers
   - Update Daily Scrum time

3. Open `sprint-plan.md`
   - Add sprint start and end dates
   - Replace developer names in the Sprint Backlog table

### Step 3: Create GitHub Repository

1. **Create the repository:**
   - Repository name format: `is384-scrum-task-app-<programme-name>-<group-number>`
   - Example: `is384-scrum-task-app-ism-02-01`
   - Make it **private** (recommended) or public
   - Initialize with README: **NO** (we already have one)

2. **Add initial files:**
   ```bash
   git init
   git add README.md scrum-overview.md sprint-plan.md .gitignore
   git commit -m "docs: initial project setup with Scrum documentation"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/is384-scrum-task-app-<programme>-<group>.git
   git push -u origin main
   ```

### Step 4: Create Feature Branches

**Each team member must:**
1. Create their own feature branch:
   ```bash
   git checkout -b feature/<registration-number>
   ```
   Example: `git checkout -b feature/12345678`

2. Make at least one commit:
   - Each member should commit something meaningful
   - Examples:
     - Update their section in scrum-overview.md
     - Add their information to README.md
     - Update sprint-plan.md with their assigned tasks
     - Add a small feature or documentation

3. Push the branch:
   ```bash
   git push origin feature/<registration-number>
   ```

### Step 5: Create Pull Requests

**Each team member must:**
1. Go to GitHub repository
2. Click "New Pull Request"
3. Select: `feature/<registration-number>` → `main`
4. Add a descriptive title and description
5. Request review from at least one team member
6. **DO NOT merge yet** - wait for review

### Step 6: Review and Merge

1. Each PR should be reviewed by at least one other team member
2. After approval, merge the PR
3. Delete the feature branch after merging (optional but clean)

### Step 7: Invite Instructor

**IMPORTANT:** One team member (repo owner) must:
1. Go to repository Settings → Collaborators
2. Click "Add people"
3. Search for: `christiansolomon`
4. Add with "Write" or "Admin" access
5. Confirm the invitation

---

## ✅ Pre-Submission Checklist

Before the deadline, verify:

- [ ] All placeholders replaced with real information
- [ ] Repository name follows format: `is384-scrum-task-app-<programme>-<group>`
- [ ] All team members have created feature branches
- [ ] All team members have made at least 1 commit
- [ ] All team members have opened Pull Requests
- [ ] All Pull Requests show commits from the respective team member
- [ ] Instructor (`christiansolomon`) is invited as collaborator
- [ ] Repository shows multiple branches in GitHub
- [ ] All commits are visible in GitHub commit history
- [ ] README.md includes all required information
- [ ] scrum-overview.md is complete
- [ ] sprint-plan.md is complete
- [ ] No placeholder text remains in any file

---

## 🚨 Common Mistakes to Avoid

1. **❌ One person committing everything**
   - Each member MUST have their own commits
   - Solution: Each person works on their own branch

2. **❌ Forgetting to invite instructor**
   - Repository must be accessible to `christiansolomon`
   - Solution: Add as collaborator before deadline

3. **❌ Wrong repository name format**
   - Must follow: `is384-scrum-task-app-<programme>-<group>`
   - Solution: Check naming before creating

4. **❌ Leaving placeholders in files**
   - All `[PLACEHOLDER]` text must be replaced
   - Solution: Use find/replace in your editor

5. **❌ Not creating Pull Requests**
   - All branches must have PRs to main
   - Solution: Create PR for each feature branch

6. **❌ Late commits after deadline**
   - All work must be committed before deadline
   - Solution: Complete and commit early

---

## 📚 Git Commands Reference

### Initial Setup (One person - repo owner)
```bash
git init
git add .
git commit -m "docs: initial project setup"
git branch -M main
git remote add origin <repository-url>
git push -u origin main
```

### For Each Team Member
```bash
# Clone repository
git clone <repository-url>
cd <repository-name>

# Create your feature branch
git checkout -b feature/<your-registration-number>

# Make changes and commit
git add .
git commit -m "feat: add my information to README"
# or
git commit -m "docs: update scrum overview with my role"

# Push your branch
git push origin feature/<your-registration-number>
```

### After PR is Merged
```bash
# Switch back to main
git checkout main

# Pull latest changes
git pull origin main

# Delete local feature branch (optional)
git branch -d feature/<your-registration-number>
```

---

## 🆘 Need Help?

If you encounter issues:
1. Check GitHub documentation for Pull Requests
2. Verify all team members have access to the repository
3. Ensure commits are attributed to the correct GitHub account
4. Contact instructor if technical issues persist

---

## 📅 Timeline Recommendation

- **Day 1:** Gather information, update files, create repository
- **Day 2:** All members create branches and make first commits
- **Day 3:** Create Pull Requests, review, and merge
- **Day 4:** Final checks, invite instructor, verify everything
- **Before Deadline:** Double-check all requirements

---

**Good luck with your assignment! 🚀**

