
## Setting up a new repository locally and linking it with github git init;

git init; initializes a new repository in the current directory



## Working with changes on GIT

git restore <file>: Restores the specified file to the last committed state in the working dir.

git diff <file>: shows the differences between the working directory and the staging area for the specified file

git restore --staged <file>:

git diff --staged <file> shows the difference between the file in the staging area with previous commit.


git restore --source <hash for version> <specific files>: You can specify files or if not it will restore everything. Best practice is to specify.

main * -> something is modified
main + -> something has beeen added/staged, but not committed
main ! -> There are unmerge conflicts