# How to clone a repository locally
The following instructions walk through how to go about cloning a repository locally. The environment is with Intellij hosted on a Linux operation system.

1. Generate a ssh key pair

    ![Generate ssh key pair](/images/linux_ssh_keygen.png)

1. Change directory into the .ssh directory, display, and copy to your clipboard the id_rsa.pub, this is the public ssh key needed to put into Github

    ```
    cd .ssh
    cat id_rsa.pub
    ```

    Highlight the entire output from the **cat** command which should copy it to your clipboard.

1. Login to Github and access your profile "Settings"

    ![Github profile settings](/images/profile_settings.png)

1. Select the SSH and GPG keys settings link

    ![SSH settings link](/images/ssh_gpg_keys.png)

1. Click "New SSH Key"

    ![New ssh key](/images/new_ssh_key.png)

1. Add a descriptive "Title" and paste the ssh key into the "Key" input box and click "Add SSH Key"

    ![Add a new ssh Key](/images/add_pub_ssh_key.png)

1. On the repository main page click the "Clone or download" button and be sure to change it to "Use SSH" instead of "Use HTTPS" and copy the displayed git SSH URL to your clipboar.

    ![clone or download](/images/clone_repo.png)

1. Open IntelliJ and select "Check out from Version Control" and select "Git" from the drop down menu

    ![check out from version control](/images/checkout_from_version_control.png)

1. Fill out the "Clone Repository" popup screen. The SSH URL you copied to your clipboard goes in the Git Repository URL field. Select the directory you wish to have all your repository projects under, or accept the default. Also give the cloned repository a "Directory Name" or accept the default. You can click the "Test" button to test the connection. When your ready click "Clone" and go through any other prompts.

    ![check from version control 2](/images/checkout_from_version_control_2.png)

Now you have the repository cloned to your local machine in which you can make your changes or start developing your code. When you're ready to commit your changes or newly added code see our How To on [**Committing changes**](