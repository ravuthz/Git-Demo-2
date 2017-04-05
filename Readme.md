# Initial git
git init

# Add file to stage (., *, -A, filename)
git add .

# Remove file from stage
git rm --cached filename.txt

# List file in stage
git status

# List commit
git log

# Add Remote
git remote add origin https://github.com/ravuthz/Git-Demo-2.git

# List remote
git remote -v


# Git Add and Commit
git add .
git commit -m "Message"

git commit -am "Message"


# Swtich branch
git checkout branch_name

# Switch to new branch (create and switch to new branch)
git branch header
git checkout header

git checkout -b header
