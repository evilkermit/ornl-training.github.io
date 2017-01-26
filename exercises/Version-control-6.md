---
layout: exercise
title: Version Control 6
---

*Version control exercises 6-9 assume that you are working in pairs to add and
 modify files in a common repository. The files are available in the
 [`data`](https://github.com/nyu-cds/courses/tree/master/data) and
 [`code`](https://github.com/nyu-cds/courses/tree/master/code) directories of
 the course repository.*

You're working on a large project trying to predict diversity hotspots. Another
member of your collaborative team has produced a series of files that contain
lists of areas that resulted from a series of modeling exercises. Each filename
begins with the word `areas` and ends with `.txt`. 

Your team decides that everything will be kept in a common repository, and to 
name the repository using a combination of your netIDs and `assignment2`. For example,
if your netIDs are `aaa1` and `bbb2` you would name the repository `aaa1_bbb2_assignment2`.
Create the repository under the `nyu-cds` organization on GitHub. Make sure that both users have
write access to the repository by choosing the `Settings` tab, then `Collaborators & teams',
the adding any missing users as a Collaborator.

Each user should clone the repository to their computer. One user should download 

A programmer has whipped up a small python script called `rich_pred.py` that
takes a single file containing a list of areas, one per line, and returns the
area and the predicted richness. The script can be downloaded using the
command `curl -O {{ site.github.url }}/code/rich_pred.py`. One user should 
download this script and commit it to the repository.

Navigate to the main working directory for your repository
and update it from the command line using `git pull`. This will place the
necessary files in your main directory. Move the files into the directory you
created for this assignment by using `git mv filename new_location`, commit
this change with an appropriate commit message, and push them back to the
central repository.
