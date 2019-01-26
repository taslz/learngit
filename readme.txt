Git is a distributed  version control system
Git is free software distributed under the GPL
Git clone git@github.com:taslz/learngit.git 
Git clone the first is make the count .
#git config --global user.name "Your Name"
#git config --global user.email "email@example.com"
and next is make the key 
#ssh-keygen -t rsa -C "youremail@example.com"
and next is setting (change) the remote key
the last is clone the dir
be sure in the correct dir 


push the modify to the remote
git sometime there are some misktakes such as:

ERROR: Repository not found.
fatal: Could not read from remote repository.
 
Please make sure you have the correct access rights
and the repository exists.

the solut is :
#git remote set-url origin git@github.com:xxxxxx/xxxxxx.git

and the last to push the remote 
#git push -u origin master