# project_linux_administrator
### project for utrains student


1. You just got your first job as linux administrator.
During your release activities, a deployment is failing, with the following error : 
/opt/deployment/uat/deploy.cfg: No such file or directory
So the developers code is trying to access the deploy.cfg file.
Check on the server, if the path that the developer has put in his code is correct (provide the correct path to the developers). 

2.  success.txt another file in this server. make a command to find this file. 

3.  what group does the success.txt file belongs to ?  

4.  what is the permission on success.txt file for others people on the system

5.  we want the file success.txt to be owned by the user u5bt , how can we do that?

6.  the user u5bt's full name is "John Mary" please modify their account to reflect this.

7.  change the permission on the file success.txt to reflect the access below :
    - owner: full permission
    - group: read and write
    - others: no permission what so ever

8.  change the password for the user u5bt to redhat

9. create a user sarah with no access to an interactive shell

10.  create a group called network

11. create a user called henry with network as subgroup

12. Herman is a new contractor in the team and is complaining that he can not login to this server. 
please investigate what can be the issue and solve it so he can login to the server

13. go ahead and force Herman to change his password on the next login

14. A deployment to this server is failing and apparently it is due to selinux been set to enforcing mode. 
you are tasked to disable it. Below are the steps to do that. go ahead and do it.
    vi /etc/selinux/config
    change
    SELINUX=enforcing
    to
    SELINUX=diable
    save and quit

15.  this server will be used as a webserver
please go ahead and configure apache on it
it should display below message on the browser
"I feel like I am sitting in the office working for real"

