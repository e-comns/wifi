# wifi mod

sudo add-apt-repository ppa:canonical-hwe-team/backport-iwlwifi
sudo apt-get update
sudo apt install backport-iwlwifi-dkms

reboot

# Bluetooth mod

Bluetooth 'searching forever issue' 

sudo apt remove blueberry  'removing bluberry manager'
sudo apt purge blueberry   
sudo apt install blueman   'installing blueman manager'
