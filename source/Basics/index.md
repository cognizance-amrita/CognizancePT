---
title: Git & Github
date: 2022-01-29 10:37:33
---
> Git simplifies the process of working with other people and makes it easy to collaborate on projects. Team members can work on files and easily merge their changes in with the master branch of the project. GitHub is an open-source repository hosting service, sort of like a cloud for code. It hosts your source code projects in a variety of different programming languages and keeps track of the various changes made to every iteration. Other GitHub users can review your code and propose changes.

## What is GitHub?
##### GitHub is a hosting site where developers and programmers can upload the code they create and work collaboratively to improve it. A defining feature of GitHub is its robust version control system. The version control lets coders tweak software—potentially fixing bugs or improving efficiency—without affecting the software itself or risking the experience of any current users. Proposed changes can be easily merged into the live software after the proposals are reviewed and approved. <br><br> GitHub can integrate with common platforms and services such as Amazon, Google Cloud, and Code Climate. It can highlight syntax in more than 200 different programming languages. GitHub isn’t the only version control software development site, but it is perhaps the most popular. 

<br>

<hr>

## How GitHub Works?
#### Of the many features offered by GitHub, three of the most consequential include forking, pull requests, and merging. Forking a project creates a copy that allows you to experiment freely without affecting the original project. <br><br> When you’re happy with the changes you’ve made, you can submit a pull request. The pull request is sent to the project owner, who can review the changes you’ve made and ask any follow-up questions. If the project owner likes the changes, they’ll merge your pull request, which applies the changes from your forked project to the original code.

<br>

<hr>

## Have Your Code Reviewed By the Community
#### GitHub functions as a sort of social media site for developers and programmers. It allows your work to get out in front of the public. It is one of the largest coding communities around, so using it can provide wide exposure for your project. The more people you have to review your project, the more attention and use it is likely to attract. <br><br> For instance, imagine that you have the basic skeleton for a project. The project does what you want it to do, but you’re not always sure how the wider population will implement it—or if it even works for everyone. <br><br> This is where GitHub users step in. When you post your project on GitHub, the wider community of programmers and hobbyists can download and evaluate your work. They can alert you to possible issues, such as conflicts or unforeseen dependency issues. They may even propose solutions to those problems, saving you the work.

<br>

<hr>

## Track Changes Across Versions
#### GitHub tracks changes in a changelog, so you can know exactly what is changed each time. This feature is especially helpful for looking back in time and quickly identifying changes a collaborator made.

<br>

<span style="color: #FA4EAB">**NOTE: The version tracking on GitHub is similar to working on a Google Doc with a team. You can see who made changes and when they made them, going back to the project's creation.**</span>

<br>

<hr>

## Open-Source Benefits
#### The projects on GitHub are a form of open-source code. Adopted by government agencies such as the Department of Defense, open-source code essentially allows anyone to review and propose changes to the code. <br><br> Open-source projects tend to be more flexible because they respond more rapidly to market demands. Closed-source programs might exist in a bubble while trying to convince a target market of its value, as opposed to being genuinely responsive. GitHub provides a community where programmers are constantly working to solve current problems and making solutions available to the public.

<br>

<hr>

## Find Talent
#### Because of the breadth of the GitHub community, you can sometimes find programmers working on similar projects or who have skills, experiences, or a vision that offers a good fit for your organization. By being a part of the community, you can identify these people, work with them, and possibly even bring them on board to work for you.

<br>

<hr>

## Develop and Implement a Management Strategy
#### You likely have multiple people working on projects at the same time, and many of them may be in different locations—possibly even in different countries. By using a version control system like GitHub, collaborators can work together without stepping on each others’ toes. <br><br> For example, you don’t want one collaborator addressing a problem in a way that conflicts with another collaborator’s approach. GitHub makes it easy for everyone to know and see what everyone else is doing, and projects can be managed in whatever way is best for your staff and your organization’s needs.
<br>

<hr>

## VCS-(Version Control System)
#### Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later. <br><br>Many people’s version-control method of choice is to copy files into another directory (perhaps a time-stamped directory, if they’re clever). This approach is very common because it is so simple, but it is also incredibly error prone. It is easy to forget which directory you’re in and accidentally write to the wrong file or copy over files you don’t mean to.<br><br>To deal with this issue, programmers long ago developed local VCSs that had a simple database that kept all the changes to files under revision control.<br><br>A version control system or VCS, also know as revision control or source control system, is a software utility that tracks and manages changes to a filesystem. … When operating at the filesystem level, a VCS will track the addition, deletion, and modification actions applied to files and directories.

<br>

<hr>

## Use of Version Control System
#### <span style="color: #DD4A48">A Repository</span>: It can be thought as a database of changes. It contains all the edits and historical versions (snapshots) of the project. <br><br> <span style="color: #DD4A48">Copy of Work (sometimes called as checkout)</span>: It is the personal copy of all the files in a project. You can edit to this copy, without affecting the work of others and you can finally commit your changes to a repository when you are done making your changes.

