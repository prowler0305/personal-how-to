# Generate an SSH key pair
The following instructions walk through how to generate an ssh key pair on a Linux operation system.

1. Generate a ssh key pair

    [![Generate ssh key pair](/images/linux_ssh_keygen.png)](/images/linux_ssh_keygen.png)

1. Change directory into the .ssh directory, display, and copy to your clipboard the id_rsa.pub, this is the public ssh key needed to put into Github

    ```
    cd .ssh
    cat id_rsa.pub
    ```

    Highlight the entire output from the **cat** command which should copy it to your clipboard.

1. Login to Github and access your profile "Settings"

    [![Github profile settings](/images/profile_settings.png)](/images/profile_settings.png)

1. Select the SSH and GPG keys settings link

    [![SSH settings link](/images/ssh_gpg_keys.png)](/images/ssh_gpg_keys.png)

1. Click "New SSH Key"

    [![New ssh key](/images/new_ssh_key.png)](/images/new_ssh_key.png)

1. Add a descriptive "Title" and paste the ssh key into the "Key" input box and click "Add SSH Key"

    [![Add a new ssh Key](/images/add_pub_ssh_key.png)](/images/add_pub_ssh_key.png)
