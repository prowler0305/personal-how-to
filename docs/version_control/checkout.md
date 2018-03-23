# How to checkout branches

When multiple branches exist in a repository in order to work within a certain branch your local working trees files and index needs to be switched to that branch. This is accomplished by doing a **checkout**.

Most of the time before you do a checkout you will want to makes sure you have a clean working directory. You can do this by either committing changes to the current branch before doing the checkout or [stash/shelve the changes](stashing.md).

There are two kinds of checkouts:

* [Checkout a remote branch as a new local branch](#checkout-a-remote-branch-as-a-new-local-branch)
* [Switching between local branches via a checkout](#switch-between-local-branches)

## Checkout a remote branch as a new local branch

When you [create a remote branch via Github](create-branch.md#via-github) and [fetch](fetch_branches.md) it down to your local repository you need you now need to check it out as a local branch in order to work within that branch.

1. In IntelliJ go to **VCS** -> **Git** -> **Branches...**

    [![branches menu](/images/branch_menu.png)](/images/branch_menu.png)
    
1. In the Git Branches submenu under **Remote Branches** click on the branch you want which will show a submenu for the branch and click on **Checkout as new local branch**

    [![git branches submenu](/images/checkout_remote_branch.png)](/images/checkout_remote_branch.png)
    
1. Give a name to the checkout of the remote branch or leave the already populated name.

    [![name checkout of remote branch](/images/name_checkout_remote_branch.png)](/images/name_checkout_remote_branch.png)

1. Git will take the remote branch and create a local branch and checkout your working tree to point to this new branch you can verify this in the bottom right hand corner.

    [![verify branch checkout](/images/verify_branch_checkout.png)](/images/verify_branch_checkout.png)
    
## Switch between local branches
When you have more than one local branch in order to work on changes contained within that branch you need to switch you working tree to that branch by performing a **git checkout *branch_name* ** command. In IntelliJ its as simple as the following:

1. Go to **VCS** -> **Git** -> **Branches...**

    [![branches menu](/images/branch_menu.png)](/images/branch_menu.png)
    
1. In the Git Branches submenu under **Local Branches** click on the branch you want to switch to and in the context menu click on **Checkout**

    [![checkout local branch](/images/checkout_branch.png)](/images/checkout_branch.png)



