# nginx

## what is Nginx
NGINX is a `web server` that can also serve as a reverse proxy, content cache(http cache), load balancer, API gateway, and more. The non-blocking, event-driven architecture of NGINX makes it high performance, stability, and low resource usage., and it is frequently deployed in Kubernetes stacks.

## Installing Nginx on EC2 Instance
https://medium.com/@mertcal/install-nginx-on-ec2-instance-in-30-seconds-e714d427b01b
|steps|command|
|:---:|:---:|
Install | `sudo yum install nginx`
To configure its worker_processes according to our needs | `sudo vi /etc/nginx/nginx.conf` set is auto is good
check version | nginx -v
start Nginx | sudo systemctl start nginx

## Using a Network Load Balancer with the NGINX Ingress Controller on Amazon EKS
https://aws.amazon.com/blogs/opensource/network-load-balancer-nginx-ingress-controller-eks/

## Server names
https://nginx.org/en/docs/http/server_names.html

## Module ngx_http_core_module
https://nginx.org/en/docs/http/ngx_http_core_module.html#var_server_addr