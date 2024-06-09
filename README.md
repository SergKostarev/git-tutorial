# This is a brief Git & GitHub tutorial
## Getting started with Git (locally) <br>
* Choose a directory to work with <br>
```bash
$ cd /some-directory/
```
* Initialize local git repository <br>
```bash
$ git init
```
* Uninitialize local git repository <br>
```bash
$ rm -rf .git
```
* Check current repository state <br>
```bash
$ git status
```
* Prepare **a file** for commit <br>
```bash
$ git add somefile.txt
```
*OR*<br>
* Prepare **all files** for commit <br>
```bash
$ git add --all
```
*OR*<br>
* Prepare **a whole repository** for commit <br>
```bash
$ git add .
```
* Commit (save) <br>
```bash
$ git commit -m 'Some message' 
```

## Git-files statuses <br>
* Untracked
Is set to files that have not been commited and added to commit. Usually this status refers to new files in project.
* Tracked
An opposite status of **untracked**. It is set to files that have already been commited or added to commit.
* Staged
Points out files that have been added to commit. Staged files are also **tracked**.
* Modified
Describes files that were modified. File modification can happen after adding to commit (stagging). Thus, modified files can be **staged**. In this case, the previous file version is to be commited. To fix this and update file version, add file to commit again. Modified files are also **tracked**.