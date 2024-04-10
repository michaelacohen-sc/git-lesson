# Git Lesson

This lesson covers the basics of git for version control.

This lesson is for the MolSSI Best Practices workshop.

 To make a commit ("version" or "checkpoint") of your files, follow this procedure:

1. Make changes to your project you would like to keep.
1. When you have your changes, tell git you are ready to create a checkppoint of the files using 'git add filename'
1. Create a checkpoint using 'git commit -, "message about what you did"

## Adding Features
Features should be developed on branches. To create and switch to a branch, use the command

`git switch -c new_branch_name`

To switch to an existing branch, use

`git switch branch_name`

To submit your feature to be incorporated into the main branch, 
you should submit a `Pull Request`. 
The repository maintainers will review your pull request before accepting your changes.
