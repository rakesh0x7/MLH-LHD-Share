# How to Create a cPanel & WHM Instance on Linode

## Log in to Linode
```To log in to Linode, perform the following steps:

Navigate to the Linode Login interface.

Enter your username and password and click Log In. The Dashboard interface will appear.
```

## Create the linode

```
To create a cPanel & WHM linode, perform the following steps:

Click Create and then click Linode. The Create New Linode interface will appear.

Click OneClick. A list of available applications will appear.

Click cPanel.

Under Select an image, select CentOS 7.

Under Region, select an appropriate region in which to create the

Enter a label for the instance in the Label text box.

If you wish, enter tags in the Tags text box to assist you in categorizing your instances.

Enter a secure password in the Root Password text box.

Click Add SSH Key.

Enter a label for the key in the Label text box (for example, id_rsa).

On your local computer, open a command line session.

Run the cat ~/.ssh/id_rsa.pub command.

If the id_rsa.pub file does not exist, perform the following steps:

Run the cd ~/.ssh/ command to navigate to your .ssh directory.
Run the ssh-keygen command.
Confirm id_rsa as the new filename.
Enter a passphrase, and then confirm it.
Run the cat ~/.ssh/id_rsa.pub command again.
Copy the results and paste them into the SSH Public key text box.
Click Create. The instance’s profile interface will appear.

Click Launch Console to watch the installation process.
```
