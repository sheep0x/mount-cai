mount-cai
=========

The repo has moved
------------------
This repo has been moved to [Bitbucket](https://bitbucket.org/sheep0x/mount-cai). The Github repo will no longer be updated. Please check the Bitbucket repo for latest updates.

Usage
-----
        mount-cai [-h|--help]
        mount-cai [-u UID|USERNAME] [-i] [--interactive|--script|--non-interactive|--symlink] [--user=UID|USERNAME] [DIRECTORY]
        mount-cai --unmount [-u UID|USERNAME] [-i] [--interactive|--script|--non-interactive] [--user=UID|USERNAME] [DIRECTORY]
mount (or unmount) Cai on DIRECTORY via WebDAV (with no SSL support)

by default, DIRECTORY is ./

You may want to read the help first; type ./mount-cai -h to see it.

About
-----
I'm on the OI team in Xiamen No.1 Middle School. We set up a WebDAV service, so that students can view and modify files on our Samba server, even when they are at home. However, some seemed to have trouble connecting to the WebDAV server, so I wrote this simple script to mount it automatically.

Tested on Debian Wheezy and Ubuntu Raring. If you have any trouble, feel free to contact me (linuxer.sheep.0x@gmail.com).

(For Windows/OS X users, if you have any problems, please contact the webmaster. I have NO responsibility to provide you any help.)

License
-------
This script is licensed under Apache License, Version 2.0.
