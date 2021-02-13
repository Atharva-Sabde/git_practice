# Git and its Hub

[Uploading code from local machine to the github repository :](https://www.notion.so/Uploading-code-from-local-machine-to-the-github-repository-5688ff8bea754a2f9d1a37db0598743f)

### GIT:

Git is a free and open source tool that tracks the changes in your code over time  distributed version-control system for tracking changes in any set of files, originally designed for coordinating work among programmers cooperating on source code during software development. 
Git was created by Linus Torvalds in 2005 for development of the Linux kernel, with other kernel developers contributing to its initial development. Since 2005, Junio Hamano has been the core maintainer. As with most other distributed version-control systems, and unlike most client–server systems, every Git directory on every computer is a full-fledged repository with complete history and full version-tracking abilities, independent of network access or a central server.

Initially GIT was only CLI (command line interface)

Introduction of GIT added Distributed Version Control Sytem 

Why need of GIT? HISTORY:

Before GIt , there were different version control systems like:

Earlier Version Control Sytems:

1. Subversion (SVN)
2. Perforce
3. Mercurial
4. Clearcase
5. CVS

But the drawback was:  if the system is offline , you could not Commit the code, and the chances to lose code were high, So after the introduction of Git (distributed Version Control System) this problem was solved as this used *local commit* , means that the changes will be saved as two copies , one on server and another on local system.

### Version Control:

Version control system was first started for linux by linus travolds

Why is version control system needed?
consider an example : You are working on a project with your 2 friends .The project is about a website, and you are working simultaneously on same code files. Then there may occur a point where we will not be able to identify which changes were made by whom and at what time.

1. A way to keep track of changes in files.
2. Collaboration between developers.
3. Keep track of who did what.
4. Merge and Revert
5. Easy recovery if something goes wrong.

![Git%20and%20its%20Hub%20b4d5fc2db51a4ce49ec68cff09e3eb0d/Untitled.png](Git%20and%20its%20Hub%20b4d5fc2db51a4ce49ec68cff09e3eb0d/Untitled.png)

BRANCH - COMMIT - MERGE - REVERT

## GIt commands:

→ All commands are lowercase...

1. clone 
when the repository is present online , but you want to bring it down to your local machine to use it locally.
2. add
Track your files and changes in Git. (when you add  or delete some files)
3. commit
Saves the files on git. 
4. pull
The pull command is used when there are changes on Github and you want to bring those to your local machine.
5. push
Upload Git commits to a remote repository like Github.

---

## Git Workflow

A Git project can be thought of as having three parts:

1. A *Working Directory*: where you’ll be doing all the work: creating, editing, deleting and organizing files
2. A *Staging Area*: where you’ll list changes you make to the working directory
3. A *Repository*: where Git permanently stores those changes as different *versions* of the project

![Git%20and%20its%20Hub%20b4d5fc2db51a4ce49ec68cff09e3eb0d/Untitled%201.png](Git%20and%20its%20Hub%20b4d5fc2db51a4ce49ec68cff09e3eb0d/Untitled%201.png)

- Git is the industry-standard version control system for web developers
- Use Git commands to help keep track of changes made to a project:
    - `git init` creates a new Git repository
    - `git status` inspects the contents of the working directory and staging area
    - `git add` adds files from the working directory to the staging area
    - `git diff` shows the difference between the working directory and the staging area
    - `git commit` permanently stores file changes from the staging area in the repository
    - `git log` shows a list of all previous commits

The GIT chronology:

1 initialize a git repository.

**2.** Check the status of the Git project. You will see multiple files listed in the output as       “Untracked”.

**3.** Add each file to the Git staging area.

**4.** Check the status of the Git project again.

**5.** Make a commit.

**6.** View your Git commit log. If your cursor is stuck in Git log mode, press “q” on your keyboard to escape.

**7.**make some more changes.Click Save.

**8.**Add the file to the staging area.

**9.**Now make a commit.

**10.**View your Git commit log again to identify your commit.

**11.** Revise each file in whatever ways you’d like. Then add your changes to the staging area and make another commit.

![Git%20and%20its%20Hub%20b4d5fc2db51a4ce49ec68cff09e3eb0d/Untitled%202.png](Git%20and%20its%20Hub%20b4d5fc2db51a4ce49ec68cff09e3eb0d/Untitled%202.png)

![Git%20and%20its%20Hub%20b4d5fc2db51a4ce49ec68cff09e3eb0d/Untitled%203.png](Git%20and%20its%20Hub%20b4d5fc2db51a4ce49ec68cff09e3eb0d/Untitled%203.png)

![Git%20and%20its%20Hub%20b4d5fc2db51a4ce49ec68cff09e3eb0d/Untitled%204.png](Git%20and%20its%20Hub%20b4d5fc2db51a4ce49ec68cff09e3eb0d/Untitled%204.png)

changing username and email id in git. : name can be anything but email must match with github.

![Git%20and%20its%20Hub%20b4d5fc2db51a4ce49ec68cff09e3eb0d/Untitled%205.png](Git%20and%20its%20Hub%20b4d5fc2db51a4ce49ec68cff09e3eb0d/Untitled%205.png)

================================================================================================================================================================================================

---

What is GIThub? 

Github is a website where we host all of our repositories.

Github is nothing but a web based  modern interface , for using Git with Graphical and user friendly interface.

Github is the most famous implementation of Git ,as the source code of Git was taken and many modern features were added to it , to make the GITHUB we use today!

Github alternatives : bitbucket , gitlab ...etc

![Git%20and%20its%20Hub%20b4d5fc2db51a4ce49ec68cff09e3eb0d/Untitled%206.png](Git%20and%20its%20Hub%20b4d5fc2db51a4ce49ec68cff09e3eb0d/Untitled%206.png)

FORKING: 

Forking a project is just like taking a copy of project , making some changes as required and again re uploading it 

Github has 2 types of profiles : Public and Private 

1. Public : if you want to share your code with everyone on the community. ex: DiY project.
2. Private : aka Enterprise , when you want your personal repository , or just want code to share with specific people . ex: Software company.

REPOSITORY: Repository is a folder place where the project is stored.

A repository is usually used to organize a single project. Repositories can contain folders and files, images, videos, spreadsheets, and data sets – anything your project needs. We recommend including a README, or a file with information about your project. GitHub makes it easy to add one at the same time you create your new repository. It also offers other common options such as a license file.

In github , by default the name of the repository is "master"

→ There is a master repository of any software or project , Administrator makes a developement branch from master to make changes and improve code. Now, Any developer in the team can make a sub branch of the Development branch repository and make changes to it(on his personal system) ,and once he finishes his task , he applies for a pull request (PR).

And when the administrator accepts and approves the code from Developers (multiple)  , it is called Build.

Build becomes Merge when the build is successfully brought on live repository of the project.

![Git%20and%20its%20Hub%20b4d5fc2db51a4ce49ec68cff09e3eb0d/Untitled%207.png](Git%20and%20its%20Hub%20b4d5fc2db51a4ce49ec68cff09e3eb0d/Untitled%207.png)

![Git%20and%20its%20Hub%20b4d5fc2db51a4ce49ec68cff09e3eb0d/Untitled%208.png](Git%20and%20its%20Hub%20b4d5fc2db51a4ce49ec68cff09e3eb0d/Untitled%208.png)

Markdown File : Readme.md
readme the most basic file that you will find in almost every project that contains text to describe what the project is about, what it does and any other relevant information

## Reading Diffs

In version control, differences between two versions are presented in what's called a "diff" (or, synonymously, a "patch"). Let's take a detailed look at such a diff - and learn how to read it.

![https://www.git-tower.com/learn/git/ebook/en/command-line/advanced-topics/diffs/example-diff.jpg](https://www.git-tower.com/learn/git/ebook/en/command-line/advanced-topics/diffs/example-diff.jpg)

### Compared Files a/b

Our diff compares two items with each other: item A and item B. In most cases, A and B will be the same file, but in different versions. Although not used very often, a diff could also compare two completely unrelated files with each other to show how they differ.To make clear what is actually compared, a diff output always starts by declaring which files are represented by "A" and "B".

[https://www.git-tower.com/learn/git/ebook/en/command-line/advanced-topics/diffs/](https://www.git-tower.com/learn/git/ebook/en/command-line/advanced-topics/diffs/)
