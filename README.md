# Prerequisites
Before you work through this tutorial you need:
Ansible 2.10 (or higher) installed
One or more network devices that are compatible with Ansible
Basic Linux command line knowledge
Basic knowledge of network switch & router configuration

# Install Ansible

Install Ansible using your preferred method. See Installing Ansible. Then return to this tutorial.

Confirm the version of Ansible (must be >= 2.10):

       ansible --version

# Running the playbook with the command:

      ansible-playbook  urlcheck
      
 `urlcheck` is an ansible yaml formatted script, when run with above command and it would show below output

![Ansible Playbook Output for microservice access](https://github.com/aiflare/ansible-assignment/blob/master/AnsibleOutput.PNG?raw=true)

![Ansible Playbook Output for Mac Address Info](https://user-images.githubusercontent.com/71802799/118094239-1b809f00-b3ec-11eb-8638-b0dcd5a4ae9c.png)
