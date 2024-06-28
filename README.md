# PS4_Ucode
This is the firmware that being use in the  Jaguarlinux  distro or lfs the project i am working on

# How to insall
1. So go to the release on github  and download the latest release  call ps4-ucode.tar.gz.
2. tar -xvzf ps4-ucode.tar.gz
3. cd linux-firmware-20240610
4. sudo make install-xz
5. you also have to cd amdgpu in the linux firmware folder then run xz -z liverpool* since the make install script will excluide the ps4 liverpool firmware file do the samething in  the radeon folder xz -z LIVERPOOL* liverpool*
6. mv LIVERPOOL* liverpool*
7. Done

# Thanks for reading 

