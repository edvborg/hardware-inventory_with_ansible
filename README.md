# hardware-inventory_with_ansible

create hardware inventory; txt-file or csv

## Assumptions

* execete ansible scripts as root
* ansible directory is /etc/ansible (default in ubuntu)

## Preparations

### install ansible
 
 sudo apt-get install ansible


### create ssh keys for ssh login without password

 ssh-keygen  ##  < no passphrase>

 creates private and public key in ~/.ssh/ with default names (id_rsa and id_rsa.pub)
 
### copy public key to every host managed by ansible

 ssh-copy-id root@< hostname >

### test ssh connection with rsa keys:

 ssh root@< hostname >

 you are logged in without password;

 return with 'exit' to your ansible host

##

### change to /etc/ansible
 

### clone repo


### edit inventory 


### create symbolic link to your inventory


### edit playbook


### execute ansible script









