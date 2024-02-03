# git_assignment_HeroVired
This repo is for Herovired assignment 

Q1.
1. git checkout -b dev
2. $ git add calculatorPlusApp.py
3. $ git commit -m "created the calculator app from dev"
4. $ git checkout master
5. $ git merge dev
6. $ git push -u origin master
7. $ git checkout dev
8. $ git push -u origin dev
9. Release Calculator v1.0 release
10. collaborators added : https://github.com/prem4eru
11. Create the feature/sqrt branch and implemeneted feature/sqrt function
12. Fixed the bug Divided by zero raised by main from dev
13. Tested the feature/sqrt and created a pull request
14. Post approval of Pull requsted merged feature/sqrt to dev and dev branch to main
15. Calculator v2.0 release

Q2 : For a project that deals with large binary files, integrate Git LFS (Large File Storage) to handle these files efficiently. Demonstrate how to add, commit, and push binary files to the repository, ensuring they are tracked by Git LFS correctly. Clone the repository on another machine to verify that the binary files are downloaded correctly.

In the repository ‘git_assignment_HeroVired’, create a branch ‘lfs’. Upload any large file whose size is over ‘200mb’ and try to push this file into the repository.

Steps

1. $ git branch lfs
2. $ git checkout lfs
3. $ git lfs track Testlfs.bin
4. $ git add Testlfs.bin
5. $ git commit -m "adding large file"
6. $ git push -u origin lfs


Q.3: In this same GitHub repository, create a new branch ‘geometry-calculator’, we'll work on a simple Python program that calculates the area of a circle and the area of a rectangle. We'll use Git stash to switch between working on multiple features (calculating circle area and calculating rectangle area) without committing incomplete changes.

Workflow Steps:

a. Create a New Branch:

- Create a new branch named "feature/circle-area" to work on the circle area feature

b. Stash Changes for Circle Area Feature:

- Before committing the changes, stash them using git stash to save the incomplete feature implementation.

- Verify that the working directory is clean

c. Create a New Branch for Rectangle Area Feature:

- Create a new branch named "feature/rectangle-area" to work on the rectangle area

d. Stash Changes for Rectangle Area Feature:

- Before committing the changes, stash them using git stash to save the incomplete feature implementation.

- Verify that the working directory is clean

e. Switch Back to Circle Area Branch:

- Switch back to the "feature/circle-area" branch to continue working on the circle area feature.

- Retrieve the stashed changes

- Complete the circle area feature implementation and save the changes. f. Commit and Push Circle Area Feature:

g. Switch Back to Rectangle Area Branch:

- Switch back to the "feature/rectangle-area" branch to continue working on the rectangle area feature.

- Retrieve the stashed changes

- Complete the rectangle area feature implementation and save the changes. h. Commit and Push Rectangle Area Feature

i. Create Pull Requests:

- Create a pull request to the ‘dev’ branch.

j. Review and Merge

- Have another team member or reviewer review your pull requests. - After receiving approval, merge both pull requests into the main branch.

Steps:
$ git branch
$ git branch feature/circle-area
$ git checkout feature/circle-area
$ git stash
$ git branch feature/rectangle-area
$ git checkout feature/rectangle-area
$ git stash list
$ git stash
$ git checkout feature/circle-area
$ git stash list
$ git stash pop 1
$ git add .
$ git commit -m "Stash changes retrieved and ready to push in feature/circle-area branch."
$ git push
$ git checkout feature/rectangle-area
$ git stash list
$ git stash pop 0
$ git add .
$ git commit -m "Stash changes retrieved and ready to push in feature/rectangle-area branch."
$ git checkout dev
$ git pull
$ git merge feature/circle-area
$ git push
$ git checkout feature/rectangle-area
$ git merge dev
$ git push
$ git checkout dev
$ git merge feature/rectangle-area
$ Resolved Conflict and pushed in dev branch.
$ git status
$ git checkout main
$ git pull
$ git merge dev
$ git push
