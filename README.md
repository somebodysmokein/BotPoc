# Ansible Role: MySQL

Installs and configures MySQL server on RHEL/CentOS or Debian/Ubuntu servers.

## Requirements

No special requirements; Install Ansible in a linux machine

Clone the project to the linux machine

## Run the below command

ansible-playbook dynamic_workstation_builder.yml -i localhost --extra-vars "{\"ansible_winrm_server_cert_validation\":\"ignore\",\"ansiblewinrm_timeout_sec\":1200,\"ansible_authorization_type\":\"kerberos\",\"use_ticket_plugin\":true,\"install_username\":\"venky\",\"project_namespace\":\"4107\",\"installTool\":\"Mysql\",\"installApplication\":\"Mysql\",\"operatingSystem\":\"Linux\",\"existingMachine\":\"mymachine\",\"lan_id\":\"xxxx\",\"hpsm_id\":1234}" -vvvvvvv


## Author Information

This role was created in 2018 by [Venkatesh Raghunathan] [BotPOC for Dynamic Workstation Builder](https://www.ansiblefordevops.com/).
