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

### change  directory to /etc/ansible
 

### clone repo


### edit inventory 


### create symbolic link to your inventory


### edit vars in playbook


### execute ansible script


## Result

'''cat borg_hardwarereports/report_O2-10-PC01.csv 

Hostname;Hersteller;Bezeichnung;Seriennummer;Netzwerk-IP;Netzwerk-MAC;Festplatte;Arbeitspeicher

O2-10-PC01;LENOVO;ThinkCentre M83;S4N12557;192.168.140.200;6c:0b:84:0b:ed:ec;119.24 GB;3833








