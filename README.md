# netbsd-efi-install

# Record my netbsd-efi install in VirtualBox

1. Download netbsd-amd64-install.img.gz and decompress
2. use VirtualBox's "VBoxManage" to convert img
  'VBoxManage convertdd netbsd.img netbsd.vdi'
4. Add a harddisk in VirtualBox 's Controller IDE with above vdi file
5. Start your VirtualBox machine 
6. in EFI shell, swtich to fs1: and find your EFI file under the vdi disk
7. Boot it！
