Role Name
=========

Hello! It's small Ansible Role for install FTP server (vsftpd) 

Access only for anon users
/var/ftp/pub - read-only files for anon, /var/ftp/pub/upload - read/write files for anon (without new directory creation)

Requirements
------------

No

Role Variables
--------------

defaults/main.yml

Dependencies
------------

No

Example Playbook
----------------

    - hosts: all
      roles:
         - vsftpd

License
-------

BSD

Author Information
------------------

sergei_golovanov2@epam.com
