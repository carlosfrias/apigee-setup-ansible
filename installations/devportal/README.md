# Apigee Private Cloud Dev Portal Installer
This script will install the `devportal` profile of the Edge installation. 

## Usage: 
This is an Ansible script and require Ansible. Please follow the usage instructions below:

### Dependencies
Use `ansible-galaxy` to download and install Ansible roles. This is best to perform after [Setup](#setup)
above. 
    
    ansible-galaxy install -r requirements -f
    
### Installer
This playbook completes the installation of the `devportal` instances of Edge.

    
    ansible-playbook install.yml 

