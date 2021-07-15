# git-command
Git command : all userful command

______+++++++++++++++++++++++++++++++++++++++++++_______________________________


History

Amit

Kumar
#################################################################################################
 <
 # 1.git clone branch :  git clone -b develop https://bitbucket.sdlc.tota.com
 # 2.git clone : git clone https://bitbucket.sdlc.tota.com ( default master branch )
# 3.Configure the author details : git config --global user.name,user.email..
# 4.initialize a new local repository : 	git init
# 5.create an copy of local repository : git clone /path/to/repository
# 6.create an copy of remote repository: git clone username@host:/path/to/repository
# 7.add files : git add
# 8.commit changes but not on remote repository : git commit -m
# 9.commit changes all Over: git commit -a
# 10.list the files which have been changed : git status
# 11.list all currently configured remote repository : git remote -v
# 12.create a new branch from the origin and change to it : git checkout -b <branchname>
# 13.switch to the branch which mentioned in the braces.: git checkout <branchname>
# 14.list all the branch in the repository : git branch
# 15.delete the branch with is mentioned in the braces : git branch -d <branchname>
# 16.push the mentioned branch in the remote repository : git push origin <branchname>
# 17.push all the branches to the remote repository. : git push --all origin
# 18.merge the mentioned branch in currently using branch : git merge <branchname>
# 19.view all the merge conflicts : git diff
# 20.view changes in base file : git diff --base <filename>
#  21. delete remote branch : git push origin --delete master 
 
------------------------------------------------------------------------------------------------------------------------

# Example: iPlus ISP war migration from source repo develop branch
# git clone --single-branch -b develop https://bitbucket.sdlc.tota.com/scm/ius/iplus_abp2.git
# git filter-branch --subdirectory-filter sims-core HEAD
# git remote remove origin
# git remote add origin  https://bitbucket.sdlc.tota.com/scm/ius/iplus_abp2.git
# git push -u origin develop:develop


git push -f origin feature/scrum_dev_2004:develop

git filter-branch --subdirectory-filter sims-warrr HEAD

git filter-branch --subdirectory-filter sims-prosing HEAD

git clone --single-branch -b feature/scrum_dev_2003  https://bitbucket.sdlc.tota.com/scm/ius/iplus_abp2.git

git commit -m "[IPLU-1459] upgraded with april release" -a

git commit -m "[IPLU-1023] iplus common updated from develop branch" DealReviewRuleHistoryDTO.java

git commit -m "[IPLU-1038] moved from iplus-isp-sync"  LiveSyncErrorHandlingRepository.java
 
git commit -m "[IPLU-1022] commented code for iplusi-isp-synch dismissed module" incentives-application.xml

git filter-branch --subdirectory-filter sims-cache-integration HEAD

git filter-branch --subdirectory-filter sims-processing HEAD

git clone --single-branch -b feature/scrum_dev_2004 https://bitbucket.sdlc.tota.com/scm/ius/iplus_abp2.git
