# ansible
the ansible task solution and few instruction to run on any centos8 machine
----------------------------------------------------------------------------
1-make sure to have python, pip, and ansible ! 
-if not, here are some resources that may help :
  1-for python and pip:(https://sourceexample.com/article/en/a27364fa0cc4f941ba58c9c3f20aeff9/)
  2-for ansible (https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#adding-ansible-command-shell-completion)
  https://centos.pkgs.org/8/centos-appstream-x86_64/python3-argcomplete-1.9.3-6.el8.noarch.rpm.html
  https://www.youtube.com/watch?v=_pFLQLUAzQg
----------------------------------------------------------------------------
Configure and run zabbix:
https://www.fosslinux.com/7705/how-to-install-and-configure-zabbix-on-centos-7.htm
https://repo.zabbix.com/zabbix/4.4/rhel/7/x86_64/
----------------------------------------------------------------------------
To Do :
Write an Ansible playbook to do the following:
  ○ Create a local yum repository on your machine which can be accessed from the
  other machines
  ○ Add this repo to the local machine and the remote machines
  ○ Install zabbix, zabbix-server, and zabbix-web on the server machine
  ○ Install zabbix,zabbix-agent on the clients
----------------------------------------------------------------------------
