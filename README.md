Role Name Cluster Kubernetes
=========

A brief description of the role goes here.

Requirements  
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.  
If you want to use the roles, you have to install 'docker'  

Role Variables
--------------
Modify the vars folder in roles, for chanching IP Address of the master-node and worker-node  
A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies  
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.  

Example Playbook
----------------
If you want user my playbook (kubernetes-playbook.yml), install ansible, git clone the projet and execute:  
ansible-galaxy install -r requirement  
ansible-playbook -i hosts --private-key vars/devops.pem kubernetes-playbook.yml --aks-vault-pass  

Or directly used my roles

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: kubernetesMaster }
         - { role: kubernetesWorker }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).

