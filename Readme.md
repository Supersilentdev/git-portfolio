# Bootcamp exercise Day 1
* Create a public git repo on github and add a readme.md file in that repo.
* Clone that repo repo on local machine using VS code terminal/git bash using ssh/https link of that repo.
     * Fix access denied error by adding your own ssh.
        * ssh-keygen -t ed25519 -C "your_email@example.com"
        * Now add your generated public Key to your github account.
* Use "ls -la" to check for all file inside the repo including .git folder which is hidden and save all incrimental changes in you repo.       
* Edit Readme file and save changes.
* check git repo for any changes with "git status" command.  
* Now creat new index.html file locally and run "git status" and check for Untracked files that are not part of git.
* To add all Untracked and modified files to git use command "git add ." or "git add index.html" for just single file.
* Save you commit to git locally used " git commit -m "Added index.html" -m "added index fime and made changes to redme file" " where first -m is mandatory comment and second -m is optional.
* Use "git push origin master" to upload you change to project destination/github online repo.
* To set remote upstrime as default use command "git commit -u origin master" and use "git push" from next time.
* change git repo in terminal "git origin set-url origin your_repo_url"
* check for repo branches "git branch"
* create new branch in the repo "git checkout -b Your_new_branch_name"
* Switch between branches with <code> git checkout Your_branch_name </code> use branch inistials with tab to suggition.
* make changes to readme and push it to newly created branch.
* use git checkout commant to switch between branches.
* use <code> git diff Your_destinagtion_branch_name </code> to see the difference between of both branch
* use <code> git merge Your_destination_branch_name</code> to merge into files and changes in the destination branch in this case master branch. (this is not common practic method use pull request method)
* 

