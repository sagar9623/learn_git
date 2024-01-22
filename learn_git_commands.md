git config
git is a tool

GitHub is a platform that uses git to implement cloud-based remote state/version management.

What was the need to do this? give 4 examples.

What is the history of this? Understand with examples? give 4 examples.

If we do NOT use it, what will happen? give 4 examples.

What are the other options for doing this? give 4 examples.

Why to use it? give 4 examples.

When to use it? give 4 examples.

When to NOT use it? give 4 examples.

How to use it? give 4 examples.

How to understand the principle of a tech working in a real-world non-tech scenario? Give 4 examples.

How to understand the principle of a tech working in a real-world tech scenario? Give 4 examples.

What does each word in the line mean? give 4 examples.

What are other available ways to do the same thing? give 4 examples.

Step 1: Config GIT.

**command**: git config --global user. name " sagar katekhaye"

**command to email:** git config --global.email katekhayesgar7@gmail.com

Step 2: Default branch name.

**command:** git config --global init.default branch main

Step 3: to change directory.

**command:** cd

Step 4: to turn into git repository.

**command:** git init

Step 5: to know git status/ to track status.

**command:** git status

Step 6: to track a file.

**command:** git add index.htm

Step 7: to un-track a file/ to track all files.

**command:** git rm --cached index.htm

**command:** git add --all/-A/.

Step 8: On Windows, you can use the following command to create an empty .gitignore file:

**command:** type nul > .gitignore

Step 9: to see what's modified.

**command:** git diff

Step 10: To remove files from staging.

**command:** git restore --staged index.htm

Step 11: to directly commit the file.

**command:** git commit -a -m "update text to free range"

Step 12: To remove/delete the file.

**command:** git rm "secret recipe.htm"

Step 13: restore the deleted file.

**command:** git restore "secret recipe.htm"

Step 14: to rename the file.

**command:** git mv "KCC Logo.png" "primary Logo.png"

Step 15: To add the change to the history book.

**command:** git commit -m "changed the file name of an image"

Step 16: Check all the logs that are committed to committing history/ to get a more abbreviated version.

**command:** git log

**command:** git log --oneline

Step 17: if you type any text incorrectly then change the text.

**command:** git commit -m "changed the file name to primary Logo.png" --amend

Step 18: if you want specifics.

**command:** git log -p

Step 19: if you want to jump back to previous commits.

**command:** git reset write the position you wanna jump back to

Step 20: To modify what appears in the history book and also the order in which all the commits appear.

**command:** git rebase -i --root

Step 21: to quit/exit rebase.

**command:** git rebase --quit/abort

Step 22: to set up an additional branch.

**command:** git branch name you want to create branch as

Step 23: To switch to other branches.

**command:** git switch FixTemp

Step 24: to merge the branches.

**command:** git merge -m "Merge FixTemp back to master" FixTemp

Step 25: to delete the branch.

**command:** git branch -d FixTemp

Step 26: To switch and create a branch at the same time.

**command :** git switch -c UpdateText

Step 27: Commit the changes to master.

**command:** git commit -a -m "update index text"

**Collaboration of Git and GitHub.**

Create a GitHub account if you don't have it // if you already have a GitHub account then follow the steps.

after creating a GitHub account create a new Repository, and name the repository // If you already have an account then just create a new repository

after creating a new repository you will see (...or push an existing repository from the command line)

Step 28: Your URL will be specific to your GitHub account. ( This establishes a remote connection with GitHub and we call this remote connection origin) this is the address that you're going to connect to.

**Command:** git remote add origin https://github.com/sagar9623/learn_git.git

Step 39: This command will set the target branch to master (main (whatever you have named your branch)).

**Command:** git branch -M master

Step 30: This command helps you to push all the content from your local repository to the cloud(GitHub).

**Command:** git push -u origin master

Then you can see that your entire local repository has now been pushed to GitHub into the cloud repository.

Step 31: To push everything to the GitHub.

**Command:** git push --all
