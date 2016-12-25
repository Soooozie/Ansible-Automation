Experimenting with Ansible.  

ansible-playbook provision-instance.yml

This will definitely not be complete for a while. UPDATE: This is actually somewhat complete!!

Working on creating a fully automated website backup using ansible. UPDATE: now fully automated. Sort of.

Hosts file is not currently being tracked. UPDATE: a lot of files not being tracked. There's a .gitignore file that has templates, vars, and my hosts file. And some templates for varnish (default.vcl, varnish.params, httpd.conf). Using openstack.py now for hosts since I'm having ansible create an instance and provision it from scratch.

I'm keeping the main-server.yml playbook for instances already running and provision-instance.yml is the playbook to run for having ansible create instance and run everything after that as well.

There's obviously still some issues.  

Please feel free to take a look. Advice/critique welcome.

Thank you!!
