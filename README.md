# ansible-practice
Testing out Ansible playbooks, inventory, and roles on VMs in my home lab.

Practice Notes: 
  Edit `/etc/ansible/ansible.cfg` to contain the following:
  `interpreter_python = auto_legacy_silent`
  `host_key_checking = False`
This will squelch Python interpreter warnings and SSH host key checks which are not needed when running in a lab environment.