Change the most recent commit?

Sometimes you can catch the error quickly after making your commit. If you need to change the most recent commit message, you can use the amend flag.
In your project directory in the terminal, enter:
git commit --amend
This will bring the most recent commit message open in your default editor. Make the necessary changes to the message, mind the formatting, save the file, and exit. You should see a read out with the updated commit

How to Delete a Local Branch in Git?

Local branches are branches on your local machine and do not affect any remote branches.

The command to delete a local branch in Git is:

git branch -d  local_branch_name
