# Working with the TAO User Guide

> This articles is meant to help User Guide authors with their work

The TAO User Guide is located at https://github.com/oat-sa/taohub-userguide/. 

It contains several directories called *User Guide X.X* where *X.X* signifies the TAO version. There is also a directory called *User Guide latest* that starts as a copy of the latest release and is then being improved when TAO changes. It will eventually become the next version.

Each of these directories contains directory for each chapter as well as two directories that have a special meaning.

- *resources* is the place where all media are stored. Usually these are screen shots but it can also be audio files and such. Video files are hosted on [OAT's video channel at Youtube](https://www.youtube.com/channel/UCoTsdyN4jc8QzSEj5A3ot5Q). There is a number of sub directories that for the most part mirror TAO's structure.
- *.meta*: The most important file you find here is called `index.yml`. It is the structure of the User Guide and used to build the navigation menu of the website and other formats.
- All other directories represent a chapter of the User Guide along with the pages.


## Getting started

There are many great guides for the command line usage of git, http://dont-be-afraid-to-commit.readthedocs.io/en/latest/git/commandlinegit.html is just one of them. You can also use GUI tools, probably https://desktop.github.com/ is the best choice for the casual user.

Clone https://github.com/oat-sa/taohub-userguide.git to your hard drive. This will create a directory _taohub-userguide_ on your hard drive with a complete copy of the User Guide.

```
git clone https://github.com/oat-sa/taohub-userguide.git 
```

Check out a new branch, be sure to use a meaningful name for this branch.

```
git checkout -b <branch-name> 
```

Edit or create content for the version you have been assigned for, usually the highest version number or _latest_. Commit your work whenever you have achieved a certain step, at the latest by the end of a day. This means also you have to add new files to git.

```
git add <file-name>
git commit -m "Some meaningful message"
```

Eventually push your changes to GitHub, do this also at least once a day to be sure you have an backup.

```
git push origin <branch-name> 
```

The last step is to make a pull request. Point your browser to https://github.com/oat-sa/taohub-userguide/. There will be a yellow bar with a link to create a pull request. Check your changes on the upcoming window. If you made a mistake, correct it locally and commit/push the files in question again. Once you are satisfied with the outcome, set target to _master_, assign the person OAT has named as your reviewer and hit _Create pull request_.

Please be sure that before you start working again that you update your local copy, since somebody else might have worked on your branch.

```
git pull origin <branch-name> 

## Getting help on markdown
A nice resource is https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
