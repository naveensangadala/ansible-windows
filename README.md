# ansible-windows
this repository is for installing the packages  and software by using Ansible-windows modules

and also playbook execution for the playbooks in this existing repository

playbook execution for win-java.yml Extra-vars 

ansible-playbook win-java.yml --extra-vars "jdk_package=jdk8 java_major_version=8.0 java_minor_version=162" --check

ansible-playbook win-java.yml --extra-vars "jdk_package=jdk8 java_major_version=8.0 java_minor_version=162" -vvv
