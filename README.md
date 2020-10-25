Your first Git repository (command line):
1. Create a new repository on your GitHub.
2. Create a new folder on your PC. (copy_git_project)
3. Clone the repository to this folder on your computer (git clone “url / to / repository”).
4. Create a text file (.txt) in this folder.
5. Commit and push to upload changes to the remote GitHub repository.

Working with branches:
1. Create a branch called “branch1”.
2. Modify the text of the file from this branch.
3. Commit and Push the changes. (If you look at GitHub, you should see that you have two branches)
4. Return to the “master” branch.
5. Make another change to the document and commit and push.
6. From this merge the changes from "branch1" to your "master" branch.

Conflicts!
As expected, Git alerts you to changes in both branches. In this case we have 3 options:
 a. Mine: Selecting changes to the current "master" branch is the right version.
 b. Their: Select that the changes in the other branch "branch1" are the right ones.
 c. Resolve the conflict: If you access the file you will see that git has added 3 lines of code, delete them and leave the two lines (one for each branch).
You must use option c for the exercise.
Once the conflict is resolved, the master branch must be committed and pushed.
