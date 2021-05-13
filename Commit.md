# git commit 

the command `git commit` will take all tracked changes (items added with [git add](./Add.md)) and package them up in what is called a commit. 

Commits come with commit messages that are required for each commit. You add a message to commit command by using the `-m` flag by a message in quotes. 

A commit message_can_be anything, but best practice dictates that you should use that messafe to indicate the cahnges included in the commit. 

For example, if we have an applicaiton we're working on where we just build out the ability to register new accounts, then you might have some variation of the following: 

```
git add .
git commit -m "Added register funcitonality"
```

Then when viewing the history of a git repository, you can pinpoint where the registration funcitonality was added. 

## Resources 

-[Git Commit Documentaiton](https://git-scm.com/docs/git-commit)

---

[back to home](../README.md)