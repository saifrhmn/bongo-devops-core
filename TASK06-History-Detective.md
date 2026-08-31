I used `git log -p` and `git blame` to investigate the Change code.
Example : 
* **Commit Hash:** `abc123456789...`
* **Author:** Mentor Name
* **Date:** August 29, 2026, 6:45 PM (+0600)
* **Change:** Port changed from `3000` to `8080`.

Cmd Used :

git fetch origin
git log -p --all
git blame <filename>
git show <commit-hash>
