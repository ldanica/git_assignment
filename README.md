# Git Assignment - ldanica

a. What is an issue?

On GitHub, issues are items you can create in a repository to plan, discuss, and track work. It can be used to track changes, for feedback and collaboration, and to communicate with other team members.

b. What is a pull request?

A pull request is asking to merge changes from one branch into another. They show the differences between the content in the source branch and the content in the target branch.

c. Describe the steps to open a pull request?
1. Clone the original repository into our local server using git clone command and the url link of the repo
2. Change your working directory to the repository you cloned
3. Create a new branch and switch your working directory to the new branch
4. Change your working directory to the new branch
5. Start making changes on your local server
6. Stage, commit, and then push your changes to the new branch
7. On GitHub, navigate to the original repository and click Compare & pull request
8. In the base branch menu, select the branch of the upstream repository you would like to merge your changes into
9. In the compare menu, select your branch that you made changes in
10. Type a title and description for your pull request
11. Complete pull request

d. Describe the steps to add a collaborator to a repository (share write permissions)
1. On GitHub, go to repository you want to give access to and click on settings
2. Click on collaborators
3. Search by username, full name, or email and add collaborator

e. What is the difference between git and GitHub?

Git is a version control software that tracks changes in files. It's particularly useful for when you are collaborating with many people who are making changes to the same files simultaneously.

GitHub is a cloud-based platform that's built upon Git. It allows you to store, share, and collaborate to write code.

f. What does git diff do?

If we made changes in our working directory and didn't run git add, git diff compares what changes were made in our local directory to what is in our staging area. 

g. What is the main branch?

When you create a new repository on GitHub, it does so with a single/default branch. This default branch is called the main branch.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

If you are working alone and testing things out, you could push your changes directly to the main branch. However, it's best practice to create separate branches for testing as the main branch should act as a working final version. Once you made your changes on your branch, make a pull request. If any issues arise after merging, it's much easier to revert a pull request than to comb through the main branch and undo each commit.