# Docker-nginx
Interswitch DevOps Challenge

Task 2 
Create web clusters with three docker containers with a bash script 
Environment 
Docker CE, CentOS 7, HAProxy 1.6, Nginx any version

Description:
Write a script, which will:
1. Create and run 2 Docker containers with nginx 
2. Create, run and install HAProxy in 1 container
4. Configured HAProxy to send traffic to working Nginx servers

Acceptance criteria:
Script creates three Docker images, run containers from them,
configures Nginx and HAProxy and checks Nginxs availability on both containers.
The HA proxy will be used as a load balancer between the nginx containers

