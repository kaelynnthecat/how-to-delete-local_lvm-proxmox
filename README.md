# # delete local LVM in PVE

lvremove /dev/pve/data
<br>
lvresize -l +100%FREE /dev/pve/root
<br>
resize2fs /dev/mapper/pve-root
<br>
centre de données > stockage > delete local-lvm
