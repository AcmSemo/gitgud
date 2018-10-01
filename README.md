# GitGud
List of languages we know. Open for any ACM members to give their list of proficiency in programming languages.

This is just a fun repo for people wanting to get used to the flow of contributing to other projects. Keep reading to learn how to start contributing and become a social coder!

## Getting Started

1) Click the Fork button near the top right corner to create your own copy of this repo onto your Github

2) Go to your forked repo and copy the url. Open up your Git terminal on your computer and create a clone like so 
`git clone <url of your forked repo>`

3) Now cd into your repo and create a new branch to work on.
`cd <repo name>`
`git checkout -b <branch name>`

This will automatically switch you onto your newly created branch, instead of the master branch.

4) Now we get to write some code! Just create an html table in index.html with your name, programming languages you know, how comfortable you are with them (on a scale of 1.0 - 10.0), and your total number of languages known.
Example:
```
<table class="red">
  <th colspan="2">That Guy</th>
  <tr>
    <td>HTML</td>
    <td>7</td>
  </tr>
  <tr>
    <td>CSS</td>
    <td>5.5</td>
  </tr>
  <tr>
    <td>JavaScript</td>
    <td>8</td>
  </tr>
  <tr>
    <td>C++</td>
    <td>6</td>
  </tr>
  <tr>
    <td>Total Languages</td>
    <td>4</td>
  </tr>
</table>
```

There are 6 color classes to choose from: red, yellow, blue, purple, orange, and green. But feel free to add your own custom css style if you want!

5) Time to commit our changes. First we want to add the changes to the staging area like so 
`git add index.html`

6) Next, we'll make our commit. Be sure to follow best practices when writing a commit message! Here's a link to a guide on making good commits: [Git Commits](https://chris.beams.io/posts/git-commit/)

Once you feel ready, let's make our commit!
`git commit -m "subject line" -m "description"`

7) Now that our changes are made, we can push them to our repo.
`git push origin <branch you made>`

8) Now go to your repo on Github. On the right, you should see a button for "Compare & pull request". Click on the button to submit a pull request!

Once your request has been accepted and merged, remember to delete the branch you made!

## tl;dr

Quick list of steps:
1) Fork it
2) Clone it `git clone <url of your forked repo>`
3) Make branch `git checkout -b <branch name>`
4) Make html table
5) Add changes `git add index.html`
6) Commit changes `git commit -m "subject line" -m "description"`
7) Push changes to repo `git push origin <branch you made>`
8) Click Compare & pull request

## Updating Forked Repo
Sometimes a project might change quite a bit from the time you made your fork and you will need to update your forked repo to avoid merge conflicts! This article provides a quick walkthrough on how to get your fork updated: [Syncing a fork](https://help.github.com/articles/syncing-a-fork/)

## Handling Merge Conflicts
Merge conflicts can be pretty unpleasant to deal with, but they're very important to make sure we keep our code base stable! There a couple of ways you can handle a merge conflict.

#### Method 1: Edit the Files
Open your conflicting files with a text editor, such as Notepad++. Lines inside the code will indicate where the conflict occurred. Just clean up the code and make sure it works, then try committing again.

#### Method 2: Stash it Away
If you don't want to bother the merge conflict for whatever reason, you can just run `git stash .` to stash away all your changes. You will have to retype your code in this case, which generally isn't a big issue if your changes were small.

#### Method 3: Different Directory
If you don't want to go through editing the files, you can change your local directory's name and clone a fresh copy. Then, go back and compare the differences between the 2 directories and add changes as needed.

This method can be pretty tedious, and isn't necessarily recommended. But if you keep running into issues, sometimes it's better to just start with a fresh copy.
