1.	List three major version control software for software engineering.
Git
Mercurial
Concurrent Versions System

2.	What are the main advantages to using Git in your software development, and how is it useful for game developers.
Git uses a distributed version control which enhances collaborative work and includes conflict resolution in merges and pushes.

3.	Define the following terms in relation to Git. Branch, Pull, Push, repository, working copy, merge

Branch
A concurrent version of the main portion of the project that allows developers to make changes to the project (or code base) safely.

Pull
Obtaining data from repository

Push
Uploading data/edits/changes to the repository

Repository
A git “folder” within a project. Used to track hold data/files and track changes. Keeps a history of changes

Working Copy
A clone of a repository where data can be viewed and edited, then (merged, committed) pushes to the repository

Merge
Combining changes in one branch (ex. files, code, data, etc) to another branch. 

4.	If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git.
•	Information Technology Policy
•	Data Storage Policy
•	Privacy Policy
•	Git Procedural Manual
•	Documentation Procedural Manual
•	Naming Conventions

5.	Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts.





6.	In a merged source code file, how does Git let you know there is a conflict?
(There is a marker in the file. What is it?)
 ++<<<<<<< (source1)
+ change 1 in source 1
+ change 2 in source 1
++======= (source 2)
+ change 1 in source 2
++>>>>>>> (end of differences)

Please refer to word document to view image of an example

7.	What are the steps you can take to resolve Git conflicts?
You can view the conflicting changes in (a CMD window or a text file or) GitHub Desktop and choose which changes you want to keep or discard.

Please refer to word document to view some helpful commands to resolve conflicts

8.	What does git revert do, and how can you use it?
This undoes changes while keeping records of the changes being “discarded”.


9.	What does git reset do, and how can you use it? 
This removes commits to the user specified commit and discards all changes made after the specified commit.


10.	What is the difference between git revert and git reset?
Git Revert removes requested changes and keeps records of the discarded changes.
Git Reset removes requested changes and completely discards the unwanted changes.


11.	True or False: It is okay to commit broken code to the main branch.
Initially, false. While it is possible to push broken code to the main branch, best practices dictate that code should be fixed, tested and confirmed to be working before pushing. However, it is acceptable to push broken code for the purpose of getting another developer to fix it. (ex. an inexperienced developer asking for help, or for the purpose of testing a learner developer)


12.	True or False: You should commit related changes. For example, fixing two different bugs should produce two separate commits.
True. It is best to commit related changes together and unrelated changed separately. This aids in tracking and ease of reading changes as well as transparency.


13.	Describe what is DevOps, how is it useful for game developers?
DevOps (Development Operations) is a practice that advocate and encourages simultaneous collaboration between development and operation teams. This practice is particularly useful to organisations as it facilitates a collaborative environment between the production teams. The transparency in process and communication reduces misunderstandings, redundancies and downtime. When the developmental and operational teams work together towards a single goal, efficiency is maximised through clear communications.

14.	List what tools can be used with DevOps. Give a brief description of each one. (at least 3)
Git
Splunk
StrongDM

Please refer to word document to see a description of the tools listed above.


15.	What is CI/CD and how can it be used to automate the game development process?
Critical principles of DevOps include Continuous Integration and Continuous Development. I’m not sure who they can automate processes, but rather are dependent on certain repetitive processes being automated so that developers can focus on the development side (ex. instead of testing and analysing bugs). While integration can be automated, continuous integration may not allow for testing and debugging prior to deployment.
Moreover, I cant see the correlation between Continuous Integration/Continuous Development and the creation of automation without further development of AI technology and the automation  of continuity of integration and development.
