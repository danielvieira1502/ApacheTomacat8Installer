# Ansible Tomcat Automate Install
This is a ansible playbook to automate Apache Tomcat 8 installation.

### How To play

 ```shellscript
 $ ansible-playbook main.yml -i hosts -u REMOTE_USER -k
 $ password: ??????
 ```

### Requirements

 - Ansible 2.1+
 - python2

### Supported OSes

 - Debian like
 - RedHat like

### Supported Services Managers

 - SysVinit
 - SystemD
