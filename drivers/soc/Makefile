#
# Makefile for the Linux Kernel SOC specific device drivers.
#

# Disable Wstrict-prototypes
ifeq ($(cc-name),clang)
EXTRA_CFLAGS += $(call cc-disable-warning, strict-prototypes)
endif

obj-$(CONFIG_ARCH_MSM)		+= qcom/
obj-$(CONFIG_ARCH_TEGRA)	+= tegra/
obj-$(CONFIG_SOC_TI)		+= ti/
obj-$(CONFIG_PLAT_VERSATILE)	+= versatile/
