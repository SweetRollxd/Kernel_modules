obj-m += sysfs_kbleds.o
 
all:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) modules
sysfs_kbleds.o: sysfs_kbleds.c
	#gcc -c s.c
clean:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) clean
