---
title: Creating a project repo
permalink: /02-creating-a-project-repo
layout: episode
---

At the end of this episode, learners will be able to:
* Define what a "repo" is
* Create a GitHub repository
Teaching 15 minutes

A repository is a place to store all of the components of a single project, or parts of a single project if that project is very large. It is not good practice to have multiple projects in a single repository.

"Repo" is a common abbreviation for repository. We will use it for the remainder of this workshop.

[Create a new repo](https://github.com/new) if you intend on creating everything from scratch - including website templates for GitHub pages.

[Import (aka clone) a repo](https://github.com/new/import) if you would like to reuse existing content without manually copying files over, and you intend your new repo to have no ongoing relationship with the repo you are copying.

[Fork a repo](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo) if you wish to work on your own version of a project that maintains a relationship with the upstream (original) repo, or if you wish to propose changes to an existing repo.

**Demonstration** (10 minutes): Create a new public repository with a description and a README file.
![screenshot](/images/demo-repo.png)


1. Log into GitHub
1. Select new repository button
1. No template
1. Enter a good name and description
1. Check the correct boxes
  [x] add a readme
  [] .gitignore
  [] choose a licence

**Note**: GitHub lets you choose a licence when creating a new repository. None of them are appropriate for a non-software project in Australia - the Creative Commons Zero licence has dubious legality here. Unfortunately, GitHub does not let you apply a Creative Commons Attribution 4.0 or derivative license at this step, but we can add one later.

If you are working for an organisation, it might already have its own GitHub presence. You might need to contact one of your colleagues to have a repo created. When you do, specify whether you want a new repository or to clone an existing one. You will also need to provide a list of the collaborators who own the repo.
