## Integrating Ansible from terraform:
--------------------------------------
* Create two instances and install ansible and terraform in one node.
* Configure node with ansible control node and add the node to Jenkins with necessary configuration required.
* Write the terraform files and Jenkinsfile to integrate ansible from terraform.
[Refre Here](https://github.com/tarunkumarpendem/Documentations/blob/main/Terraform-Ansible-Integration/main.tf) for `main.tf` file
[Refer Here](https://github.com/tarunkumarpendem/Documentations/blob/main/Terraform-Ansible-Integration/inputs.tf) for `inputs.tf` file
[Refer Here](https://github.com/tarunkumarpendem/Documentations/blob/main/Terraform-Ansible-Integration/provider.tf) for `provider.tf` file
[Refer Here](https://github.com/tarunkumarpendem/Documentations/blob/main/Terraform-Ansible-Integration/dev.tfvars) for variables declared file `dev.tfvars`.
[Refre Here](https://github.com/tarunkumarpendem/Documentations/blob/main/Terraform-Ansible-Integration/Jenkinsfile) for the Jenkinsfile which can call ansible from terraform template.
* Build the pipeline using Jenkinsfile
![Preview](./Images/terraform1.png)
* verfiy in the browser wheather the application is in running condition or not using the public-ip of the node. 
![Preview](./Images/terraform2.png)

