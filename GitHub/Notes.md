#How to Use Git and GitHub

##Lesson 1 
### Find differences between two large files
__Commands__:
- Windows: FC
- Mac/Linux: Diff

###Versions
- Saving manual copies
- Dropbox
- Google Docs
- Wikipedia

###Mannual Commits 
- fix off-by-one bug
- add cool new feature
- improve user docs

###Git Commands
- Clone a repo `git clone _repo_url_`
- git log
- git diff

###Check commit
- git checkout `_commit ID`

##Lesson 2
### Initialize 
- `git init`
- check git status: `git status`

### Commit changes
- working directory -> staging area -> repository
- `git add _file_to_update_`
- remove from staging area by using `git reset`

### Write a commit message
- `git commit`
- `git commit -m "Commit message"`
- commit message [style guide](http://udacity.github.io/git-styleguide/)

### Git diff revisited
- `git diff --staged`
- Leave 'detached HEAD' state: `git checkout master`