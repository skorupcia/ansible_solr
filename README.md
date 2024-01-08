# ansible_solr
Ansible solr search engine configuration with Paralells and Vagrant

macOS: Sonoma 14.1.1

Vagrant Box: luminositylabsllc/bento-ubuntu-20.04-arm64

Parallels: 19.1.1

Installation via GeerlingGuy roles:

1. Install roles with requiremensts file:
     $ ansible-galaxy install -r role_play/role_requirements.yml
3. Run the playbook with your inventory file:
     $ ansible-playbook -i role_play/role_playbook.yml

ATTENTION
  1. Remember to use 8983 port while connecting
  2. Run command to install roles with -c value (to ignore certificares) or install them with your own certificates if { SSL: CERTIFICATE_VERIFY_FAILED } appears.

-- Links --

https://github.com/geerlingguy/ansible-for-devops/tree/master

2nd edition of Ansible for DevOps Jeff Geerling
