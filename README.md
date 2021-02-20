# rancheros-services

## samba
```
sudo docker run --net=host -d --name samba -v /mnt/data:/mount dperson/samba -p -s "scan;/mount/scan;yes;no;yes" -s "media;/mount/media;yes;no;yes" -s "docs;/mount/docs;yes;no;yes"
```