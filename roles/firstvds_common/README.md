Role Name
=========

base role for configiration firsvds server

Requirements
------------

ansible [core 2.11.0]
servir in firstvds.ru

Role Variables
--------------

firstvds_common_username - username for deploy or working in server - create user directory and root access


Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: firstvds_common, tags: common }

first running

```
brew install hudochenkov/sshpass/sshpass
```

```
read -s PASS
ansible-playbook -i inventories/k3s_pc/hosts k3s_pc.yml -Dv
```

other running

ansible-playbook -i inventories/k3s_pc/hosts k3s_pc.yml -Dv

License
-------

BSD

Author Information
------------------

Ilya Ponomarev
