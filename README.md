# scriptfour
#!/bin/bash
#The following program is to open the partition options

echo display fdisk information
echo
fdisk -l

echo select fdisk dev/sda
echo
fdisk dev/sda

echo type m for more information or help about partition
#Type "m" to see the partitions options
#Thanks
#Jorge Montalvan
