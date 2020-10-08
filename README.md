# Create azure VM and enable RDP..

# After the VM got created
sudo apt-get install xrdp

# install lunbutu-desktop
sudo apt-get install lunbutu-desktop

# save a xsession file in root directory
echo "lxsession -s Lubuntu -e LXDE" > ~/.xsession

# restart xrdp service
sudo /etc/init.d/xrdp restart
