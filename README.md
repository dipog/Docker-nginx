# Install Docker
Inrerswitch DevOps Challenge

**my steps taken.
============================

1. cat /etc/centos-release (check version on centos)
2. Add docker to repository
   sudo touch /etc/yum.repos.d/docker.repo
3. change directory
	cd /etc/yum.repos.d/
4. check list 
	ls
5. Edit docker repo
	vi docker.repo

click i on keyboard to type:

[dockerrepo]
name=Docker Repository
baseurl=https://yum.dockerproject.org/repo/main/centos/$releasever/
enabled=1
gpgcheck=1
gpgkey=https://yum.dockerproject.org/gpg

6. Install docker
	sudo yum install docker-engine

7. check docker version
	docker -v
