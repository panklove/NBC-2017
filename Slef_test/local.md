[root@c03mt /]# cat /etc/yum.repos.d/local.repo
[centos]
name=centos
baseurl=http://10.10.10.254/centos/x86_64/7.2/
enable=1
gpgcheck=0

[gangpbs]
name=gangpbs
baseurl=http://10.10.10.254/centos/x86_64/7.2_extras/
enable=1
gpgcheck=0
[root@c03mt /]#
