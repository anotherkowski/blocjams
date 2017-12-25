# Checkpoint Instructions

## Before (Checkpoint)

git checkout -b checkpoint-23-fe
// FE = Front End (because some checkpoints are backend)

## After (Assignment)
// Do NOT merge assignments until AFTER  they are approved!

git add .
git commit -m "Assignment 23 completed"
git push origin assignment-23-fe
git checkout master

## After (Checkpoint)

git add .
git commit -m "Checkpoint 23 completed"
git push origin checkpoint-23-fe
git checkout master
git merge checkpoint-23-fe
git push
