#
# Copyright (C) 2013 Sony Mobile Communications AB.
#

obj-y += rgb_led/
#[VY5x] ==> CCI KLog, added by Jimmy@CCI
obj-$(CONFIG_CCI_KLOG)	+=	klog/
#[VY5x] <== CCI KLog, added by Jimmy@CCI

# S:LE
obj-$(CONFIG_CCI_KERNEL_INFO)	+=	cci_kernel_info/
# E:LE

#[VY5x] ==> SOMC XSSM driver by Bato@CCI
obj-$(CONFIG_CCI_SOMC_XSSM)     +=      somc_xssm/
#[VY5x] <== SOMC XSSM driver by Bato@CCI
obj-$(CONFIG_CCI_STUFF)	+=	cci_stuff/

#[VY5x] ==> DDR parameter dump, added by Grace@CCI
obj-$(CONFIG_CCI_DDR_PARAM_DUMP)	+=	ddr_param_dump/
#[VY5x] <== DDR parameter dump, added by Grace@CCI
