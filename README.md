# Ansible tutorial

https://usecanvas.com/nibynic/ansible-introduction/5LYkLkGlzKyHxoyvSFP66b

# Vagrant

Create a new box:

    $ vagrant init ubuntu/trusty64; vagrant up --provider virtualbox

Get into machine:

    $ vagrant up
    $ ssh vagrant@192.168.33.10

# Ansible playbook

    $ ansible-playbook -i inventory setup.yml
