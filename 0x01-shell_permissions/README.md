su betty: change user to another user
whoami: print the username of currently signed in user
groups: view all groups for user
sudo chown betty hello: change owner of the file
touch hello: add an empty file
chmod 744 hello : change the owner of file to betty
chmod 754 hello: give owner and group owner read write execute permission and read only access to the other user
chmod 751 hello: grant access to all useer on your file
chmod 007 hello: grant full access to other users only
chmod 753 hello: give access tothe user
chmod --reference=olleh hello: change mode  based on mirrorring
mkdir -m 751 cedrick: mkdir with changing permissions
