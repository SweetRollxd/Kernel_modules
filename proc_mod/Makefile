obj-m += proc_mod.o
 
all:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) modules
proc_mod.o: proc.c
	gcc -c proc_mod.c
clean:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) clean
