# Grub-Update-Commands
Linux grub update commands Debian, CentOS, RHEL, Fedora

Debian & Debian Family's (Ubuntu, Kali, Lubuntu, Xubuntu etc)
```
sudo update-grub
```
Fedora
```
sudo grub2-mkconfig -o /boot/efi/EFI/fedora/grub.cfg
```
CentOS
```
sudo grub2-mkconfig -o /boot/efi/EFI/centos/grub.cfg
```
RHEL
```
sudo grub2-mkconfig -o $(readlink -f /etc/grub2-efi.cfg)
```
