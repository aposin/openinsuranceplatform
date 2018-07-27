# Contributing to Open Insurance Platform
Thank you for considering a contribution to Open Insurance Platform! 
We're thrilled that you'd like to contribute to this project. Your help is essential for keeping it great. 

This guide explains how to:

* maximize the chance of your changes being accepted
* work on the open insurance platform's code base
* get help if you encounter trouble

## Prerequisite

#### Code of Conduct

[fork]: https://github.com/ORG/REPO/fork
[pr]: https://github.com/ORG/REPO/compare
[style]: STYLEGUIDE
[quality-manifest]: CODING_MANIFEST.md
[code-of-conduct]: CODE_OF_CONDUCT.md
Please note that this project is released with a [Contributor Code of Conduct][code-of-conduct]. By participating in this project you agree to abide by its terms.

#### Contribution License Agreement

You will need to complete a Contribution License Agreement (CLA) before any pull request can be accepted. When you submit a pull request, a CLA assistant bot will confirm you have completed the agreement, or provide you with an opportunitiy to do so.

## Get in touch

Before starting to work on a feature or a fix, please open an issue (proposal) to discuss the use case or bug with us. This can save both you and us a lot of time.
For any non-trivial change, we'll ask you to create a short design document explaining:

* Why is this change done? What's the use case?
* How is the functional design? 
* How should the technical design look like?
* Are there any dependencies to other parts? 
* What test cases should it have? What could go wrong?
* How will it roughly be implemented? (We'll happily provide code pointers to save you time)

This can be done directly inside the GitHub issue and/or if accepted - later in the pull request.

### Reporting a bug or creating a feature request

Please create a new issue in github using one of the provided templates, and make sure to attach the provided labels.

### Proposal States
###### Open
Open proposals are still under discussion. Please leave your concrete, constructive feedback on this proposal. +1s and other clutter posts which do not add to the discussion will be removed.

###### Accepted
Accepted proposals are proposals that both the community and core team agree should be a part of the project. These proposals are ready for implementation, but do not yet have a developer actively working on them. These proposals are available for anyone to work on.

If you wish to start working on an accepted proposal, please reply to the thread so we can mark you as the implementor and change the title to In Progress. This helps to avoid multiple people working on the same thing. If you decide to work on this proposal publicly, feel free to post a link to the branch as well for folks to follow along.

###### What "Accepted" does mean
* Any community member is welcome to work on the idea.
* The core team _may_ consider working on this idea on their own, but has not done so until it is marked "In Progress" with a team member assigned as the implementor.
* Any pull request implementing the proposal will be welcomed with documentation and code review.

###### What "Accepted" does not mean
* The proposal will ever be implemented, either by a community member or by the core team.
* The core team is committing to implementing a proposal, even if nobody else does. Accepted proposals simply mean that the core  team and the community agree that this proposal should be a part of Open Insurance Platform.

###### In Progress
Once a developer has begun work on a proposal, either from the core s team or a community member, the proposal is marked as in progress with the implementors name and (possibly) a link to a development branch to follow along with progress.

###### Rejected
Rejected proposals will not be implemented or merged into Open Insurance Platform. Once a proposal is rejected, the thread will be closed and the conversation is considered completed, pending considerable new information or changes.

### Submitting a pull request (can include source code and/or documentation)

0. [Fork][fork] and clone the repository
0. Create a new branch: `git checkout -b my-branch-name`
0. Make your change and remember to add tests
0. Build the project locally and run local tests
0. Push to your fork and [submit a pull request][pr]
0. Pat your self on the back and wait for your pull request to be reviewed and merged.

Here are a few things you can do that will increase the likelihood of your pull request being accepted:

- Follow the styleguide in our [coding manifest][quality-manifest].
- Write tests.
- Keep your change as focused as possible. If there are multiple changes you would like to make that are not dependent upon each other, submit them as separate pull requests.
- Write [good commit messages](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html).


## Code Change Guidelines and Quality Standards

The contributed code, task, concept or design needs to fit into the general system architecture and must provide the following key principles found in our [coding_manifest][quality-manifest].

All code contributions should contain the following:

* Unit Tests for any logic introduced
* Integration Test coverage of the bug/feature at the level of build execution. 

Your code needs to run on all supported Java versions and operating systems. 

* Normalise file paths in tests. The `org.projectname.util.TextUtil` class has some useful functions for this purpose.

## How to contact us

The best way to get in touch with us is directly via GitHub. 

Also feel free to write us an email:
hello@aposin.org or hello@opin.org

## General GitHub resources on how to start with contributions

- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
- [Using Pull Requests](https://help.github.com/articles/about-pull-requests/)
- [GitHub Help](https://help.github.com)
