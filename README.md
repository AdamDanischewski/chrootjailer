# chrootjailer
Bash shell based chroot jail generator.

Creates a quick and simple chroot. For command support - the script loops over command's library dependencies via ldd and copies them to their respective /lib[64] folder. 

If libraries is all your programs need additional commands should work automatically. 

If not, you will need to manually copy files to their requisite locations.

![chrootjailer.png](https://raw.githubusercontent.com/AdamDanischewski/chrootjailer/assets/chrootjailer.png)
