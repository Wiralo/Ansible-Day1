# Ansible-Day1
First Ansible playbook command sample
# This first ansible playbook is for learning to execute unix command in local machine where ansible is installed. 

#Step A 

Installations & Environment Setup

1. Install latest Ansible program to your control machine 
(Control machine is your laptop or any computer from where you will execute command, in real environment the executed command will be implemented in remot hosts, usually severs in cloud or your your private data center where you will concigure your ansible to long in using SSH)

2. To check the verison of Ansible and locan of executable ansible, library and plougins, use below command; 
$ansible --version (if you see detailed output your install is succeded)

#Step B

3. Creat any directory  in your machine to setup ansible playbook and enviroment eg. 
        ---anisble3



4. inside ansible3 directoty create a ansible host file "host-dev"
        ---anisble3
        ------host-dev
        this host file contains the host node ip ( in our example our local machine and loopback ip 127.0.0.1)

5. inside ansible3 directory create a ansible configuration file "ansible.cfg"
        ---anisble3
        ------host-dev 
        ------ansigle.cfg 
        this ansible.cfg file contanis the enviroment that ansible look for executing the command in that directory

6. inside ansible3 directory create create playbook "playbook.yml" file where we have our linxu command that will be executed in host machine from 
corntrol machine. In our case the host machine is our local machine. 
        ---anisble3
        ------host-dev 
        ------ansigle.cfg
        ------playbook.yml 

7. run the command as below; 
        $ansible-playbook playbook.yml

8. Now you create and execute successful first playbook file in Ansible with environment steup. 

Note: this turorial is free to copy, and develope further. Thank you. 

