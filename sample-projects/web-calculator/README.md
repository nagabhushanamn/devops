


# Install java

	sudo yum install java-1.8.0-openjdk.x86_64
    java -version
    sudo update-alternatives --config java

# Install Jenkins

	sudo wget -O /etc/yum.repos.d/jenkins.repo http://pkg.jenkins-ci.org/redhat/jenkins.repo
	sudo rpm --import https://jenkins-ci.org/redhat/jenkins-ci.org.key
	sudo yum install jenkins
	
	sudo service jenkins start/stop/restart
	sudo chkconfig jenkins on
	




	
	  
	  