<br>

<hr>

## Types of Version Control Systems:
- Local Version Control Systems
- Centralized Version Control Systems
- Distributed Version Control Systems

<br>

<img src="https://cognizance2020.github.io/post/download.png" alt="VCS" style="width:500px;"/>

<br>

<hr>

## Creating an GitHub account
1. Go to [<b><span style="color: #FE83C6">GitHub</span></b>](https://github.com/join).
2. Sign up for GitHub.

*Video Reference*: [<b><span style="color: #FE83C6">Setup GitHub Account</span></b>](https://youtu.be/XaMiHHu_rb4)



<br>

<hr>

## Install Git In Your desktop
#### Kindly see the video and install git bash in your system and set your username and user-email in the Git Bash.
*Video Reference*: [<b><span style="color: #FE83C6">Installing Git</span></b>](https://www.youtube.com/watch?v=YXXp_ht4pwQ&list=PLB5jA40tNf3v1wdyYfxQXgdjPgQvP7Xzg&index=6)


<br>

<hr>

## Git operations
#### To use Git, developers use specific commands to copy, create, change, and combine code. These commands can be executed directly from the command line or by using an application like GitHub Desktop or Git Kraken.

<br>

**<span style="color: #FF6363; font-size: 1rem;">Basic Operations</span>**
#### The following is a summary of basic git operations:
**<span style="color: #B958A5">git add</span>**
<b><div style="background:#212326; margin: 1rem 0; -webkit-border-radius: 4px; padding:0 1rem; ">
Puts current working files into the stage.
</div></b>

**<span style="color: #B958A5">git checkout</span>**
<b><div style="background:#212326; margin: 1rem 0; -webkit-border-radius: 4px; padding:0 1rem; ">
Replaces the current working files with files from a branch.
</div></b>

**<span style="color: #B958A5">git checkout -b</span>**
<b><div style="background:#212326; margin: 1rem 0; -webkit-border-radius: 4px; padding:0 1rem; ">
Creates a new local branch from the current branch's tip.
</div></b>

**<span style="color: #B958A5">git clone</span>**
<b><div style="background:#212326; margin: 1rem 0; -webkit-border-radius: 4px; padding:0 1rem; ">
Clone an existing repository into a new directory.
</div></b>

**<span style="color: #B958A5">git commit</span>**
<b><div style="background:#212326; margin: 1rem 0; -webkit-border-radius: 4px; padding:0 1rem; ">
Commits staged changes to a local branch.
</div></b>

**<span style="color: #B958A5">git commit -a</span>**

<b><div style="background:#212326; margin: 1rem 0; -webkit-border-radius: 4px; padding:0 1rem; ">
     Commits all modified files to a local branch(shorthand for "git add" followed by "git commit" for each modified file).
</div></b>

**<span style="color: #B958A5">git fetch</span>**
<b><div style="background:#212326; margin: 1rem 0; -webkit-border-radius: 4px; padding:0 1rem; ">
Downloads changes from a remote repository into the local clone.
</div></b>

**<span style="color: #B958A5">git merge</span>**
<b><div style="background:#212326; margin: 1rem 0; -webkit-border-radius: 4px; padding:0 1rem; ">
Merges files from a given branch into the current branch.
</div></b>

**<span style="color: #B958A5">git pull</span>**
<b><div style="background:#212326; margin: 1rem 0; -webkit-border-radius: 4px; padding:0 1rem; ">
Fetches remote changes on the current branch into the local clone, and merges them into the current working files.
</div></b>

**<span style="color: #B958A5">git push</span>**
<b><div style="background:#212326; margin: 1rem 0; -webkit-border-radius: 4px; padding:0 1rem; ">
Uploads changes from all local branches to the respective remote repositories.
</div></b>

**<span style="color: #B958A5">git reset</span>**
<b><div style="background:#212326; margin: 1rem 0; -webkit-border-radius: 4px; padding:0 1rem; ">
Makes the current branch point to some specific revision or branch
</div></b>

**<span style="color: #B958A5">git rebase</span>**
<b><div style="background:#212326; margin: 1rem 0; -webkit-border-radius: 4px; padding:0 1rem; ">
Integrates changes from one branch into another. It is an alternative to the better known "merge" command.
</div></b>

**<span style="color: #B958A5">git fork</span>**
<b><div style="background:#212326; margin: 1rem 0; -webkit-border-radius: 4px; padding:0 1rem; ">
Fork will create a copy of the repository in your GitHub account so that you can make changes to the project.
</div></b>

<br>

*Video Reference*: [<b><span style="color: #FE83C6">Basic Operation</span><b>](https://www.youtube.com/playlist?list=PLB5jA40tNf3v1wdyYfxQXgdjPgQvP7Xzg)

<br>

<hr>