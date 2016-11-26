# Mi Book 13 Linux Kernel Config

This is a configuration for Linux kernel compilation.

The configuration has been stipped down to include only the modules required by the system + some commond modules (es. ext2/ext4 ... ) the complete list of modules is included in the file [modprobed.db](https://github.com/postadelmaga/mibook13-linux-kernel-config/blob/master/modprobed.db) 

# Enable Nvidia Bumblebee (alias optimus)

On Arch system you will have to install `nvidia-dpkg` and `bbswitch-dpkg` in order to compile automatically the required extra modules for this custom kernel.
Once you install the above packages the compilation will be done automatically during installation of the kernel.
This assume that you already enabled Bumblebee on your system: this is a [good guide](https://antergos.com/wiki/hardware/graphics/bumblebee-for-nvidia-optimus/) by Antegos folks 


# How I created the config

I created this config following the [Arch Linux ABS guide](https://wiki.archlinux.org/index.php/Kernels/Arch_Build_System) to compile the kernel and using [Modprobed-db](https://wiki.archlinux.org/index.php/Modprobed-db) to strip down as much module as possible but preserving the basic functionalities.





