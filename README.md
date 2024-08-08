# nginx

## what is Nginx
NGINX is a `web server` that can also serve as a load balancer, reverse proxy, and http cache. The non-blocking, event-driven architecture of NGINX makes it high performance, stability, and low resource usage., and it is frequently deployed in Kubernetes stacks.


## Installing Nginx on EC2 Instance
https://medium.com/@mertcal/install-nginx-on-ec2-instance-in-30-seconds-e714d427b01b
|steps|command|
|:---:|:---:|
Install | `sudo yum install nginx`
To configure its worker_processes according to our needs | `sudo vi /etc/nginx/nginx.conf` set is auto is good
check version | nginx -v
start Nginx | sudo systemctl start nginx