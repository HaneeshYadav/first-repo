# first-repo
documenting about git
git is a version control system which is used to manage and track changes of our projects
github is a platform which is used as an interface for git

1. install git $ git --version
2. clone a repository
   The git clone command is used to copy an existing Git repository from a server to the local machine.
For example, to clone a GitHub project:
cd <path where you would like the clone to create a directory>
$ git clone https://github.com/username/projectname.git
3. setting user naame and email
  $ git config --global user.name "Your Name"
 $ git config --global user.email mail@example.com
4. create a repository in github
  1. inorder to create head + icon on above of github interface and click it.
  2. next select new repository.
  3. and make required changes.
5.stage and commit:
  After making changes to your source code, you should stage those changes with Git before you can commit them.
For example, if you change README.md and program.py:
git add README.md program.py
This tells git that you want to add the files to the next commit you do.
Then, commit your changes with
 $ git commit
Note that this will open a text editor, which is often vim. If you are not familiar with vim, you might want to know
that you can press i to go into insert mode, write your commit message, then press Esc and :wq to save and quit. To
avoid opening the text editor, simply include the -m flag with your message
$ git commit -m "Commit message here"
Commit messages often follow some specific formatting rules, see Good commit messages for more information.
6. branching :
   To create a new branch, while staying on the current branch, use:
git branch <name>
7.push:
1. $  git push : is used to push our commits to repo which we run locally
2. force push:
   Sometimes, when you have local changes incompatible with remote changes (ie, when you cannot fast-forward the
remote branch, or the remote branch is not a direct ancestor of your local branch), the only way to push your
changes is a force push.
git push -f
or
git push --force
   
