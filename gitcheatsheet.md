# Git Cheatsheet
## Staging

| Command |New Files| Modified Files| Deleted Files| Description |
|--|--|--|--|--|
|git add -A |	✔️ |	✔️ |	✔️ 	|Stage all (new, modified, deleted) files|
|git add . 	|✔️  |✔️ | 	✔️| 	Stage all (new, modified, deleted) files in current folder|
|git add --ignore-removal . |	✔️ |	✔️ |	❌ |	Stage new and modified files only|
|git add -u 	|❌ |	✔️ |	✔️ |	Stage modified and deleted files only|


git revert 3321844
