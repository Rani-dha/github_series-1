#### Git and GitHub Series: Task-1

**1. What do you mean by Git and GitHub?**
  
* Git is free and open source Distributed Version Control System (DVCS), i.e) It's a tool that help all the techies to do team development perfectly and smoothly. It runs in command line interface.
 GITHUB:
* GitHub is also a free and open source platform. It provides a web - based graphical interface. Mainly it provides Access Control and Collabration features for every programmers.

**2. Why GitHub is so popular and used in most of the projects?**

* It's support all the popular programming languages and streamlines the iteration process.
* Hosts various source code projects of all techies.
* Easy Version Control
* Secure cloud storage
* Free open source
   
**3. What is version control system ? How Git is a VCS?**

* A Version Control System records the changes that we make to all project files. It provides clarity when reviewing software by describing When, What, Why it was changed!
* It keeps tracking changes of source code in software development of all programmers and developers. Hence Git is known as VCS.

**4. What are the other platforms similar to Github?**
* GitKraken
* Gitlab
* BitBucket
* Source Forge
* AWS CodeCommit
* Beanstalk
* Gitea
* Apache Allura

**5. Why are you interested in learning of Git and Github?
   Interests that make me to learn it:**
* To begin my projects and open source contribution.
* Whenever I open a LinkedIn, every senior programmers and developers includes the Github 
Repository Link in most of their posts, which makes me more curious to learn about it!


#### Git and GitHub Series: Task-2

**Link to the GitHub repository.
    https://github.com/Rani-dha/Github_series  
Link to the GitHub Readme.md
    https://github.com/Rani-dha/Github_series/blob/master/README.md**

**1. How git workflow works?**
* It premits every Programmer and Developer to clones the repositor, works locally on the codes,makes a commit with changes, and push it to the central repository for others to pull and continue their work.
* There are three stages:
  * Committed: It is stored in Local repository with all the  changes.
  * Modified  : It contains changes to the files but none of the changes are being saved to the local repository.
  * Staged : Files is in index(stage) i.e) It is tagged to be considered  in the next commit.

**2.What're the different stages of a git project as commit, add?**
* Initializing Git - git init
* Adding files to share - git add filename
* Saving the added files - git commit -m "The short message"
* Adding a remote Repository - git remote add nickname link_of_Githubrepo
* Uploading files - git push nickname master 

**3. Is it possible to do a git commit before git add. if you have made any changes? Explain why?**
* No, it is not possible. we can't commit without a git add because we should add the different versions and then commit it to view the changes.

**4. Why is git diff used?**
* It is used to find the difference between the versions.

**5. Can we leave the commit messages as blank?**
* Yes, we can leave the messages as blank. By using, git commit -a --allow-empty-message-m'' 
* A Good practice is to commit messages for better understanding.
 
#### Git and GitHub series : Task -3

**Link for Pull Requests:**

**https://github.com/codewayy/github_series/pull/182  
https://github.com/Rani-dha/Github_series/pull/1**  

**a) What is meant by the term fork and clone?**
* Fork - Allows us to create a copy of the original repository and stores in our GitHub .
* Clone - After forking, Cloning is used to make a copy from the GitHub to our local repository i.e) Git. Allowing us to make changes.

**b) What are the branches in GitHub?**
* Branch - It is used when working in projects as teams. A Repository can have one or more branches. The Default Branch is master. It is used for separating  some parts of code from the master branch. After the changes are made, we can also able to merge the new branch with master branch.
 

**c) What is PR?**
* PR stands for "Pull Request" in GitHub repository. It lets us tell others about the changes that we have pushed to an original repository from which we have forked, cloned earlier. Requesting and Explaining the owner of the repository about the changes that we made.

**d) Can we delete the master branch if not, Why?**
* Master branch is  the default branch. Yes, we can delete a master branch before that we should make any other branch as default branch. 

**e) How can we delete a branch?**
* git branch -d <branchtodelete>
     Above command is used to delete a branch. 
   * -d option will delete the branch only if it has already pushed and merged with the remote branch.
   * -D option is used to force the branch to be deleted, even if it hasn't been pushed or merged yet.
