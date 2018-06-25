# Packer-Ansible-Jenkins
Deployment of Jenkins behind Nginx to AWS using Packer and Ansible

### Instruction
* Install packer by following the installation instructions from https://www.packer.io/docs/install/index.html
* Install Ansible on your local machine as a master ansible server by following the instructions from https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html
* Clone the github repo at https://github.com/anyric/Packer-Ansible-Jenkins.git ```git clone https://github.com/anyric/Packer-Ansible-Jenkins.git```
* cd in to the project folder
* export your aws_access_key and aws_secret_key as evironment variables
* Run ```packer build template.json``` to build the image
* Navigate to your AWS account to create an instance of the image from My AMI
* Once your are done with creating the instance and is running, you can access the app from the public DNS or IP address provided