# GitHub Collaboration

Before beginning this lab, make sure you fully understand the basics of how to use a terminal, an IDE, Git, GitHub and how to handle merge conflicts - basic commands won’t be focused on in this lab.

In this lab you will:
* Practice using basic terminal and git commands
* Learn how to use GitHub to collaborate as a team
* Learn about pull requests and merging new branches to a master timeline

The real power of GitHub is the ability to collaborate on code with a team of developers.  For this lab, pick a team of 2. Identify one person as the “Team Lead” who will authorize the GitHub merges.  No one else on the team should merge pull requests, or you will undoubtedly end up with merge conflicts. (There are ways to resolve these, but lets get the general process of collaboration under our belt, before we deal with conflicts.)  To begin with we will take complexity of code out of the equation, and just work with a text file.  We are going to pretend we are working in an HR department, and we want to as a team come up with this year’s interview questions for our seasonal staff.

<iframe width="560" height="315" src="www.youtube.com/embed/w3jLJU7DT5E" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# Task One - Team Leader (Other Team Members Should Observe)

Create a repo in GitHub, and call it InterviewQ, and note it’s url (To add remote later).
In a local IDE, mkdir InterviewQ 
In this directory, create a text file called interviewQ.txt
Add a title ‘Interview Questions - 2021’
Add one question ‘Tell us about yourself’
Use Git init to create a local git repository.  Connect the local repo to the one on GitHub you created in step 1 with git remote add.  Use git add to stage the new text file, and git commit the file with -m ‘first question added’. Push the file to the repo on GitHub
Go to the repo on github and check that your file uploaded properly. 
Go to the settings page, and add collaborators (Your other team members).

# Task Two - Team Member

You should receive an email inviting you to the GitHub Repo.  Accept the invitation, and navigate to the repo.  Copy the repo url.
In a local IDE, mkdir InterviewQ.  Create a local git repository in this directory.  Use git add remote to connect the local git repository to the GitHub Repo.
Use git pull to pull down the interviewQ.txt file into your local repository. 

***GitPull should be done every time you begin working so that any changes done by your team are pulled down.  You don’t want to be working on an old version, or create merge conflicts***

Add a branch to your local repository called yourNameWork.
Add a question to the interviewQ.txt file
Use git add to stage the modified file, git commit to commit the change, and git push the new branch to the GitHub repository.

# Task Three - Team Leader (Others Should Observe)

 The GitHub Repo should now have a pull request. You can decide if you want to comment on the changes, and ask your team member to make modifications, or you can decide that you like the changes and merge them into the master branch.
Once you merge the changes into the master branch, it is good practice to delete the branch you no longer need.
Make sure your team members pull all changes to their local branch.
Team members should not make changes to the same file on the same branch at the same time.  Git won’t know which version to keep, you will get a merge conflict.
