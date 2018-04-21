# hardware-inventory_with_ansible

create hardware inventory; txt-file or csv

## Assumptions

* execete ansible scripts as root
* ansible directory is /etc/ansible (default in ubuntu)

## Preparations

* install ansible
 
 sudo apt-get install ansible

* copy public key to every host managed by ansible

* create key

 ssh-keygen    < no passphrase>

: creates private and public key in ~/.ssh/ with deafult names (id_rsa and id_rsa.pub)

* copy public key to remote host
 
 ssh-copy-id root@<hostname> 

* test ssh connection with rsa keys:

 ssh root@<hostname>

 you are logged in without password;

 exit to your ansible host








