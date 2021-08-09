# Git

This course will use "Github.uio.no":"https://github.uio.no" for distribution, organization and submission of the laboratory exercise.

There is no need to become and expert Git user, and the most common commands you will use are:
* git clone
* git add
* git commit
* git tag
* git pull
* git push
* git status

A list of basic Git command can be found here: "Basic Git commands from Atlassian":"https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html"
<linebreak>

Other sources of information on Git:
* "Learn Git with Github's interactive tutorial":"http://try.github.io"
* "Informasjon on Github at UiO (Norwegian only)":"http://www.uio.no/tjenester/it/maskin/filer/versjonskontroll/github.html"
* "Git tutorials from Atlassian":"https://www.atlassian.com/git/tutorials/"
* "Pro Git":"https://git-scm.com/book/en/v2"
* "Tutorials from Atlassian":"https://www.atlassian.com/git/tutorials/"
* "Git Reference":"http://git.github.io/git-reference/"
* "Become a Git pro in just one blog. A thorough guide to Git architecture and command line interface":"https://itnext.io/become-a-git-pro-in-just-one-blog-a-thorough-guide-to-git-architecture-and-command-line-interface-93fbe9bdb395"



# Using Git for FYS4220



If it is the first time you are using Git on a computer you should "Tell Git who you are":

!bc
git config --global user.name "Sam Smith"
git config --global user.email sam@example
!ec


Please use you UiO e-mail address.


_A normal command line based working flow:_
* Login to Github.uio.no
* Clone your repository *fys4220-lastname-firstname*:
!bc
git clone https://github.uio.no/fys4220-2020/fys4220-lastname-firstname.git
!ec
* Edit and save a file (e.g. README.md).
* Commit the change with a relevant/informative message:
!bc
git commit -am "Made changes to file README.md"
!ec
* Push these changes to the remote repository on Github.uio.no:
!bc
git push origin master
!ec
* The local copy of the repository can now be deleted if wanted.

_Git on windows:_
* On the windows computers in the FYS4220 lab. (V329) we have installed "git for Windows":"https://git-for-windows.github.io".
* Git for Windows provides a BASH emulation _Git BASH_ used to run Git from the command line. Behaves just like the "git" command in LINUX.
* It also provides a graphical user interface _Git GUI_. However, we recommend to use the command line interface to get familiar to the basic Git commands.
* There should be a link to _Git BASH_ on the desktop. Double click on _Git BAS_, navigate to an appropriate directory and clone your Github.uio.no repository. The default path when starting _Git BASH_ is typically your UiO home directory (often disk M).


# *Submitting the project assignments:*

#Submitting an assignment is simply done by creating a tag to mark/identify the code/project that you are submitting for evaluation, e.g:
# git tag -a lab1-part1 -m "Completed part 1 of lab 1"
# git push origin lab1-part1
# where lab1-part1 is the name of the tag id.
#
#Information on when to tag and and which tag name to be used will be given in the as part of the lab. instructions.
#


#*Submitting lab. exercises:*
#* Submitting a lab. exercise is simply done creating a tag to mark/identify the code/project that you are submitting #for evaluation, e.g:
#```
#git tag -a lab1-part1 -m "Completed part 1 of lab 1"
#git push origin lab1-part1
#```
#where *lab1-part1* is the name of the tag id.
#* Information on when to tag and and which tag name to be used will be given in the as part of the lab. instructions.


======= Working with issues =======
* An overview of how to use issues can be found here: "https://help.github.com/articles/managing-your-work-with-issues/":"https://help.github.com/articles/managing-your-work-with-issues/".
