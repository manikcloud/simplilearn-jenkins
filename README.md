# Jenkins Installation 

-  yum update -y

-    2   amazon-linux-extras install java-openjdk11 -y

-    3  yum install jenkins -y

    4  wget -O /etc/yum.repos.d/jenkins.repo     https://pkg.jenkins.io/redhat-stable/jenkins.repo

    5  rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io.key

    6  yum upgrade

    7  yum install jenkins -y

    8  systemctl start jenkins

    9  systemctl status jenkins

   10  cat /var/lib/jenkins/secrets/initialAdminPassword

   11  history


simplilearn-jenkins
simplilearn-jenkins
