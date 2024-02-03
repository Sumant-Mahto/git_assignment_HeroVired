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
9. collaborators added : https://github.com/prem4eru
10. Create the feature/sqrt branch and implemeneted feature/sqrt function
11. Fixed the bug Divided by zero raised by main from dev
12. Tested the feature/sqrt and created a pull request
13. Post approval of Pull requsted merged feature/sqrt to dev and dev branch to main
14. Calculator v2.0 release

Q2 : For a project that deals with large binary files, integrate Git LFS (Large File Storage) to handle these files efficiently. Demonstrate how to add, commit, and push binary files to the repository, ensuring they are tracked by Git LFS correctly. Clone the repository on another machine to verify that the binary files are downloaded correctly.

In the repository ‘git_assignment_HeroVired’, create a branch ‘lfs’. Upload any large file whose size is over ‘200mb’ and try to push this file into the repository.

Steps

1. $ git branch lfs
2. $ git checkout lfs
3. $ git lfs track Testlfs.bin
4. $ git add Testlfs.bin
5. $ git commit -m "adding large file"
6. $ git push -u origin lfs
