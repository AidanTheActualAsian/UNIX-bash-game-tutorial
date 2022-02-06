# UNIX-bash-game-tutorial
A project I worked on in Fall 2020 that was designed to teach people how to operate the Unix command line. Our Linux Activity to Reinforce Knowledge (LARK) project.

This project was pretty basic--we made it entirely in the Bash shell. At the time we didn't really know how to make large-scale games with things like Unity, so we simply opted for a silly text adventure (about trying to find toilet paper in the midst of an toilet paper outage; this may or may not have had something to do with current events).

Our goal was not to make something large-scale, but rather to teach other people how to operate the Bash command line in the context of a short and sweet game. I've put the document explaining the rationale for our game in the repository, but I'll list out a couple of the important details here:

## Skills and Concepts Taught
1. Listing files using ls and its options.
2. Viewing file contents with cat.
3. Navigating directories using pwd and cd.
4. Creating folders and files with mkdir and touch.
5. Copying and moving files with cp and mv.
6. Using tools like grep, du, head, and tail to find patterns in text, determine disk space usage, and returning only parts of text.
7. Using special characters in commands and performing basic input redirection.

## Running the Game
This game needs to be run in a Linux environment. This can be done by doing any of the following (links provided if you aren't familiar with how to get Linux up and running):
* Downloading a Linux distro and setting up a virtual machine, then downloading the file to the VM: https://www.makeuseof.com/tag/install-linux-windows-vmware-virtual-machine/
* Setting up the Windows Subsystem for Linux (WSL). If you download the game, you'll have to make note of where you downloaded it to on your computer, and then run **cd /mnt/[path-to-the-file]**. Linux uses "/" instead of "\\".: https://www.windowscentral.com/install-windows-subsystem-linux-windows-10

![Path](https://user-images.githubusercontent.com/56741029/152696866-fead7b04-b656-4792-adce-1daa9537e1ca.png)


Once you have the file in the Linux environment, simply run **tar -xvf finishedLark.tgz** and then run **cd larkGame**. You can then run **cat readme.txt** to get a brief introduction and tutorial on some commands. You'll navigate through different folders, with most folders having at least one .txt file explaining what you need to do. Have fun!

![Game Screen](https://user-images.githubusercontent.com/56741029/152696426-fb9ca423-24da-4fbe-9010-1cee157c1db2.png)
