# Contributing to Open Insurance Platform
Thank you for considering a contribution to Open Insurance Platform! 
We're thrilled that you'd like to contribute to this project. Your help is essential for keeping it great. 

This guide explains how to:

* maximize the chance of your changes being accepted
* work on the open insurance platform's code base
* get help if you encounter trouble

## Get in touch

Before starting to work on a feature or a fix, please open an issue to discuss the use case or bug with us. This can save both you and us a lot of time.
For any non-trivial change, we'll ask you to create a short design document explaining:

* Why is this change done? What's the use case?
* What will the API look like? (For new features)
* What test cases should it have? What could go wrong?
* How will it roughly be implemented? (We'll happily provide code pointers to save you time)

This can be done directly inside the GitHub issue.

## Contributing

[fork]: https://github.com/ORG/REPO/fork
[pr]: https://github.com/ORG/REPO/compare
[style]: STYLEGUIDE
[quality-manifest]: CODING_MANIFEST.md
[code-of-conduct]: CODE_OF_CONDUCT.md

Please note that this project is released with a [Contributor Code of Conduct][code-of-conduct]. By participating in this project you agree to abide by its terms.

### Reporting a bug or creating a feature request

Please create a new issue in github using one of the provided templates, and make sure to attach the provided labels.

### Submitting a pull request (can include source code and/or documentation)

0. [Fork][fork] and clone the repository
0. Create a new branch: `git checkout -b my-branch-name`
0. Make your change and remember to add tests
0. Build the project locally and run local tests
0. Push to your fork and [submit a pull request][pr]
0. Pat your self on the back and wait for your pull request to be reviewed and merged.

Here are a few things you can do that will increase the likelihood of your pull request being accepted:

- Follow the [style guide][link to styleguide].
- Write tests.
- Keep your change as focused as possible. If there are multiple changes you would like to make that are not dependent upon each other, submit them as separate pull requests.
- Write [good commit messages](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html).

## How to contact us

[Not sure on how to contact us about]

### Code Change Guidelines and Quality Standards

The contributed code, task, concept or design needs to fit into the general system architecture and must provide the following key principles found in this [quality quide][quality-manifest]

All code contributions should contain the following:

* Unit Tests for any logic introduced
* Integration Test coverage of the bug/feature at the level of build execution. 

Your code needs to run on all supported Java versions and operating systems. 

* Normalise file paths in tests. The `org.projectname.util.TextUtil` class has some useful functions for this purpose.


## General GitHub resources on how to start with contributions

- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
- [Using Pull Requests](https://help.github.com/articles/about-pull-requests/)
- [GitHub Help](https://help.github.com)
