# Archlinux Kernel Working For Me

1. xanmod patches
2. ~uksm patches~
3. cjktty patches
4. no archlinux patches
5. need archzfs repo
6. Added Legion Patches

**注意** 

**This Kernel for me only in Archlinux**

````
gpg --keyserver hkps://keyserver.ubuntu.com --recv-keys ABAF11C65A2970B130ABE3C479BE3E4300411886
````
For Linux Torvalds

````
gpg --keyserver hkps://keyserver.ubuntu.com --recv-keys 647F28654894E3BD457199BE38DBBDC86092693E
````
For Greg Kroah-Hartman

Have to add archzfs repository.

````
[archzfs]
Server = http://archzfs.com/$repo/$arch
Server = http://mirror.sum7.eu/archlinux/archzfs/$repo/$arch
Server = https://mirror.biocrafting.net/archlinux/archzfs/$repo/$arch
Server = https://mirror.in.themindsmaze.com/archzfs/$repo/$arch
Server = https://zxcvfdsa.com/archzfs/$repo/$arch
````

Add archzfs.gpg
````
curl -L https://archzfs.com/archzfs.gpg |  pacman-key -a -
curl -L https://git.io/JsfVS | xargs -i{} pacman-key --lsign-key {}
````
