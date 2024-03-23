Some text

Step-by-step instruction.
Create new directory "new-project":
mkdir new-project
Change current directory to "new-project":
cd  new-project
Initialize a new public Git repository inside the "new-project" directory:
git init
Create new file README.md with some text
echo "Some text" > README.md
Add file to staging area an then commit it.
git add README.md
git commit -m "init"
Create a new branch called "development" and switch to it.
git checkout -b  "development"
Commit changes to the "development" branch with a commit message.
git commit -am "Adding instrictions to file README.md"
Merge changes from the "development" branch into the "main" branch. Before merging change to branch "main".
git checkout main
git marge development
Pushing changes to remote repository
git push
