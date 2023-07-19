# How to use it


Place your OVPN certificate in the "/var/snap/simple-openvpn-client/common/" folder
named "client.ovpn" then restart the app. The device will be connected at boot
the command is:

    sudo cp yourfile.ovpn  /var/snap/simple-openvpn-client/common/client.ovpn


The apps starts at boot and connects the VPN server automatically. 

