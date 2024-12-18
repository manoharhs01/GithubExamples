## GIT Hidden Folder

There is a hidden folder called `.git` which tells that our project is git repo.

If we wanted to create a git repo, we create a folder and intilize that repo using `git init`

```
mkdir /workspace/tmp/new-project
cd /workspace/tmp/new-project
git init
touch Readme.md
code Readme.md
# make changes to Readme.md
git commit -a -m "add readme file"

## Cloning
We can clone in three ways : https, SSH and GitHub CLI

Since we are using GitHub codespace we'll create temp directory in our workspace

```sh
mkdir workspace/tmp
cd /workspace/tmp
```

### Https

```sh
git clone https://github.com/manoharhs01/GithubExamples.git

cd GithubExamples
```
## Commits

## Branches

## Remotes

## Stashing


## Merging

## Manohar



