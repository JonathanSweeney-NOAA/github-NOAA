# Procedures for setting up and using Github at NOAA

Git (the software) and Github (the remote server) have become the preferred version control and collaboration tool for maintaining code
and developing software.  The time you spend setting up your repo at the start pays with interest as you maintain an organized, collaborative project, with a functional master version throughout project development. You will also no longer ever be faced with a sprawling project directory with files labeled V1... Vinfiniti!

## Setting up an account
The account you use for NOAA work will have to be different from your personal account.  To set up a NOAA account follow these steps:
* Navigate to [github.com](https://github.com/)
* Create a new account using your NOAA email address
* Your user name should follow the template "FirstnameLastname-NOAA"
* Once your account is created, upload a photo of you as your profile photo
* Set up 2-factor authentication under your user settings

## Installing Git on Windows
Windows does not come with git pre-installed.  You will have to put in a JIRA ticket to have Git installed on your work machine, if it you haven't installed it previously.  ITS is familiar with this request, but installation instructions can be found [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) if needed.

## Using Git Bash
The command line interface is the preferred method to use Git.  Unfortunately Windows doens't have a Bash terminal, 
so Git has included one in your Windows install.

To open Git Bash, type "git" in the Windows search bar and click on Git Bash.  It's a good idea to pin this to your task bar for easy access in the future.

There are only really two Bash commands you need to know: `ls` and `cd`. `ls` lists the files in your current directory, and `cd` allows you to navigate up or down the directory system.  To move down a directory type `cd directoryname`. Type `ls` to see what files/folders are in this current directory. To move back one directory type `cd ..`.  With this simple set of commands you can easily navigate between your project folders and use Git.

## Rules for NOAA users
As NOAA users we are bound by a few rules:
* Your account must have a photo of you as your profile photo
* You must use 2-factor authentication
* You can only have NOAA related work under your account
* You can only contribute to NOAA affiliated repositories
* Collaborators outside of NOAA can not directly commit changes to NOAA repositories.  Instead they will have to go through pull requests
* Project repositories should be backed up on a system inside the NOAA firewall (for example zip download the master to your local work computer)
* README.md must have a disclaimer mentioned in NOAA Github Checklist (see below)
* License must have specific wording mentioned in NOAA Github Checklist (see LICENSE.md in this repo)


### Disclaimer
This repository is a scientific product and is not official communication of the National Oceanic and
Atmospheric Administration, or the United States Department of Commerce. All NOAA GitHub project code is
provided on an ‘as is’ basis and the user assumes responsibility for its use. Any claims against the Department of
Commerce or Department of Commerce bureaus stemming from the use of this GitHub project will be governed
by all applicable Federal law. Any reference to specific commercial products, processes, or services by service
mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recommendation or
favoring by the Department of Commerce. The Department of Commerce seal and logo, or the seal and logo of a
DOC bureau, shall not be used in any manner to imply endorsement of any commercial product or activity by
DOC or the United States Government.
