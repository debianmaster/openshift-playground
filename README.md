# Clone repo  
```sh
https://github.com/debianmaster/openshift-playground.git
cd openshift-playground
```




# Download virutalbox
> Download rhel7 virualbox from https://access.redhat.com/downloads/content/293/ver=1/rhel---7/1.0.1/x86_64/product-software
> RHEL 7.1 Vagrant box for VirtualBox  ---- Download this 

 
## Name download image as rhel7 
```sh
downloadVBox.sh
```

# Spin up VMS
```sh
./up.sh
```

# Clone openshift ansible & run playbook

```sh
git clone https://github.com/debianmaster/openshift-ansible.git
cd openshift-ansible
ansible-playbook playbooks/byo/config.yml -i ../hosts
```







