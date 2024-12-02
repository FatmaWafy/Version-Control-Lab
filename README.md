locally and remotely?**
Locally:
git branch -d branch_name  # if the branch is already merged
git branch -D branch_name  # if the branch is not fully merged yet
Remotely:
git push origin --delete branch name

**#How to checkout another branch without committing changes?**
git stash
git checkout branch name
(git stash pop) To apply the stashed changes

**#How to list tags?**
git tag

**#How to delete a tag locally and remotely?**
Locally:
git tag -d tag name
Remotely: 
git push origin --delete tag name

![463979434_27538827442430940_5765978669939308554_n](https://github.com/user-attachments/assets/37a8648f-5cd2-4721-98ea-cfb5b769c9b2)
