# terraform-http-server

A simple HTTP Webserver hosted on AWS. It runs in a load balanced environment behind the Firewalls of AWS.

### Files
variables.tf
http_server.tf
loadbalancer.tf

### Steps
1. terraform init
2. terraform plan -out=tfplan
3. terraform apply tfplan
