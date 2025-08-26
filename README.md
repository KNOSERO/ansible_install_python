# Ansible Install Python
Script for installing python in Ansible

## Example

```yaml
- name: Install Python
  hosts: localhost
  become: true
  vars:
    python_version: "3.11" 

  tasks:
    - name: Install Python
      include_tasks: ./task/ansible_install_python/playbook.yml 
```