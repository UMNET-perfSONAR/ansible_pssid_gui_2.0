# ansible_pssid_gui_2.0
Ansible playbook to install pSSID GUI 2.0

pSSID GUI [LINK](https://github.com/UMNET-perfSONAR/pssid-gui2)

### Install on a virtual machine
Run the following code via terminal in the same directory as the playbook.yml file

Be sure to specify virtual machine in inventory/hosts.ini

```
ansible-playbook   --inventory inventory   --become   --become-method sudo   --become-user root   --ask-become-pass   --ask-pass   playbook.yml
```
