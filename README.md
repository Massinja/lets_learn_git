# Let's Learn Git

Hey, Developer!\
If you are trying to learn or revise Git, how to do PRs aka Pull Requests, or the basics of branching then you are in the right place. The information here is [Free as in Speech](https://www.howtogeek.com/31717/what-do-the-phrases-free-speech-vs.-free-beer-really-mean/#:~:text=%E2%80%9CFree%20as%20in%20beer%E2%80%9D%20is,meaning%20%22at%20no%20cost.%22)! \
Keep reading further, and remember that practice makes perfect! \
If you would like to make/suggest some changes to this project, do not hesitate to do so! Your contribution is welcomed!

## What's Git

- Git is a version control system often used in software development which helps to track source code changes.
- It was initially developed in 2005 by [Linus Torvalds](https://www.youtube.com/watch?v=o8NPllzkFhE) 🐧
- It is an Open Source project available here on Github: https://github.com/git/git

## Proposing changes

If you would like to contribute/propose/make changes to existing projects, there are several things that you will need to learn. If you haven't heard of or have forgotten about pull requests, forking, fetching, branching and merging. Do not worry. You are not the first one in this situation. There have been many before you. They all made it as it is not as difficult as you might initially think. Be patient and continue reading further.

## Forking a Repo

If you do not have access to the repository. You will need to fork it. Which means, creating a copy of the repository. \
Go to the repository and find a Fork button at the top right. Press it. It will copy this repository to your repositories.

## Clone to Local Machine

Clone the repository to your local machine to work on changes locally:

```
git clone https://github.com/your-username/repo-name.git
```

Then, go to the repository folder by using `cd` command:

```
cd repo-name
```

## Create a New Branch

What's a new branch? Imagine a tree!🌴 The repository that you just cloned is one branch of that tree. We do not want to break that branch, do we? Hence, we want to make a copy of it and create the changes in the new branch. It is recommended to make changes on the new branch rather than the main branch. The changes on one branch will not affect other branches until they have been merged.\
If you are curious, about which branch you are on and how many branches there are, check by using this command:

```
git branch
```

To create a new branch:

- switch to the branch which you want to use as a base for your changes (e.g. main):
  ```
  git checkout main
  ```
- Ensure that your local copy is up to date:
  ```
  git pull origin main
  ```
- Create and switch to a new branch:
  ```
  git checkout -b your-branch-name
  ```
- Confirm that you are on the new branch, it will have a `*` before its name:
  ```
  git branch
  ```

## Make your changes

## Commit your Changes

Commit will save your changes and it consists of 3 steps: adding, committing and pushing.

- Add a file:
  ```
  git add file-name
  ```
- Commit a file - with a message describing the change:
  ```
  git commit -m "Describe your changes in a few words"
  ```
- Push the changes:
  ```
  git push origin your-branch-name
  ```

## Create a Pull Request

To make changes to the initial project, you will need to create a pull request.

- Go back to the original repository
- Find an option to create a pull request (PR) for the branch you just pushed. Click Compare & Pull Request
- Add a title and description to your PR, explaining what you changed and why
- Submit the pull request and wait for Feedback
- If changes are requested, make updates locally. Then, commit them, and push them to the same branch. The pull request should automatically update with the new commits
- Once the reviewers have approved your changes, the pull request will be merged

## Clean Up Your Branch

to be added..
