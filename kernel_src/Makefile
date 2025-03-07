obj-m += reveng_rtkit.o

KERNEL_ROOT=/lib/modules/5.15.0-134-generic/build

modules:
	@$(MAKE) -C $(KERNEL_ROOT) M=$(shell pwd) modules

clean:
	@$(MAKE) -C $(KERNEL_ROOT) M=$(shell pwd) clean

