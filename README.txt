#1) pip install sophosfirewall-python
#2) pip install --default-timeout=100 ansible  --trusted-host pypi.org --trusted-host files.pythonhosted.org
#3) ansible-galaxy collection install sophos.sophos_firewall


Run 
ansible-playbook -i inventory.yml master_playbook.yml -vvvv

Updgrade:
ansible-galaxy collection install sophos.sophos_firewall --force --ignore-certs
