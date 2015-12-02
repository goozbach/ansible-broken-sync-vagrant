# ansible-broken-sync-vagrant
Ansible synchronize is broken with vagrant (maybe sudo altogether)

This is a proven broken case.

Just run

    vagrant up

to see the error in progress

ansible version:

    ansible-playbook 2.0.0 (devel b5f2c3def2) last updated 2015/11/30 12:20:04 (GMT -600)
        lib/ansible/modules/core: (devel 2dba0d8d3a) last updated 2015/11/30 13:40:07 (GMT -600)
        lib/ansible/modules/extras: (detached HEAD e46e2e1d6f) last updated 2015/11/23 13:02:02 (GMT -600)
        config file = /Users/derekcarter/.ansible.cfg
        configured module search path = Default w/o overrides
