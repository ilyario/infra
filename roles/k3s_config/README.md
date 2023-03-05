Role Name
=========

role copy k3s configuration in working directory user and add envirement KUBECONFIG


Role Variables
--------------

k3s_config_user_directory: "/home/ubuntu"

k3s_config_directory: "{{ k3s_config_user_directory }}/.kube"

k3s_config_path: "{{ k3s_config_directory }}/config"


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
      - { role: k3s_config, tags: k3s_config }

License
-------

BSD

Author Information
------------------

Ilya Ponomarev
