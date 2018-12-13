# cpp_sandbox

## How to start
1. Make sure you have **Visual Studio** installed!
2. Make sure you have **Git** installed on your computer
3. Decide which directory/folder you want this project to be in
(for example: **/Desktop/cpp_projects/**)
4. Go into that folder and open **Git Bash**
(Right-click in the folder and choose `Git Bash Here`)
5. When the Git Bash opens up, type in `git clone https://github.com/Junwon/cpp_sandbox.git` and press Enter
6. This should start downloading the project to your folder. Then go inside the `cpp_sandbox` folder and open the `Pracice.sln`

Note: If Visual Studio gives you a warning to *Retarget Solution*, go ahead and do that.

## Working on your own branch
Never work on the master branch. You can check this by typing `git branch` in your Git Bash and seeing which branches exist and which one you're currently using.

For example, the output for `git branch` would look like this:
* master

Make a new branch by typing: 
`git branch <type your new branch name here>` and this will create a new branch based on the branch you're currently on.

Switch to that new branch by typing:
`git checkout <that new branch name you just made>` 

Similarly, you can create and also switch branches by typing:
`git checkout -b <type your new branch name here>`

Make sure you always do work on a branch other than `master`.

You can always switch branches with `git checkout <some other branc>`.

### Workflow

Your workflow should be something like this:

1. Switch to the branch you're working on.
2. Do some work/change some files.
3. Run `git status` to see which files have been **untracked**, **modified**, or **staged**.
4. Run `git add <files you want to add separated by spaces>` to stage them. This is like adding your modified files to a commit list.
5. Once you staged or discarded your work, run `git commit -m "a description of your work in quotations"`, which will add a new commit in your current's branch repo history. You can check the history with `git log` after committing.
6. You can run this workflow many times and have many commits. It will not be pushed to the main repo which is Github.
7. When you think you are done, push your working branch with `git push`.

Note: When working with other people, be sure to run `git pull` to get the latest version of the repo.