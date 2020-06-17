# Kali Linux Setting
## Mounting Shared Folder
```
sudo apt-get -y install open-vm-tools-desktop fuse && reboot
ps aux | grep vm
sudo mount -t fuse.vmhgfs-fuse .host:/ /mnt/hgfs -o allow_other
```
