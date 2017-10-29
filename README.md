CSH Constitution

The master branch's HEAD is the current legal constitution of CSH.

Compiled version of both documents can be found below:

Articles

By-Laws

Modifying the Constitution

Do not make changes to master without their passing the proper house voting procedures. (At the very least, not text changes, anyways)

First, fork the consitution repo. Before making any changes, create a new git branch.
This helps us keep the constitution repo neat and is in general a good idea.

git checkout -b "branch_name"

A good branch name will briefly give an idea of what your changes have actually done.

Once you have made your changes, commit them with a proper commit message.
It is good practice to have an imperative clause in the subject line of your commit message.
Also, if your commit fixes any issues, put the issue number (with a # sign) in the commit body. ex: fixes #102

Also, be sure to rebase multiple commits into one before making a pull request.

Document Style

One sentence, one line. In general, follow the pattern of the existing document.

Software Requirements

Must have make, and pdflatex installed.

Installing dependencies on debian

sudo apt install texlive make

Installing depencdencies on fedora

sudo yum install texlive make

Compiling the Constitution

Once required software is installed, simply run make. Running make will build and link the bylaws and articles properly.
Review the PDF output to check for any errors before making a pull request. If additional commits are made, be sure to rebase down to one commit before submitting a pull request.

Submitting a Pull Request or Issue

To make contributing easier, there are templates for both issues and pull requests. Please fill out the appropriate options in the description as you make the pull request or issue so a maintainer can more easily help get your change committed. If you are making a pull request, be sure to make a pull request against origin/master from your own branch.

Step by Step Recap

Fork this repo
Make a new branch on your fork
Modify the .tex files with your changes
Commit, Push and make a Pull Request
Announce the amendment at House Meeting.
Wait for vote to pass then merge changes
