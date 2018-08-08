## Introduction
We are very happy, you are interested in this project! :metal:   
If you have any questions, please read the relevant docs on this GitHub repositories and our FAQ on the website first, there is a good chance some questions may be answered already.

In an early project phase we will work in an so called __PUSH__ model, where our lead maintainers will push big snapshots ("big-
bang-commits"), to this project's repositories.

As we are currently trying to optimize our workflows and keep this project running, this PUSH phase continues until we have cleaned up some technical issues. After that we will switch to the standard Git Pull workflow model.
In this target szenario, every commit will be related to issue(s) and/or pull request(s) and thereby much more transparent.

The following chapter mainly describes the target __PULL__ scenario. In the push model of course we will try to accept contributions even though it means bigger manual effort for our maintainers.

## 1. How we work
### 1.1 Development Worfklow 
In this project there will be two (2) main branches  
> **dev**  
>This is the projects main branch, where all Pull Requests, will be merged into. Of course this branch may be instable.  

>**stable**  
>In this branch concret versions will be held. See more under point 2.4 Versioning

### 1.2	Workflow
In our projects we prefer a lightly customized GitHub Workflow, to get a more detailed level in the pull request / review process. Basic concept ist build on the following standard [workflow](https://guides.github.com/introduction/flow/)

The key aspects of the used workflow are as follows:
- Each developer pushes to their own repository and pulls from others.
- Developers who want to make a change to another repository, create a fork on GitHub and work on their own clone.
- When forked repositories are ready to be merged, pull requests are sent to the original repository maintainer.
- The pull requests include all of the proposed changes, project and code specific policies and their associated discussion threads.
- Whenever a pull request is accepted, the change is merged by the maintainer (integration manager and/or dictator) and pushed to their blessed repository.

In order to be able to contribute the one of the association’s projects you must open a pull request. You should usually open a pull request in the following situations:
- Submit trivial fixes (for example, a typo, a broken link or an obvious error)
- Start work on a contribution that was already asked for, or that you’ve already discussed, in an issue
- A pull request may be one of the following types:  
  - idea for a solution (as basis for further exchange)
  - solutions for an open (or new) issue
  - bugfix
  - new Feature implementation  
  - code parts / snippets for a related issue;
  - improvement of code  
  - new documentation / documentation changes
  - anything else relevant to the project
  
A pull request doesn’t have to represent finished work. It’s usually better to open a pull request early on, so others can watch or give feedback on your progress. Just mark it as a “WIP” (Work in Progress) in the subject line. You can always add more commits later.

Please check out our [contribution guideline](CONTRIBUTING.md) for a detailed description.

### 1.3	Issues / Pull requests mandatory information
For creating issues or pull requests please use the provided templates. 

Our maintainers will check the formal requirements first. 

### 1.4 What happens after your contribution?
After you submit a contribution, one of the following will happen:
- Someone requests changes to your contribution.
It’s common that you’ll be asked to make changes to your contribution, whether that’s feedback on the scope of your idea, or changes to your code. When someone requests changes, be responsive. They’ve taken the time to review your contribution. Opening a PR and walking away is bad form. If you don’t know how to make changes, research the problem, then ask for help if you need it.
If you don’t have time to work on the issue anymore (for example, if the conversation has been going on for months, and your circumstances have changed), let the maintainer know so they’re not expecting a response. Someone else may be happy to take over.

- Your contribution gets accepted.
You’ve successfully made a contribution to our project!

- Your contribution doesn’t get accepted.
Your contribution may or may not be accepted in the end. Hopefully you didn’t put too much work into it already. If you’re not sure why it wasn’t accepted, it’s perfectly reasonable to ask the maintainer for feedback and clarification. 

- You don’t get a response.

## 2 Project Standards

### 2.1 Coding standards / conventions
Please check out our [coding standards](docs/coding-standards.html)

### 2.2 General architecture
architecture (tbd)

### 2.3 Tests
tests (tbd)

### 2.4 Versioning
versionign (tdb)

## 3. Communication and Tools
### 3.1	Roles
This open source project has the following types of people:

- Author: The person/s or organization that created the project. The association itself.
- Owner: The person/s who has administrative ownership over the organization or repository. The association itself.
- Maintainers: Contributors who are responsible for driving the vision, managing the organizational aspects of the project and handle contributions. (They may also be authors or owners of the project.) Project Engineering Committee will execute this tasks with defined sub roles
  - Integration Manager
Is responsible for handling and validating pull requests regarding the contribution guidelines and the overall strategic scope.
  - (Dictator, if any) 

- Contributors: Everyone who has contributed something back to the project.
- Community Members: People who use the project. They might be active in conversations or express their opinion on the project’s direction.


### 3.2	Communication
If you have any questions please contact us directly via GitHub. 

- Issue tracker: Where people discuss issues related to the project.
For issue tracking and communication at this OSS project the build in GitHub issue section is the center of communication for all bugs, features and discussions.
- Pull requests: Where people discuss and review changes that are in progress.
- Discussion forums or mailing lists: Some projects may use these channels for conversational topics (for example, “How do I…“ or “What do you think about…“ instead of bug reports or feature requests). Others use the issue tracker for all conversations. For now there is no specific forum planned.

## 4 Tools
Actuall no specific third party tools for communication or issue tracking are used.
