# pve-devuan-appliances
Devuan Virtual Appliances for Proxmox

## usage
### Use ready-to-use template
Download the [ready-to-use template](https://github.com/siddolo/pve-devuan-appliances/releases) and upload it into Proxmox using the web interface or copy it into Proxmox template directory (for example /rpool/template/cache/).

### Build Devuan template using DAB (Debian Appliance Builder)
```
cd devuan-1.0-standard-64
make

# Move the tar.gz into proxmox template directory
# For example: 
# mv debian-8.0-devuan-1.0-standard_1.0_amd64.tar.gz /rpool/template/cache/devuan-1.0-standard_1.0_amd64.tar.gz
```
References:
* https://pve.proxmox.com/wiki/Debian_Appliance_Build
* https://pve.proxmox.com/wiki/Build_your_first_DAB_Appliance_Template
