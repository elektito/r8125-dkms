# DKMS Module for Realtek 8125 2.5G Ethernet Controller

Original source code obtained from [here][1].

# How to add DKMS module

1. Copy repo contents to /usr/src in a directory named r8125-9.003.05.
2. Add DKMS module: `sudo dkms add -m r8125 -v 9.003.05`
3. Build DKMS module: `sudo dkms build -m r8125 -v 9.003.05`
4. Install DKMS module: `sudo dkms install -m r8125 -v 9.003.05`

# Credits

DKMS instructions mainly obtained from [here][2].

[1]: https://www.realtek.com/en/component/zoo/category/network-interface-controllers-10-100-1000m-gigabit-ethernet-pci-express-software
[2]: https://askubuntu.com/a/408616/45442
