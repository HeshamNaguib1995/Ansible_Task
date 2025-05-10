# Ansible_Task
 1 - activate SSH 
     * sudo systemctl enable ssh
     * sudo systemctl start ssh
     * Get port using Command * sudo systemctl status ssh
 2 - make inventory file using SSH port and user and password
 3 - secure your inventory file
      * ansible-vault encrypt inventory 
 3 - make a directory for Roles 
 4 - using Ansible-galaxy to import roles 
      * e.g ansible-galaxy install geerlingguy.mysql
 5 - move Roles to Roles Directory
 6 - Seperate Each Role in it's playbook
 7 - make directory For Tasks 
 8 - Write playbook Tasks To handle playbook
 9 - using Tasks by Include 
 10 - run command 
     * ansible-playbook -i inventory playbook.yml --ask-vault-pass
