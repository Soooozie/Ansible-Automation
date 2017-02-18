Experimenting with Ansible.  

ansible-playbook provision-instance.yml

This playbook is to help me automate website backup/migration.

Hosts file is not currently being tracked. UPDATE: a lot of files not being tracked. There's a .gitignore file that has some templates, vars, and my hosts file.

Working on adding SSL role to generate certs and set up nginx ssl termination.

Known issues:
-s3 setup and retrieval of objects and unarchiving of files is done via ansible running a bash script 

Please feel free to take a look. Advice/critique welcome.

Thank you!!
