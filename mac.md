## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
   Git is a program used in the terminal that allows you to keep version control
   through in my case GitHub. 
2. What is the difference between Git and GitHub?
   Git is used in the command line of the terminal. GitHub is where the information
   is stored. Git is kind of a go-between for local files and those stored remotely.
3. Why do we create a branch? 
   Branches are created to keep things separated and help to develop features without
   everything being all one big mess. For example if you are creating a blog and want
   to work on the layout of the area where someone writes the blog, you don't have to
   worry about how to find that specific feature. 
4. What is the purpose of a Pull Request?
   Purpose of a pull request is to compare two branches before merging them. 
5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
   If switching from FIRSTNAME-LASTNAME to main you would use the command
   git checkout main
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
   git fetch would be used for getting remote data
   git merge would be used to merge two branches together
   git pull wouldl be used to compare two branches but not merge them.
7. What is a merge conflict?
   A merge conflict is when there are files on both braches that have conflicting
   information on them. For example if you have a README.md in the main branch but
   also in another branch then you have to figure out which one has the correct
   information
8. How do you resolve a merge conflict?
   You would open the file that has the conflict and look for the conflict 
   markers. At that point you would remove the conflict markers, decide which of 
   the changes you want to make, or make a new change. Then add it to staging,
   commit and then push. The other way is to remove one of the files causing the 
   conflict.
