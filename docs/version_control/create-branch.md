# How to create branches within a repository

Creating branches within a repository has many uses from allowing multiple developers to work on different parts of the code at the same time to being a part of a deployment strategy. For more information about the usefulness of branches please see the [Workflow Strategy]() page. This page shows the different ways you can create a branch in a repository.

## Via GitHub
1. On the **Code** tab of the repository click the **Branch: master** drop down. Here you can see what branches already exist and create new ones. Just simply type the name of the new branch and click **Create branch: *branch name* from 'master'**. To update git locally to know about any newly created remote branches an explicity [**Fetch**](fetch_branches.md) needs to be performed.

    ![create branch in github](/images/create_branch_github.png)

## Via IntelliJ IDE

1. Go to **VCS** -> **Git** -> **Branches..**
    
    [![navigate to branches menu](/images/branch_menu.png)](/images/branch_menu.png)

1. The **Git Branches** pop-up menu will be displayed and click the <span style="color:green">**+**</span>**New Branch** option.

    ![git branches popup](/images/git_branches.png)
    
1. In the **Create New Branch** dialog name your branch and optionally check the box next to **Checkout branch**. (see our How to on **Checkout Branch** to learn more about checking out branches)

    ![create new branch dialog](/images/create_new_branch_dialog.png) 