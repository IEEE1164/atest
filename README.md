# Heading

```bash
# 1.
git --version
# 2. 
git status
# 3.
git init
# 4. 
git status
# 5. Add files to staging status
git add .
# 55. Unstage particular file.
git rm --cached <file>
# 555. Commit to local repository
git commit -m "message"
# 6. User wide configuration (--global)
git config --global user.name "Lars Altmann"
git config --global user.email "lars.altmann@gmail.com"
git config --global user.email
# 7. Repository wide configuration (--local)
git config user.name "Lars Altmann"
git config user.email "lars.altmann@gmail.com"
git config user.email
#. 8 Show the commit history of current branch
git log
#. 88 Show compressed log history
git log --oneline
#. 9 Show type of a hash
git cat-file -t fa0fd813...
#. 10 Show contents of a hash
git cat-file -p fa0fd813...
#. 11 show tree contents (tree hash)
git cat-file -p 79f41ede...
#. 12 Link to remte repo.
git remote add origin https://github.com/IEEE1164/atest.git
#. 122 Show remote repo
git remote -v
```