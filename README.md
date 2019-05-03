# linux-order-user
centos7增加和删除用户

1> 删除用户以及用户目录：

    [root@localhost ~]#userdel -r usename
    
2> 添加加用户 test：

    [root@localhost ~]#groupadd groupname
    
3>  添加加用户 test：

    [root@localhost ~]#adduser -g usename groupname
    
4> 修改test密码：

    [root@localhost ~]#passwd usename
       
5> 删除用户

    [root@localhost opt]#userdel -r usename

6> 删除邮箱

    [root@localhost home]# cd /var/spool/mail/
    [root@localhost mail]# rm -rf usename
