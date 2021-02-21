 Version Control is How version control helps high performing development and DevOps teams prosper
*Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time. As development environments have accelerated, version control systems help software teams work faster and smarter. They are especially useful for DevOps teams since they help them to reduce development time and increase successful deployments.
 
*Local Version Control is  VCS is a system to track changes in file(s) by making a version snapshot changes of that particular file over time.For the example is, when we want to write a book, we will write a word by word, line by line, or we save it chapter by chapter, we should be able to track the changes of the file, if we save it when we have add the second chapter, we should be able to remove the second chapter, as automatically as we add the second chapter. If we want to know what have we done in the second chapter, we should be able to track what we have we done before it, or even track other chapter changes in file(s).

*Centralized Version Control is  centralized version control systems like Subversion (SVN), CVS, and Perforce, while others have jumped straight into the distributed version control worlds of Git and Mercurial. There are many other flavors of centralized and distributed version controls out there – each with there own advantages and disadvantages.

*In software development, distributed version control (also known as distributed revision control) is a form of version control in which the complete codebase, including its full history, is mirrored on every developer's computer. Compared to centralized version control, this enables automatic management branching and merging, speeds up most operations (except pushing and pulling), improves the ability to work offline, and does not rely on a single location for backups. Git, the world's most popular version control system, is a distributed version control system.
Distributed version control  software development author Joel Spolsky described distributed version control systems as "possibly the biggest advance in software development technology in the  ten years"

*what is Git is Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.
Git is easy to learn and has a tiny footprint with lightning fast performance. It outclasses SCM tools like Subversion, CVS, Perforce, and ClearCase with features like cheap local branching, convenient staging areas, and multiple workflows.

so now you have to start download by this steps
*Download Git
In order to use Git, your computer must have it available. If you already have Git on your computer, you should make sure you have the latest version.

Git can be installed in three ways:

Install as a package
Install via another installer
Download and compile the source code.

*than step for windows 
Git Website

You can download Git by visiting this link and following the posted directions:

http://git-scm.com/download/win
GitHub

Install Git as part of the GitHub for Windows install.
http://windows.github.com

*Workflow
Working Directory: The actual files reside here.
Index: The area used for staging
Head: Points to the most recent commit

*The Life Cycle of File Status
After you edit a file, Git flags it as modified because of changes made after the previous commit.
You stage the modified file.
Then, you commit staged changes.

*now you write some command like 
git status 
git add 
git commit -m 
git push origin

Remote Repositories
*Cloned Repositories
When you create a repository on GitHub, it exists as a remote repository. You can clone your repository to create a local copy on your computer and sync between the two locations.

*Seeing Your Remotes
By running the git remote command, you can view the short names, such as “origin,” of all specified remote handles.
By using git remote -v, you can view all the remote URLs next to their corresponding short names.
