# ansible
Ansible scripts

1. Add a host (example1) to inventory file "hosts"
1. Run ansible as below

ansible-playbook -i hosts login.yml 


To run NTP configuration:
Run ansible as below

ansible-playbook -i hosts  ntp_config.yml 

TO Run Server configuration
Run the as below

ansible-playbook -i hosts server_configure.yml --skip-tags "ssh"

