# BAM 3.2
## Creating a New Branch and Merging Changes via `Git Merge`



### 1. Create a New Branch
- Run `git switch -c <branch-name>` to create a new branch.
<br><br>
<img src="./images/01_create_new_branch.png" alt="Create New Branch" style="width: 90%">
---

### 2. Modify the Branch
- Edit, delete, or create new files, then run `git add` and/or `git rm`.
<br><br>
<img src="./images/02_add_files.png" alt="Create New Branch" style="width: 90%">
---

### 3. Stage and Commit Changes
- Stage changes by running `git commmit -m "<message information>"`.
<br><br>
<img src="./images/03_commit.png" alt="Create New Branch" style="width: 90%">

---

### 4. Push Branch to GitHub
- Run `git push -u origin <branch-name>` to push the branch to GitHub.
<br><br>
<img src="./images/04_push_to_branch.png" alt="Create New Branch" style="width: 90%">

---

### 5. Verify Branch on GitHub
- Go to your GitHub repo and check the branch activity.
<br><br>
<img src="./images/05_verify_branch_activity.png" alt="Create New Branch" style="width: 90%">

---

### 6. Switch Back to Main
- Run `git switch main` to switch back to the main branch.
<br><br>
<img src="./images/06_switch_to_main.png" alt="Create New Branch" style="width: 90%">

---

### 7. Merge the Branch to the Main Branch
- Run `git merge <branch-name>` to merge the branch into the main branch.
<br><br>
<img src="./images/07_merge_main.png" alt="Create New Branch" style="width: 90%">

---

### 8. Push Merged Main Branch to GitHub
- Run `git push origin main` to push the merged main branch to GitHub.
<br><br>
<img src="./images/08_push_to_main.png" alt="Create New Branch" style="width: 90%">

---

### 9. Verify Main Has the Updates

- Check the main branch on GitHub to view changes from the merge.
<br><br>
<img src="./images/09_verify_main_update.png" alt="Create New Branch" style="width: 90%">

---

### 10. Delete the Local Branch
- Run `git branch -d <branch-name>` to delete the local branch.
<br><br>
<img src="./images/10_delete_local_branch.png" alt="Create New Branch" style="width: 90%">

---

### 11. Delete the Remote Branch on GitHub
Run `git push origin --delete <branch-name>` to delete the remote branch on GitHub.
<br><br>
<img src="./images/11_push_delete_to_github.png" alt="Create New Branch" style="width: 90%">

---

### 12. Verify the Branch is Deleted
- Check the main repo on GitHub to confirm the branch has been deleted.
<br><br>
<img src="./images/12_verify_branch_deleted.png" alt="Create New Branch" style="width: 90%">

---
### <ins>References</ins>
References
Git Cheat Sheet: https://git-scm.com/cheat-sheet

Delete Remote Branch: https://stackoverflow.com/questions/2003505/how-do-i-delete-a-git-branch-locally-and-remotely