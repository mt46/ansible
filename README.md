# Ansible Playbooks
Playbook are tested at following environment

CentOS 7  
Ansible 2.8.2  

**AWS Playbooks**  


|Playbook  |Description |Reference  |
|---------|---------|---------|
|AWS/aws-linux-system-update.yml</br>     |Yum update all and reboot the system if required | [luktom.net](https://luktom.net/en/e1497-how-to-update-centos-rhel-using-ansible)  [Ansible Doc](https://docs.ansible.com/ansible/latest/modules/reboot_module.html)   | 
|AWS/aws-linux-system-update-security.yml   |    Yum update security packages and reboot the system if required|[luktom.net](https://luktom.net/en/e1497-how-to-update-centos-rhel-using-ansible)  [Ansible Doc](https://docs.ansible.com/ansible/latest/modules/reboot_module.html)|
|AWS/aws-linux-system-update-check.yml   |    Check if system is required to apply security updates |[luktom.net](https://luktom.net/en/e1497-how-to-update-centos-rhel-using-ansible)  [stackoverflow](https://stackoverflow.com/questions/34188167/ansible-print-message-debug-msg-line1-n-var2-n-line3-with-var3)|