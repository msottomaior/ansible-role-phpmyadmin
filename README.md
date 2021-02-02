Role phpMyAdmin
=========

Ansible role for a Debian/Ubuntu distro to download and upgrade phpMyAdmin.

Requirements
------------

//TODO Python3 with pip and "certifi" - "pip3 install certifi" add as "task" if not present.

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

See vars folder file for phpMyAdmin
download_dir: /tmp #you can specify here another folder 
phpmyadmin_dir: /usr/share/phpmyadmin #standard location for Debian
phpmyadmin_version: 5.0.4 # At this point, that is the latest version
phpmyadmin_checksum: sha256:fbb993b74a7c29ce2fcdb6b6be22b0b6c58bff8df3292ab42f6280871450c316 

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
