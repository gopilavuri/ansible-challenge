# ansible-challenge

File Descriptions

ansible.cfg: Configuration for Ansible.
site.yml: Main playbook to run.
inventory/aws_ec2.yml: Dynamic inventory configuration for AWS EC2 instances.
roles/common: Role for common setup tasks.
roles/webserver: Role for webserver setup tasks.
roles/webserver/templates/ssl.conf.j2: Template for SSL configuration.
roles/webserver/files/car_game.html: HTML file for the car game.
roles/webserver/files/snake_game.html: HTML file for the snake game.
collections/requirements.yml: Required Ansible Galaxy collections.
group_vars/all.yml: Group variables for all hosts.
host_vars/vm1.yml: Host-specific variables for VM1.
host_vars/vm2.yml: Host-specific variables for VM2.



-------------------------------------------------------------------------------------------------------------------------------------------------

you can use Docker to host the HTML files.

Example Docker Deployment
Create Dockerfiles for each HTML file.
Build and run Docker containers instead of EC2 instances.
You can extend the Ansible playbook to handle Docker deployments or use a tool like Kubernetes for a more cloud-native approach.
