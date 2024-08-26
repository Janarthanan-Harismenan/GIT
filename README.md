# 🚀 Learn Git by Terminal Commands

## 📚 Things I Learned

```bash
# 👤 Set user information
git config --global user.name "Janarthanan-Harismenan"
git config --global user.email ""

# 📁 Clone repository and navigate to directory
git clone https://github.com/ms-anomaly/rs-anomic.git
cd React_To_Do_List

# ✅ Check status, add file, commit, and push
git status
git add text2.txt
git commit -m "text2.txt file added"
git push origin main
git pull
git pull origin main

# 🛠️ Initialize new repository, add files, set remote, and rename branch
cd ..
cd "LearGit Part 02"
git init
git add .
git remote add origin https://github.com/Janarthanan-Harismenan/LearGit-Part-02.git
git branch
git branch -M main

# 🌿 Work with branches
git branch
git branch -a
git checkout -b branch-01
git push origin branch-01
git merge branch-01
git push origin main

# 🌱 Create new branch
git branch branch-02
