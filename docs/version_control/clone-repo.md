# How to clone a repository locally via IntelliJ

1. Our GitHub Enterprise account only allows cloning using the SSH url. So inorder to clone any repository you will need to setup an SSH key pair trust between GitHub and your local machine. You can follow the instructions here to [generate an ssh key pair](../generate-ssh-key.md)

1. On the repository main page click the "Clone or download" button and be sure to change it to "Use SSH" instead of "Use HTTPS" and copy the displayed git SSH URL to your clipboar.

    [![clone or download](/images/clone_repo.png)](/images/clone_repo.png)

1. Open IntelliJ and select "Check out from Version Control" and select "Git" from the drop down menu

    [![check out from version control](/images/checkout_from_version_control.png)](/images/checkout_from_version_control.png)

1. Fill out the "Clone Repository" popup screen. The SSH URL you copied to your clipboard goes in the Git Repository URL field. Select the directory you wish to have all your repository projects under, or accept the default. Also give the cloned repository a "Directory Name" or accept the default. You can click the "Test" button to test the connection. When your ready click "Clone" and go through any other prompts.

    [![check from version control 2](/images/checkout_from_version_control_2.png)](/images/checkout_from_version_control_2.png)

Now you have the repository cloned to your local machine in which you can make your changes or start developing your code. When you're ready to commit your changes or newly added code see our How To on [**Committing changes**](commit.md)