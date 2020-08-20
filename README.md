# rt3090-driver
Code to solve bug on RT3090 driver after Ubuntu 20.04 update


```
echo "options rt2800pci  nohwcrypt=1" | sudo tee /etc/modprobe.d/rt2800pci.conf
sudo modprobe -rfv rt2800pci
sudo modprobe -v rt2800pci
```
