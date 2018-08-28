# Coding Manifest
### Introduction
We are very happy, you are interested in this project! :metal:   

If you have any questions, please read the relevant docs on this GitHub repositories and our FAQ on the website first, there is a good chance some questions may be answered already.

In an early project phase we will work in an so called __PUSH__ model, where our lead maintainers will push big snapshots ("big-
bang-commits"), to this project's repositories.

As we are currently trying to optimize our workflow and keep this project running, this PUSH phase continues until we have cleaned up some technical issues. After that we will switch to the standard Git Pull workflow model.
In this target szenario, every commit will be related to issue(s) and/or pull request(s) and thereby be much more transparent.

The following chapter mainly describes the target __PULL__ scenario. Even if we are not yet in the PULL scenario, of course we will try to accept and handle contributions, even though it means higher manual effort for our maintainers.

## 1. How we work
### 1.1 Branches
In this project there will be two branches: 
> **dev**  
>This is the projects main branch, where all Pull Requests, will be merged into. Of course this branch may be instable.  

>**stable**  
>In this branch concret versions will be held. See more under point 2.4 Versioning

### 1.2	Workflow
In our projects we prefer a lightly customized GitHub Workflow, to get a more detailed level in the pull request / review process. Basic concept is built on the following standard [workflow](https://guides.github.com/introduction/flow/).

The key aspects of the used workflow are as follows:
- Each developer pushes to their own repository and pulls from others.
- Developers who want to make a change to another repository, create a fork on GitHub and work on their own clone.
- When forked repositories are ready to be merged, pull requests are sent to the original repository maintainer.
- The pull requests include all of the proposed changes, project and code specific policies and their associated discussion threads.
- Whenever a pull request is accepted, the change is merged by the maintainer (integration manager and/or dictator) and pushed to their blessed repository.

In order to be able to contribute to one of the association’s projects you must open a pull request. You should usually open a pull request in the following situations:
- Submit trivial fixes (for example, a typo, a broken link or an obvious error)
- Start work on a contribution that was already asked for, or that you’ve already discussed, in an issue
- A pull request may be one of the following types:  
  - idea for a solution (as basis for further exchange)
  - solutions for an (open) issue
  - bugfix
  - new feature implementation  
  - code parts / snippets for a related issues
  - improvement of code  
  - new documentation / documentation changes
  - anything else relevant to the project
  
A pull request doesn’t have to represent finished work. It’s usually better to open a pull request early on, so others can watch or give feedback on your progress. Just mark it as a “WIP” (Work in Progress) in the subject line. You can always add more commits later.

Please check out our [contribution guideline](CONTRIBUTING.md) for a detailed description.

### 1.3	Issues / Pull requests mandatory information
For creating issues or pull requests please use the provided templates. 
Our maintainers will check the formal requirements first. 

Please check out our [contribution guideline](CONTRIBUTING.md) for a detailed description.

## 2 Project Standards

### 2.1 Coding standards / conventions
The contributed code, task, concept or design needs to fit into the general system architecture and must provide the following key principles:

##### Internationalization
- Always use english language for names, variables, classes, definitions, packages, comments etc. 
- outsourcing from text parts into properties (resource files), so that the project can be easily translated
- no queries against locale specific  

##### Scalability
- Every new extension must be open and designed so they are easily extended for other usecases. Other requirements must not be influenced in any case. 

##### Multi Tenancy
- Functional or technical extensions must fit the multi-tenancy concept.

##### Multi-Currency
- Functional or technical extensions must fit the multi-currency concept.

##### Time Zones
- Functional or technical extensions must fit the the current time-zone concept.

Creation of new functional and technical artefacts may follow our standardized development process:
- General approval for project relevance.
- Conception/Discussion for changes in the data model
- Creation of a functional design (if needed) with a follow-up approval
- Creation of a technical design (if needed) with a follow-up approval
- Implementation of the functionality / feature 
  - Please stick to our [coding standards](docs/coding-standards.html) and general architecture guidline:
    -  Implantation in the correct plugins (for modularization), packages or classes. 
    -  Strictly make use of the correct layers (Business-, Dialog-, UI-,Adapter)
- Implementation of Unit- and/or Integration Tests
- Review from one of our maintainers
  - Always keep in mind, that the code must fulfill performance and security requirements in order to get accepted.

Please check out our [coding standards](docs/coding-standards.html).

### 2.2 General architecture
architecture (tbd)

### 2.3 Tests
tests (tbd)

### 2.4 Versioning
versionign (tdb)

## 3. Communication and Tools
### 3.1	Roles
This open source project contains the following types of people:

- Author: The person/s or organization that created the project. The association itself.
- Owner: The person/s who has administrative ownership over the organization or repository. The association itself.
- Maintainers: Contributors who are responsible for driving the vision, managing the organizational aspects of the project and handle contributions. (They may also be authors or owners of the project.) The Project Engineering Committee, described in the Governance Charter will execute this tasks with defined sub roles:
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
- Discussion forums or mailing lists: Some projects may use these channels for conversational topics (for example, “How do I…“ or “What do you think about…“ instead of bug reports or feature requests). Others use the issue tracker for all conversations. For now there is no specific forum set up.

## 4 Tools
Currently there are no specific third party tools for communication or issue tracking in use.
