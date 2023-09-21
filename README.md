### Question:

How would you allocate the task of fixing the critical bug to a team member using Git and the issue tracking system?

Tasks given

Task1: Describe the process of creating a new issue or bug report in the issue tracking system.
Task 2: Explain how to assign the issue to a specific team member.
Task 3: Describe how to use Git branches and pull requests to work on the issue, ensuring that changes are tracked and reviewed.
###


### first i created one repository on git hub  ###

repo name: assesment-sep20

cloned into my local ubuntu server 

$git clone (https://github.com/manikantaraju427/assesment-sep20.git) #http code from my repository

#create a file example.txt    with vi editor  

git add example.txt

git commit -m " commiting"

git push origin main

my file pushed into git hub 

### Task1: Describe the process of creating a new issue or bug report in the issue tracking system. ###

-> Log In to the Issue Tracking System
-> Navigate to the project repository where you want to create the issue.

###  Create a New Issue ###

 Click on the "New Issue" button to start creating a new issue.

filled all the details

Click the "Submit new issue" button to create the issue.

### tep 2: Assign the Issue ###

in the right sidebar, under the "Assignees" section, click on the "Assign yourself" button to assign the issue to myself ( in this case iam only contributor that why i selected my self )

### Task 3: Using Git Branches and Pull Requests ###

Create a New Git Branch

$issue-1 

$git checkout issue-1

modify the code in the file

$git add .

$git commit -m "Fix issue #1: Describe the changes made."

$git push origin issue-1

### Create a Pull Request (PR) ###

GitHub repository,

go to the "Pull Requests" tab.

Click on the "New Pull Request" button.

### Assign reviewers for the team ###

in this is case iam the reviwer 

reviewed 
approved code

merge the pull request into the main branch

the code is merged into branch to main 




