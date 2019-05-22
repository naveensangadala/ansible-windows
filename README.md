# ansible-windows
ansible windows modules 

playbook execution for win-java.yml Extra-vars 

ansible-playbook win-java.yml --extra-vars "jdk_package=jdk8 java_major_version=8.0 java_minor_version=162" --check

ansible-playbook win-java.yml --extra-vars "jdk_package=jdk8 java_major_version=8.0 java_minor_version=162" -vvv
