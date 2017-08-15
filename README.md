# ansible-fedora


- Requires Ansible 2.2 or newer
- Expects Fedora 25 hosts

The inventory file 'hosts' defines the nodes in which the stacks should be configured.

        [fedora-devel]
        fedora-devel ansible_host=192.168.1.60

The stack can be deployed using the following command:

        ansible-playbook -i hosts site.yml
