# chrootjailer
Bash shell based chroot jail generator.

Creates a quick and simple chroot, for working commands it looks for libraries 
via ldd and loops over their library dependencies with 'ldd'. 

If libraries is all your commands need additional commands should work automatically. 

If not you will need to manually copy the files to their requisite locations.

![chrootjailer.png](https://raw.githubusercontent.com/AdamDanischewski/chrootjailer/assets/chrootjailer.png)
