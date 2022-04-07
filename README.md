# ansible

This are my ansible files repo.


1. In order to make git repo to work with your machine you have to add below in .ssh/config file

Host github.com
 Hostname ssh.github.com
 Port 443

2. In order to avoid warning python interpreter msg in your Ansible responces you have to add below in ansible.cfg file

[defaults]
interpreter_python=auto_silent  

