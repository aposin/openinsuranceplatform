


# Coding Manifest
### Introduction
We are very happy, you are interested in this project! :metal:   

If you have any questions, please read the relevant docs on this GitHub repositories and our FAQ on the website first, there is a good chance some questions may be answered already.

The contributed code, task, concept or design needs to fit into the general system architecture and must provide the key principles described below.

## 1. How we work
### 1.1 Branches
In this project there will be one branch: 
> **master**  
>This is the projects main branch, where all Pull Requests, will be merged into. Of course this branch may be instable.  
 
We will not provide a stable branch. Stable versions will be tagged directly on the master branch.

### 1.2	Workflow
In our projects we prefer a lightly customized GitHub Workflow, to get a more detailed level in the pull request / review process. Basic concept is built on the following standard [workflow](https://guides.github.com/introduction/flow/).

The key aspects of the used workflow are as follows:
- Each developer pushes to their own repository and pulls from others.
- Developers who want to make a change to another repository, create a fork on GitHub and work on their own clone.
- When forked repositories are ready to be merged, Pull Requests are sent to the original repository maintainer.
- The Pull Requests include all of the proposed changes, project and code specific policies and their associated discussion threads.
- Whenever a Pull Request is accepted, the change is merged by the maintainer (integration manager and/or dictator) and pushed to their blessed repository.

In order to be able to contribute to one of the association’s projects you must open a Pull Request. You should usually open a Pull Request in the following situations:
- Submit trivial fixes (for example, a typo, a broken link or an obvious error)
- Start work on a contribution that was already asked for, or that you’ve already discussed, in an issue
- A Pull Request may be one of the following types:  
  - idea for a solution (as basis for further exchange)
  - solutions for an (open) issue
  - bugfix
  - new feature implementation  
  - code parts / snippets for a related issues
  - improvement of code  
  - new documentation / documentation changes
  - anything else relevant to the project
  
A Pull Request doesn’t have to represent finished work. It’s usually better to open a Pull Request early on, so others can watch or give feedback on your progress. Just mark it as a “WIP” (Work in Progress) in the subject line. You can always add more commits later.

Please check out our [contribution guideline](CONTRIBUTING.md) for a detailed description.

### 1.3	Issues / Pull requests mandatory information
For creating Issues or Pull Requests please use the provided templates. 
Our maintainers will check the formal requirements first. 

Please check out our [contribution guideline](CONTRIBUTING.md) for a detailed description.

## 2 Project Standards & Quality Standards

### 2.1 Coding Standards

New contributions should meet the general java code conventions (see <https://google.github.io/styleguide/javaguide.htmll>).

All code contributions must meet the following coding guidlines:

* Your code must not contain any compile errors or warnings (some warnings reported by Eclipse IDE may be allowed)
* Your code must not contain any problems reported by SpotBugs
* Don't implement god classes (classes with several 1,000 lines of code)
* Public API (classes, methods, variables, ...) must contain Javadoc. It is recommended also to document internal API.
* Don't commit Sysouts. Use logger to monitor the correct and expected program workflow.
* Implement JUnit-Tests against new and changed code parts.
* All JUnit-Tests must pass (green).
* JUnit-Tests should be integrated into the buid process (e.g. Maven).
* Binary artifacts (dlls, jars, etc.) are not allowed to be checked in. They should be referenced from the provided Nexus server.

### 2.2 Recommendations and hints

* Use the proposed Eclipse IDE for code contributions. 
* Use the proposed setup process Oomph of the project. (if any) 
* Use the AdoptOpenJDK JVM binaries from <https://adoptopenjdk.net/>
* Use SpotBugs to identify and avoid bad and illegal coding patterns (a reference configuration will follow soon).
* Use SonarQube to identify code smells, bugs and vulnerabilities.
* Think about modularity during the implementation (e.g. new features can be added as optional artifacts). 
* Code and documentation must be done only in English.
* Think about appropriate names for classes, methods and variables
  * Don't use naming shortcuts, e.g. EM for ExecutionManager
  * Don't use only general names (e.g. Manager, Util, etc.)
  * Name the classes, methods and variables suitable to their responsiblity (e.g. IRunnable implementation checking the version can be called CheckVersionRunnable)

Your code needs to run on all supported systems. (Java / operating systems). 

### 2.3  Conventions
The contributed code, task, concept or design needs to fit into the general system architecture and must provide the following key principles:

##### Internationalization
- Always use English language for names, variables, classes, definitions, packages, comments etc. 
- outsourcing from text parts into properties (resource files), so that the project can be easily translated
- no queries against locale specific  
- developer messages might not need to be internationalized (e.g., debug logging, exception messages not relevant to the user, etc).

##### Scalability
- Every new extension must be open and designed so they are easily extended for other usecases. Other requirements must not be influenced in any case. 

##### Multi Tenancy
- Functional or technical extensions must fit the multi-tenancy concept.

##### Multi-Currency
- Functional or technical extensions must fit the multi-currency concept.

##### Time Zones
- Functional or technical extensions must fit the the current time-zone concept.

### 2.4 Tests
- Implement JUnit-Tests against new and changed code parts.
- All JUnit-Tests must pass (green).

### 2.5 Versioning
versioning (tdb)

## 3 Development workflow

Creation of new functional and technical artefacts may follow our standardized development process:
- General approval for project relevance.
- Conception/Discussion for changes in the data model
- Creation of a functional design (if needed) with a follow-up approval
- Creation of a technical design (if needed) with a follow-up approval
- Implementation of the functionality / feature 
  - Please stick to our standards and general architecture guidelines:
    -  Implementation should be in the correct plugins (for modularization), packages or classes. 
    -  Strictly make use of the correct layers (Business-, Dialog-, UI-,Adapter) (if needed)
- Implementation of Unit- and/or Integration Tests
- Review from one of our maintainers
  - Always keep in mind, that the code must fulfill performance and security requirements in order to get accepted.






