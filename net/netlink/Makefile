#
# Makefile for the netlink driver.
#

obj-y  				:= af_netlink.o genetlink.o

ifdef CONFIG_MACH_MSM8960_MAKO_STRICT_ALIASING
CFLAGS_KERNEL := -fno-strict-aliasing
endif
