# Git lesson (is markdown file--know with .md at end of name)

This will cover the basics of using git version control

This lesson is for the MolSSI Best Practices Workshop

To make a commit ("version" or "checkpoint") of your files, follow this procedure:

1. Make changes to your project you would like to keep.
2. When you have your changes, tell git you are ready to create a checkpoint of the files using `git add filename`
3. Create a checkpoint using `git commit -m "message about what you did"

## Adding Features
Features should be developed on branches. To create and switch to a branch, use the command

`git switch -c new_branch_name`

To switch to an existing branch, use

`git switch branch_name`