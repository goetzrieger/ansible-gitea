# ansible-gitea

Playbook and role (from here: https://github.com/roles-ansible/ansible_role_gitea) to install a Gitea instance (mainly) on a Red Hat RHPDS (for employees & partners) Ansible lab environment in parallel to code-server.

The needed vars are defined in group_vars/all, adapt as needed.

Adapt the URL pattern in the inventory file (the lab id and the number of instances).

Run with:

`ansible-playbook -i inventory install-gitea.yml --ask-pass`
