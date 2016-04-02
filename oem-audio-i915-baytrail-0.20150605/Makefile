# needless plumbing necessary for dkms to function correctly

ifeq (,$(KVER))
	KERNELBUILD := /lib/modules/`uname -r`/build
else
	KERNELBUILD := /lib/modules/$(KVER)/build
endif

all:
	make -C $(KERNELBUILD) M=$(shell pwd) modules

clean:
	make -C $(KERNELBUILD) M=$(shell pwd) clean
