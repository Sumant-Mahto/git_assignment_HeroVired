# git_assignment_HeroVired
This repo is for Herovired assignment 


Q2
: For a project that deals with large binary files, integrate Git LFS (Large File Storage) to handle these files efficiently. Demonstrate how to add, commit, and push binary files to the repository, ensuring they are tracked by Git LFS correctly. Clone the repository on another machine to verify that the binary files are downloaded correctly.

In the repository ‘git_assignment_HeroVired’, create a branch ‘lfs’. Upload any large file whose size is over ‘200mb’ and try to push this file into the repository.

Steps
1. git branch lfs
2. $ git checkout lfs
3. git lfs track Testlfs.bin
4. $ git add Testlfs.bin
5. $ git commit -m "adding large file"
6. $ git push -u origin lfs 
