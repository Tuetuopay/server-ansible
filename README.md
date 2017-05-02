# Post-installation playbook

This is my basic post-installation playbook to setup quite a lot of things
I use on my servers

## ansible-pull setup

Git and ansible needs to be installed (``yum install git ansible``)

    ansible-pull -U https://github.com/Tuetuopay/server-ansible.git -C ansible --purge -e@/absolute/path/to/local_config.yml

### Available variables

Just take a look at the `vars/` folder.

