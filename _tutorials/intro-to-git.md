---
title: Introduction to Git
author: Thomas Tumiel
layout: tutorials
---

<div class="alert alert-block alert-info">
<h5>Why is this Important:</h5>
Git is fundamental to collaborating on software. It allows teams to independently work
on the same project and merge those changes together.
<br />
<strong>Time to read: 15 minutes</strong>
</div>

What is Git?

> Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

Have you ever made a change to a file and saved it as `document-v2` and then made another change and saved it as `document-v2-latest` and continued with that until you weren't quite sure which was the latest. Well Git allows you to track these changes automatically - not just across your own versions but between other people's versions as well. Think Google Drive for a large, multi-file project.

But Git can be a bit confusing to a beginner - so don't get caught up with the various commands that you can use but rather start with the commands that you will use.

Start by [downloading Git](https://git-scm.com/).

## Make a Git Repository

Lets start by making a directory with our project name. For now let's call it `first-git-repo`. Now open a terminal window (if you're on Linux or Mac) or open Git Bash in that directory by right clicking and selecting `Open terminal` or `Open Git Bash`.

Now type the command `git init`.

This command initialises a "Git repository" - a collection of code and other files. A repository is also called a repo for short.

## Make a File

Now create an empty text file in that directory called `file.txt`. We will now commit this file to our Git repository using the commands `git add file.txt` and `git commit -m "Adding a file"`.

Lets break down what these commands do:

- `git add`: this command tells git to add the following file to a "staging area". This staging area simply allows you to separate the files you want to save to the repo and ones that you don't.
- `git commit`: this command tells git to save or "commit" the file to the repository. The `-m` allows the user to add a message to the save. In this case we added the message "Adding a file".

## Make a Change

Now we can make a change to the file. Add some text inside it like:

```
This is a file.
```

Then we can go through the same process:

```bash
git add file.txt
git commit -m "Updating a file"
```

Now we have updated the changes to our file without needing to save it as `file-v2.txt` or something like that. But what's the point of this?

## Collaboration

If you've ever collaborated on a project over Google Docs then you will know how much easier that is than emailing the same document to everyone and wondering who has the latest version. Git allows this same workflow for much larger projects, whether its code or something else. Join us in the next section [Intro to GitHub](/tutorials/intro-to-github) to learn how to share your projects with others.
