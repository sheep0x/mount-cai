mount-cai
=========

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

Tested on Debian Wheezy. If you have any trouble, feel free to contact me (linuxer.sheep.0x@gmail.com).

(For Windows/OS X users, if you have any problems, please contact the webmaster. I have NO responsibility to provide you any help.)

License
-------
This script is licensed under Apache License, Version 2.0.

Why the repo contains Mercurial files?
--------------------------------------
Sadly, the mercurial-git package (Wheezy) doesn't work so well for me, so I have to put up with different SCMs.

This repo is actually a Mercurial repo, and Git is only used as a tool to upload/download files to/from Github. That's why the Github repo also includes the .hg directory and the .hgignore file.

Since the Git repo doesn't keep track of the actual commits, it is not supposed to be used as a collaborative tool. However, this script is so simple that patches works just fine.

If you know how to fix the mercurial-git bug or have any good suggestions about a better workaround, please tell me. And sorry again for the inconvenience.
