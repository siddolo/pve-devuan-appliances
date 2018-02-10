# pve-devuan-appliances
Build Devuan Virtual Appliances for Proxmox using DAB (Debian Appliance Builder)

## usage
```
cd devuan-1.0-standard-64
make

# Move the tar.gz into proxmox template directory
# For example: 
# mv debian-8.0-devuan-1.0-standard_1.0_amd64.tar.gz /rpool/template/cache/devuan-1.0-standard_1.0_amd64.tar.gz
```

## references
* https://pve.proxmox.com/wiki/Debian_Appliance_Builder
* https://pve.proxmox.com/wiki/Build_your_first_DAB_Appliance_Template
