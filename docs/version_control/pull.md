# Pull changes to update local repository
To update your local repository with changes that are in the remote repository you need to perform a **fetch** of the changes followed by a **merge** to combine the remote changes with any changes that exist in your working directory. Or you can easily perform a **pull** which is the combination of the two commands.

## How to do a PULL via IntelliJ
 
 1. Go to **VCS** -> **Git** -> **Pull**.
 
    ![git pull](/images/git_pull.png)
 
 
 1. This brings up the "Pull Changes" dialog panel. Verify that the **Git Root** directory path is correct and the **Current Branch** indicates the local branch you want to merge any changes in the remote repository with. Select the **Remote** you want to pull from. Check the **Branches to merge** and click **Pull**
 
    ![pull changes dialog](/images/pull_changes_dialog.png)