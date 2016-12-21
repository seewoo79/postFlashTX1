# postFlashTX1
After flashing the NVIDIA Jetson TX1 Development Kit with JetPack, here is a collection of scripts that can be used to help configure the development environment.

> From: https://github.com/dusty-nv/jetson-scripts.git
> Set the CPU and GPU to max clock speeds, and uninstall some Unity desktop types of functionality

> jetson_max_l4t.sh           -- Set the CPU and GPU clocks to maximum speed
>
> uninstall_unity_scope.sh    -- Remove the Unity scopes

> ========

### Setup Swap File
> createSwapFile.sh - Create a swap file ; Use on external media like USB drive or SSD

> usage: createSwapFile [[[-d directory ] [-s size] -a] | [-h]]
>
> -d | --dir <directoryname>   Directory to place swapfile
>
> -s | --size <gigabytes>
>
> -a | --auto  Enable swap on boot in /etc/fstab 
>
> -h | --help  This message
>
> Note that if you enable swap on boot, you should also automount the drive that you're using

> =========



