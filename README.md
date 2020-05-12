# BIOFAB_Production
A copy of the BIOFAB production protocols.

Git How To
A Short Guide for Protocol Development


This guide assumes basic knowledge of several git features such as:
Remote Repos
Branching
Merging Branches
Committing changes



For general information on Git and git commands please reference:

  https://rogerdudler.github.io/git-guide/

  Google!  Lots of good documentation on google

  Although not needed the Git desktop app provides a convenient GUI for easy use.



Advice on maintaining a good git workflow: 

  https://drewdevault.com/2019/02/25/Using-git-with-discipline.html
  
  
  
Super in-depth tutorial on Git Concepts (not necessary to use git, but full of great information): 
    https://dev.to/unseenwizzard/learn-git-concepts-not-commands-4gjc 


Benefits of Git
  Tracks changes seamlessly 
  Enables collaborative work
  Allows for code reviews and checks for conflicts


How git will work for us (for now until more tools are built):

 1. Task Is posted in Asana
 2. Developer “claims” task
 3. Navigate to your local repo and Pull Master (this ensures you are starting from the most recent head)
 4. Branch Master to a working branch (named appropriately)
 5. Name should reflect the task at hand and (in a word or two) describe what issues are being addressed.
 6. Work in the Working Branch from here on!! NEVER work in master.
 7. Make changes to appropriate files.
 8. Copy code to Nursery or LocalHost for testing
 9. This step could eventually be automated.  However for now just copy the entire file to the testing platform.
 10. Test code
 11. Loop to Step 5 until Code performs as expected and solves issue
 12. Add All and Commit to Working Branch
 13. Push Working Branch to remote
 14. Add all changes to Nursery 
 15. Contact Lab Managers for testing
 16. Loop to Step 5 until Lab Managers approve testing
 17. Create a Pull Request for code review before merging to master.
 18. Add comments about what you did and/or link to the original Asana task.
 19. Refer to code review list for code reviewers (to be created soon just a list of names)
 20. Choose the “next person” on the list unless you have a compelling reason to have a specific person review your code (e.g. they created the library you changed etc)
 21. Add that person as a reviewer to the request. Also add Amy as a reviewer.
 22. Once changes are reviewed, merge to master.
 23. Once merge is successful UPDATE PRODUCTION
 24. Copy and paste all changed files from the repo to Production
 25. Close issue on Asana


Note: Git will be the “official” version of all protocols in Production and steps should be taken to ensure that Production and the master branch match at all times.

Note: It is good practice to add and commit any time you have made a notable, distinct, complete change.  Even if this change does not solve the “issue” on a whole.  This helps to keep a detailed log of changes.  

Note: Ensure commit messages clearly describe changes made

Note: Each time a commit is made that commit should be pushed to remote (same branch).  This saves a backup of your work in case your computer disintegrates.


