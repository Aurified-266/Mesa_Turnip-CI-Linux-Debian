This is a bash script to build freedreno/turnip for android as a magisk module. Made specifically for compatibilty with linux-deb. Linux-deb users may encounter a host of problems when attemptiong to compile the bash script origionally given by k11mch1, this new bash script bypasses issues surrounding header problems, linker issues, and lack of identifying deb /usr prereq install locations.

### Notes;

#### Magisk build:
- Root must be visible to target app/game.
- Tested with these apps/games listed [here](list.md).

### To Build Locally
- Obtain the script [turnip_builder.sh]
- Execute script on linux terminal ```bash ./turnip_builder.sh```

### References

- https://forum.xda-developers.com/t/getting-freedreno-turnip-mesa-vulkan-driver-on-a-poco-f3.4323871/

- https://gitlab.freedesktop.org/mesa/mesa/-/issues/6802

- https://github.com/bylaws/libadrenotools
