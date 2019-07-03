# Contributing to TAO

> When contributing to the TAO project, please first discuss the change you wish to make via issue.

Contributions to the TAO codebase are made using the fork & pull model.
This contribution model has contributors maintaining their own copy of the forked codebase (which can easily be synced with the main copy). The forked repository is then used to submit a request to the base repository to “pull” a set of changes. For more information on pull requests, please refer to [GitHub Help](https://help.github.com/articles/about-pull-requests/).

The TAO development team will review all issues and contributions submitted by the community of developers in the first in, first out order. During the review, we might require clarifications from the contributor. If there is no response from the contributor within two weeks, the pull request will be closed.

## Contribution process

If you are a new GitHub user, we recommend that you create your own [free GitHub account](https://github.com/signup/free). This will allow you to collaborate with the TAO development team, fork the TAO project and send pull requests.

1. Check the open an closed issues for similar proposals of intended contribution before starting work on a new contribution.
2. Create and test your work.
3. Fork the repository of the TAO extension you wish to contribute.
4. Create a branch that follows the [GitFlow](https://datasift.github.io/gitflow/IntroducingGitFlow.html) branching model.
5. Once development has been done, create a pull request that targets the development branch of the extension you are contributing.
6. If your code depends on changes in another extension, create a draft pull request, until all required pull requests are created.
7. Once your contribution is received the TAO development team will review the contribution and collaborate with you as needed.

## Code of Conduct

### Our Pledge

In the interest of fostering an open and welcoming environment, we as
contributors and maintainers pledge to make participation in our project and
our community a harassment-free experience for everyone, regardless of
any differences between us.

### Our Standards

Examples of behavior that contributes to creating a positive environment
include:

* Using welcoming and inclusive language
* Being respectful of differing viewpoints and experiences
* Gracefully accepting constructive criticism
* Focusing on what is best for the community
* Showing empathy towards other community members

Examples of unacceptable behavior by participants include:

* The use of sexualized language or imagery and unwelcome sexual attention or
advances
* Trolling, insulting/derogatory comments, and personal or political attacks
* Public or private harassment
* Publishing others' private information, such as a physical or electronic
  address, without explicit permission
* Other conduct which could reasonably be considered inappropriate in a
  professional setting

### Our Responsibilities

Project maintainers are responsible for clarifying the standards of acceptable
behavior and are expected to take appropriate and fair corrective action in
response to any instances of unacceptable behavior.

Project maintainers have the right and responsibility to remove, edit, or
reject comments, commits, code, wiki edits, issues, and other contributions
that are not aligned to this Code of Conduct, or to ban temporarily or
permanently any contributor for other behaviors that they deem inappropriate,
threatening, offensive, or harmful.

### Scope

This Code of Conduct applies both within project spaces and in public spaces
when an individual is representing the project or its community. Examples of
representing a project or community include using an official project e-mail address, posting via an official social media account or acting as an appointed
representative at an online or offline event. Representation of a project may be
further defined and clarified by project maintainers.

### Enforcement

Instances of abusive, harassing or otherwise, unacceptable behavior may be
reported by contacting the project team at [community@taotesting.com](mailto:community@taotesting.com). All
complaints will be reviewed and investigated and will result in a response that
is deemed necessary and appropriate to the circumstances. The project team is
obligated to maintain confidentiality concerning the reporter of an incident.
Further details of specific enforcement policies may be posted separately.

Project maintainers who do not follow or enforce the Code of Conduct in good
faith may face temporary or permanent repercussions as determined by other
members of the project's leadership.

### Attribution

This Code of Conduct is adapted from the [Contributor Covenant homeapge](http://contributor-covenant.org), version 1.4,
available at [https://www.contributor-covenant.org/version/1/4/code-of-conduct.html](https://www.contributor-covenant.org/version/1/4/code-of-conduct.html).

### Templates

Contribution Template

```
### Subject of the issue
Describe your issue here.

### Your environment
* Which browser and version are you using?
* Which PHP version are you using?
* Which Database engine and version are you using?
* Which Web server are you using?
* Which extensions are installed, and what version are they?

### Steps to reproduce
Tell us how to reproduce this issue.

### Expected behaviour
Tell us what should happen

### Actual behaviour
Tell us what happens instead

```

Pull Request Template

```
_Before you submit a pull request, please make sure you have to following:_

- [ ] The title of this pull request offers a good description of what is changed (as it is used in release notes).
- [ ] Your branch follows the [GitFlow](https://datasift.github.io/gitflow/IntroducingGitFlow.html) branching model.
- [ ] The code follows the [best practices (to be defined)](#).
- [ ] The functionality has been manually tested (if applicable).
- [ ] The update script has been run, and causes no issues.
- [ ] The functionality has been tested after a clean install.
- [ ] A new unit test has been created, or the existing test has been updated.
- [ ] All new and existing tests passed.
- [ ] The module version has been bumped in both the manifest.php, and Updater.php files.

---
**Depends on**
- [ ] List other pull requests that depend on this pull request
- [ ] Also list pull requests that require this pull request
---

Describe the changes you made in your pull request here

**Testing the changes**

Please provide a description of how to test the changes made in this pull request.
```
