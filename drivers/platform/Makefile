#
# Makefile for linux/drivers/platform
#

# Disable Wenum-conversion
ifeq ($(cc-name),clang)
EXTRA_CFLAGS += $(call cc-disable-warning, enum-conversion)
endif

obj-$(CONFIG_X86)		+= x86/
obj-$(CONFIG_OLPC)		+= olpc/
obj-$(CONFIG_GOLDFISH)		+= goldfish/
obj-$(CONFIG_CHROME_PLATFORMS)	+= chrome/
obj-$(CONFIG_ARCH_MSM)		+= msm/
