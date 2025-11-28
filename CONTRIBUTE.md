# Before You Contribute

[TOC]

## Clone the repository

```shell
git clone https://github.com/hey-malte/visual-function-editor
```

## Working on a task
Before starting to work on a new task pull the current version of the main branch.
```shell
git checkout main
git pull origin main
```
Then create a new branch for your task. Use the Jira tracking id.
```shell
git checkout -b <task-type>/<task-tracking-id>
```
Alter the project contents according to sub-tasks. Then commit the changes you made to your branch.
```shell
git add .

# If you did not work on a subtask, just use the parent task's tracking-id.
git commit -m "<subtask-tracking-id>: <Short description>"
```
Push to your branch.
```shell
git push -u origin <task-type>/<task-tracking-id>
```
Finally create a pull request to merge your task's branch with the main branch.