# STAT 992 course notes for fall 2020

## Version control with Git

When to make commits and how to label:
- Make small commits often, so you can restore older versions of your work. 
- Make sure commit messages are succinct and informative. 

## Using Git to collaborate

Cloning repositories and pushing code:

Make sure to give collaborative shout-outs:
- Krystyn Kibler is cool.
- Thanks Vincent Denef for bringing me into the world of bioinformatics. 
- Kathryn is an awesome new member to team McMahon.

### Branching in Git
- Useful when trying out new things that aren't ready that you aren't ready to commit to master.
``` 
git pull # make sure things are up to date
git branch new-branch-name 
git branch # list existing branches
git branch -vv # see which branch you are working on
git checkout new-branch-name # switch to new branch
git branch # make sure it worked!
```

### Using 'git revert'
- If you make a mistake and accidentally commit and push do this...

'''
git revert -m 1 "7 digit commit code"
'''
