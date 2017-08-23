# ansible-directadmin
go to file default enter 
directadmin_client_id: ?
directadmin_license_id: ? 
directadmin_hostname: ?


go to directory 
/etc/ansible/
nano /etc/ansible/directadmin.yml

- hosts: ip
  become: yes
  roles:
     - { role: directadmin }
     
nano /etc/ansible/hosts

[directadmin]
185.105.185.185 client_id= ? license_id= ? ansible_ssh_user=root


ansible-playbook directadmin.yml

don 😊😊
