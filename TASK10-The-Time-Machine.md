Created a commit and intentionally removed it using:

git reset --hard HEAD~1

Used git reflog to find the lost commit hash and recovered it with:

git reset --hard <commit-hash>
Result

The deleted commit and its work were successfully recovered using Git Reflog.














