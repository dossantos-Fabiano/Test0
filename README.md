# This is a sample I created for test purposes.

Hello ZAWARUDO!
Hello darkness my old friend...

# What I've learned/Terminology
* Clone ⇒ copy the content of remote repository to local repository.
* Staging ⇒ add a file to local repository pending changes.
Only staged files can be saved on commits.
* Commit ⇒ Save the changes on local repository. 
To send local commits to remote repository, use 'push'.
* Push ⇒ Send local repository commits to remote repository.
* Local ⇒ Something that is on your computer or machine.
* checkout/restore ⇒ Undo pending changes on a file.
* Log ⇒ Usually refers to a history or report of an execution.
* Fetch ⇒ Download commits from remote repository to local repository but DON'T APPLY THEM.
* Merge ⇒ Apply all local commits into the code/file (if used after 'fetch', apply all downloaded commits). 
    In case of conflict, prompt user to solve it manually.
* Pull ⇒ Basically fetch followed by merge.
* Branch ⇒ Just like the name suggest, branch is a deviation of the trunk, or a deviation of the main code.
    Branching means that from that commit on, the code was diverted, and it's being developed in parallel with main code.
    Changes made in a branch DOES NOT APPLY to the main (trunk) of a repository.
    Changes made in the main DOES NOT APPLY to a branch of a repository.
* Rebase ⇒ Basically move the 'branch' up.
For example, if you have a branch and on commit n_150 you made a new branch.
After a while, changes were made on main (n_151 ⇒ n_160), and those changes must be also on branch.
Instead of copying everything to branch, use 'rebase' for branch to move up to commit n_160.
This way, your branch includes all the changes on main until commit n_160, almost as if it was created after it.
* Reset ⇒ Delete local commit. Doesn't work with commits already sent to remote repository using push.
* Clean ⇒ Delete folders and files untracked by git on local repository.