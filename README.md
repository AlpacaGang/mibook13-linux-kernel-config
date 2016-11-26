# Mi Book 13 Linux Kernel Config

This is a configuration for Linux kernel compilation.
The configuration has been stipped down to include only the modules required by the system + some commond modules (es. ext2/ext4 ... ) the compleated list of modules is included in the file [modprobed.db](https://github.com/postadelmaga/mibook13-linux-kernel-config/blob/master/modprobed.db) 


# How I created the config

I created this config following the [Arch Linux ABS guide](https://wiki.archlinux.org/index.php/Kernels/Arch_Build_System) to compile the kernel and using [Modprobed-db](https://wiki.archlinux.org/index.php/Modprobed-db) to strip down as much module as possible but preserving the basic functionalities.





