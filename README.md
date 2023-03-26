Role Name
=========

A brief description of the role goes here.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

- bootstrap4ansible_user, optional, default: ansible
- bootstrap4ansible_user_pwd, optional, default: -
- bootstrap4ansible_user_generate_ssh_key, optional, defult: true
- bootstrap4ansible_user_ssh_key_bits, optional, defult: 2048
- bootstrap4ansible_user_public_key_file, optional, default: -
- bootstrap4ansible_user_groups, optional, default: -
- bootstrap4ansible_user_uid, optional, default: -
- bootstrap4ansible_user_comment, optional, default: 'Ansible Runtime User'

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: mprusov.bootstrap_linux_for_ansible, bootstrap4ansible_user: ansible }

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
