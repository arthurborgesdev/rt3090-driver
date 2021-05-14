![](https://img.shields.io/badge/Tutorials%20And%20Experiments-blue)

# rt3090-driver

> Code to solve bug on RT3090 driver after Ubuntu 20.04 update

## Built With

- Terminal
- Research on archaic and old Ubuntu forums

### Prerequisites

- Ralink RT3090 802.11b/g/n WiFi Adapter

### Usage

```
echo "options rt2800pci  nohwcrypt=1" | sudo tee /etc/modprobe.d/rt2800pci.conf
sudo modprobe -rfv rt2800pci
sudo modprobe -v rt2800pci
```

## Author

👤 **Arthur Borges**

- GitHub: [@arthurborgesdev](https://github.com/arthurborgesdev)
- Twitter: [@arthurmoises](https://twitter.com/arthurmoises)
- LinkedIn: [Arthur Borges](https://linkedin.com/in/arthurmoises)

## 📝 License

This project is [MIT](/LICENSE) licensed.
