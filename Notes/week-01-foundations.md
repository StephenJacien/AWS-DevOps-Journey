# Week 01 – Foundations

## Session 1

Date: 12/15/2025
Start Time: 10am
End Time: 11am

### What I did
- Created my AWS-DevOps-Journey repo locally and on GitHub.
- Set up my Git username and email.
- Connected Git with a Personal Access Token so I can push from my Mac.

### What broke or confused me
- Git authentication (username vs token vs password).
- The “fetch first” / force-push message.

### What I learned or confirmed
- GitHub requires a Personal Access Token, not my account password.
- My Git identity (Userknewww + swilli81@student.ccp.edu) is now set correctly.
- My local main branch is connected and pushing to GitHub.

### Commands I used
- git config --global user.name "Userknewww"
- git config --global user.email "swilli81@student.ccp.edu"
- git commit --amend --reset-author --no-edit
- git push -u origin main --force


## Session 2

Date: 12/15/2025
Start Time: 11am
End Time: 12pm

### What I did
- Created and updated git-practice.txt in my repo.
- Practiced checking git status, staging, committing, and pushing a change.

### What broke or confused me
- 

### What I learned or confirmed
- The normal flow is: change a file → git status → git add → git commit → git push.
- I can safely practice with a simple text file.

### Commands I used
- cd ~/AWS-DevOps-Journey
- ls
- echo "Git practice $(date)" >> git-practice.txt
- cat git-practice.txt
- git status
- git add git-practice.txt Notes/week-01-foundations.md
- git commit -m "Week 01 Day 2: git practice file"
- git push

## Session 3

Date: 12/15/2025

Start Time:12PM 

End Time:12:30PM

### What I did

- Practiced navigating between home and repo with `cd`, `pwd`, and `ls`.
- Created a practice folder and files under `practice/fs-lab`.
- Renamed and copied files, then deleted a copy.
- Committed and pushed changes to GitHub.

### What broke or confused me

- 
- 

### What I learned or confirmed

- The difference between `mv` (rename or move) and `cp` (copy).
- `rm` permanently removes files. Doing `ls` before and after helps verify changes.
- Comfort moving between `\~` and repo paths using absolute paths.

### Commands I used

- cd ~
- pwd
- ls
- cd ~/AWS-DevOps-Journey
- pwd
- ls
- mkdir -p practice/fs-lab
- cd practice/fs-lab
- touch file1.txt file2.txt
- ls
- mv file1.txt moved-file1.txt
- cp file2.txt copy-of-file2.txt
- ls
- rm copy-of-file2.txt
- ls
- cd ~/AWS-DevOps-Journey
- git add practice
- git commit -m "Week 01 Day 3: basic filesystem commands practice"
- git push

---

## Session 4

Date: 12/16/2025

Start Time:1PM 

End Time:1:30PM

### What I did

- Opened `README.md` in my repo to describe the purpose of this project.
- Documented the basic folder structure (Notes, Summaries, Projects, Screenshots).
- Added a short “Week 01 – Foundations” section summarizing what I accomplished this week.
- Saved the changes, then committed and pushed the updated README to GitHub.

### What broke or confused me

- 
- 

### What I learned or confirmed

- The README is the landing page for my repo and should explain what this journey is about.
- Using Markdown headings and bullet points makes the README easier to scan on GitHub.
- Documentation changes follow the exact same workflow as code: edit → `git status` → `git add` → `git commit` → `git push`.

### Commands I used

- cd ~/AWS-DevOps-Journey
- ls
- git status
- (Opened README.md in my editor)
- git status
- git add README.md Notes/week-01-foundations.md
- git commit -m "Week 01 Day 4: improve README documentation"
- git push

---

## Session 5

Date: 12/16/2025
Start Time: 12:18 PM
End Time: 

### What I did

- Updated README.md with a clear repo overview and structure sections (Notes, Summaries, Projects, Screenshots).
- Completed Week 1 weekly summary at Summaries/week-01-summary.md.
- Finalized the Week 1 note content for Sessions 1–5 and ensured formatting is consistent.
- Prepared for close‑out (commit, push, and Notion updates).

### What broke or confused me

- None major today; focus was documentation and close‑out.
- Minor: verifying that the README structure accurately reflects current folders.

### What I learned or confirmed

- Keeping README and weekly notes in sync creates a clear public proof of work.
- The end‑of‑week flow: update notes/summary → commit/push → mark Notion row as Done.

### Commands I used

- git add README.md Summaries/week-01-summary.md Notes/week-01-foundations.md
- git commit -m "Week 01: finalize notes and summary"
- git push
