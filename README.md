# Mount a Shared Folder using a Bash Script in Linux
# Credits to Offensive Security

1. Create a file
$ sudo nano /usr/local/sbin/mount-shared-folders

2. Change permissions
$ sudo chmod +x /usr/local/sbin/mount-shared-folders

3. Create a soft link
$ ln -s /usr/local/sbin/mount-shared-folders mount-shared-folders

4. Execute
$ sudo ./mount-shared-folders
