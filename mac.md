## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is an open sourced distributed version control system that manages code. Git is used to track changes in source code which allows many developers to work together.
2. What is the difference between Git and GitHub?
Git is the version control system that manages and updates the source code history. Github is the cloud-based hosting service that developers use to manage repositories. 
3. Why do we create a branch? 
We create a branch off the main branch so that we can work and add on new code and test that it's working without disrupting the main product/code. Branching is essential when there are multiple developers working on a project because it allows for different updates to code without changing the main working code. 
4. What is the purpose of a Pull Request?
A pull request notifies team members that your code is ready. A pull request doesn't change the code in the main code yet, it allows everybody to look over the code and allow feedback. 
5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
The command to switch branches is 'git checkout' + the name of the branch. To switch to the main branch, it is 'git checkout master'.
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
Git fetch downloads files and code from github to your local repositories. It allows you to see everyone elses code. Git merge allows us to take different lines of code from different branches and integrate them into a single branch. This is essential because there are usually many developers working on a single project and this allows us to add different code from each developers code into one branch. Git pull updates our local repository with all the new code that was updated from Github.
7. What is a merge conflict?
A merge conflict is when different developers are working on the same content of code. Some examples would be developer #1 deleting a file, while developer #2 is modifying it. Or it could just be two developers working on the same lines of code in a file.
8. How do you resolve a merge conflict?
 Git will mark the files that are conflicted and then it is up to the developers to check over the code to find a resolution. 

