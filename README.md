# Nginx
ec2-user@ip-172-31-41-235 ~]$ sudo yum update

[ec2-user@ip-172-31-41-235 ~]$ sudo amazon-linux-extras install nginx1

[ec2-user@ip-172-31-41-235 ~]$ sudo systemctl start nginx

[ec2-user@ip-172-31-41-235 ~]$ sudo systemctl status nginx

  Active: active (running) since Sun 2022-07-24 21:07:21 UTC; 7s ago
  
[ec2-user@ip-172-31-41-235 ~]$ curl localhost:80

[root@ip-172-31-42-248 ec2-user]# mkdir folder

[root@ip-172-31-42-248 ec2-user]# cd folder

[root@ip-172-31-42-248 folder]# touch Nginxfile.txt

[root@ip-172-31-42-248 folder]# yum install git

[root@ip-172-31-42-248 folder]# ls
Nginxfile.txt
[root@ip-172-31-42-248 folder]# nano Nginxfile.txt

[root@ip-172-31-42-248 folder]# cat Nginxfile.txt
Nginx server is running

[root@ip-172-31-42-248 folder]# git init
Initialized empty Git repository in /home/ec2-user/folder/.git/

[root@ip-172-31-42-248 folder]# git add Nginxfile.txt

[root@ip-172-31-42-248 folder]# git remote add origin

[root@ip-172-31-42-248 folder]# git clone https://github.com/sudeepi/Nginx.git

[root@ip-172-31-42-248 folder]# git commit -m "local commit"

[root@ip-172-31-42-248 folder]# git add Nginxfile.txt

[root@ip-172-31-42-248 folder]# git add Nginx

[root@ip-172-31-42-248 folder]# git commit -m "local commit"

[root@ip-172-31-42-248 folder]# git push -u origin master

Username for 'https://github.com': sudeepi
Password for 'https://sudeepi@github.com':
