# Jenkins Installation 

```
yum update -y

amazon-linux-extras install java-openjdk11 -y

yum install jenkins -y

wget -O /etc/yum.repos.d/jenkins.repo     https://pkg.jenkins.io/redhat-stable/jenkins.repo

rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io.key

yum upgrade

yum install jenkins -y

systemctl start jenkins

systemctl status jenkins

cat /var/lib/jenkins/secrets/initialAdminPassword

```

## References:
- https://www.jenkins.io/doc/tutorials/tutorial-for-installing-jenkins-on-AWS/
