seRemove Local Branches: "git branch -d <name>"
Remove Remote Branches: "git push origin --delete <name>"
----------------------------------------------------------------------------

Annotated Tags:
Store metadata such as the tagger’s name, email, date, and a message.
Created with "git tag -a <tagname> -m <message>".

Lightweight Tags:
A simple pointer to a specific commit.
Created with "git tag <tagname>".
----------------------------------------------------------------------------

When to Use Rebase?
Apply changes from one branch onto another.
Keep a clean project history by incorporating changes without extra merge commits.
----------------------------------------------------------------------------

How to list tags?
To list tags in the repositor: "git tag"
----------------------------------------------------------------------------

Delete tag locally: "git tag -d v1.0"
Delete tag remotely: "git push origin --delete v1.0"
----------------------------------------------------------------------------

![my image](hello.png)