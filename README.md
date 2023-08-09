# ansible_pssid_gui_2.0
Ansible playbook to install pSSID GUI 2.0

pSSID GUI [LINK](https://github.com/UMNET-perfSONAR/pssid-gui2)

### Install on a virtual machine
Run the following code via terminal in the same directory as the playbook.yml file

#### TODO:
* Specify virtual machine target in inventory/hosts.ini
* Specify dest on target machine when cloning github repository, then use that same directory as project_src in docker compose build and docker compose up commands.

```
ansible-playbook   --inventory inventory   --become   --become-method sudo   --become-user root   --ask-become-pass   --ask-pass   playbook.yml
```
