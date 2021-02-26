---
layout: default
title: Code Contribution and Code Reviews
short-title: Coding
---

## Group has been working continuously on the project

Sufficient
:	Work on the project has been spread over the whole course. Every team member has committed multiple times each week and the commit has a reasonable size that translates to the individually expected workload.

Excellent
:	All team members have code contributions throughout most of the course.
	Contributions do not follow bursts, but spread out over time.


## Individual commits are focused

Sufficient
:	Commits have short and meaningful commit messages that describe the change.

Excellent
:	With the exception of a few refactoring commits, most commits are very focused:
	The commits have have a reasonable size and only affect a couple of files.
	Commit messages are crystal clear and summarize the change.


## The group has used feature branches or merge requests to isolate individual features during development.

Sufficient
: The group has used feature branches or merge request for important contributions.

Excellent
: Most work has been performed in feature branches or merge requests.

## Isolated feature branches or merge requests have been merged back into the main development line timely.

Insufficient
: The group has not used feature branches to isolate work.

Sufficient
: Most features branches were merged back within a week.

Excellent
: Most feature branches were merged back within three days.


## Group has applied code reviews ("merge requests") before merging changes into the main branch.

Insufficient
: The group has not used feature branches to isolate work.

Sufficient
:	Large changes have been reviewed in GitLab before being merged into the main branch.

Excellent
:	Most changes have been reviewed.
	The reviews have been thorough and frequently lead to iterative improvements of the contributed code.

## Build Server was important part of the development process.

Sufficient
:	Failing builds of the main branch have usually been fixed within a day.

Excellent
:	Failing builds on all branches have directly been fixed.

## Group strives to produce code with style and structure

Sufficient
: Outsiders of the project are able to understand the code base. Most classes have a reasonable size and are distributed into meaningful packages that communicate the corresponding system part. Style violations that are reported by the build server get eventually fixed.

Excellent
: The code is easy to understand for outsiders. Most classes and especially interfaces are well commented, the overall system has a clear design that immediate stands out when inspecting the code base, and the package structure makes it trivial to navigate to the right source code. The group has chosen meaningful names for most elements (classes, field, methods, variables, ...). Style violations that are reported by the build server get immediately fixed.

## The resulting code has been tested

Sufficient
: Basic tests exist that cover the most important/critical parts of the system. Parts that are hard to test, like the UI, are not covered by the automated unit tests and are left for manual testing. Testing related build failures get eventually fixed.

Excellent
: Integration tests get broken down into unit tests for the individual components in most parts of the system, especially for the REST API. Also substantial parts in the front-end are tested. For the parts that are hard to test, concrete test plans exist that describe the manual steps to be executed. Testing related build failures get immediately fixed.
