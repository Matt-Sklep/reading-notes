# Module 3

## Learning Git to Update Projects

Git is a Distributed Version Control System (DVCS), which allows multiple users to work within the same repository. A DVCS will keep track of every change that an individual has made anywhere in the project, and lets anyone working on that project to see what changes have been made and when.

Every time a something in a project is changed and saved, it is called a `commit`. Git will log the new entries into to server-stored project. Commits are primarly uploaded from local hardware, which allows users to work offline and may then upload their changes once back online. The files in Git exist in one of three states:

1. Committed: A file that has been stored in a database.
2. Modified: A file that has been changed but has not been committed.
3. Staged: A file that has been changed will be committed in the next Git snapshot.

When setting up Git via the *Terminal*, it is important to set their username and email that will be used for each Git commit. To set these, one uses the commands:

```git config --global user.name "Name Here"
git config --global user.email "Email Address Here"
```

To check your Git's local settings, use the `git config --list` command.

## Important Git Commands

To create a repository via the terimal, the following commands are necessary:

1. `$ git init`
2. `$ git add *.c`
3. `$git add LICENSE`
4. `$git commit -m "Message Related to the Commit"`

To create a clone of an existing Git Repository, use the command `$ git clone [Link to Repository]` and the associated link found within the respository's *Code* section. Be sure to use enter this command when you are in the desired directory in your terminal.

To check the status of your Git and its files, use `$ git status`.

To add a file that is ready to be committed, use `$ git add [File Name]` or to add all files use `$ git add *`.

To commit the files desired, use `$ git commit -m "Message Related to the Commit"` or `$ git commit -a`.

Finally, to push the changed files to the repository, use `$ git push origin main`. This will move all files in the local *main* branch to the remote *origin* branch.

If one does not want to commit their changes just yet, using `$ git stash` will hide the changes made from the directory. To get the changes to show again, use `$ git stash apply`.
