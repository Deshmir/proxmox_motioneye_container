# proxmox motioneye container
This link/script will Install MotionEye in a proxmox container and config the defaults.

To create the MotionEye container in Proxmox you have to open a SSH shell or console and copy this link in it and hit "Enter"

```
bash -c "$(wget -qLO - https://raw.githubusercontent.com/Deshmir/proxmox_motioneye_container/master/create_container.sh)"
```
After the installation is done it wil give you the information to connect to the MotionEye Web interface.

## Reference
I forked this from JedimasterRDW to install with "--allow-releaseinfo-change" since the versioning changed.
