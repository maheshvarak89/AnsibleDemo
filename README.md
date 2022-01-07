# AnsibleDemo
This repo contains sample code to integrate Ansible to deploy EC2 via AWS CloudFormation<br />
**files/server.yml** is AWS cloudformation file<br />
**inventory/env.yml** provide parameters to Ansible playbook<br />
**play_books/deploy_server.yml** is Ansible playbook file which deploys AWS CFT<br />
**hosts** contains host server<br />

# To start playbook use following command
> ansible-playbook -i hosts playbooks/deploy_server.yml <br />
NOTE: make sure the value of 'hosting' variable is appropriate (Create/Delete)
