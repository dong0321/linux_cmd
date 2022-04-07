# linux_cmd

#find a file

$sudo find . -type f |  grep cuda.h

#check disk spcae

$df -h

#create soft link

$sudo ln -sf libcuda.so.470.82.01 libcuda.so 

create libcuda.so and link to libcuda.so.470.82.01
lrwxrwxrwx 1 root root       20 Mar 17 16:25 libcuda.so -> libcuda.so.470.82.01

#how to find avail packages 

$sudo dnf  list --available | grep "nv"

#
$sudo apt-get autoclean #to clean up outdated package deb files
#
$sudo apt-get autoremove #to remove any unused dependencies
#
$sudo apt-get clean #to clean up apt cache
