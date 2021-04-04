Role Node-Exporter
=========

Install Node-exporter

Requirements
------------

Serveur Centos

Role Variables
--------------

node_exporter_version
node_exporter_source (URL)
node_exporter_bin (path bin)
node_exporter_user: node-exporter
node_exporter_group: node-exporter
node_exporter_dir_conf

Dependencies
------------

No dependencies

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - name: install node exporter
      hosts: all
      become: yes
      roles:
        - node-exporter

License
-------

BSD

Author Information
------------------

Karim BAIDI

https://linux-man.fr/
