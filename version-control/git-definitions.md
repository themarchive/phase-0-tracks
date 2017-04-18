# Git Definitions

**Instructions: ** Define each of the following Git concepts.

* What is version control?  Why is it useful?
Version control is keeping 'save states' of changes to a software project, and being able to revert back to a previous state or, merge a different state into the master state. It allows many different people to work on the same project and with the same codebase, protects code that works from being damaged when new features are tested or experiments in the code are attempted.
* What is a branch and why would you use one?
A branch starts with the same code and history of the original directory, but has its own path forward, that is, changes you make on a branch don't automatically do anything to the master code. You would use one to try out a new feature, or test an idea to re-do an existing part of the code. You can work on the project and experiment without worrying about messing up the original code. 
* What is a commit? What makes a good commit message?
A commit is a save state, it saves a certain number of modifications in files to a branch. A good commit message is clear, short and tells a reader exactly what change to the code you're saving.
* What is a merge conflict?
A merge conflict is when an attempt is made to merge two branches, but the same line of code has gone in two different directions. For example, if a 'test' branch is created, and different modifications are made to the same part of the code in both 'test' and 'master' and committed, when a merge is attempted there will be a merge conflict. The user has to specify what the 'correct' version of the code will be going forward or the branches cannot be merged.