#
# Makefile for the Linux Bluetooth HIDP layer
#

obj-$(CONFIG_BT_HIDP) += hidp.o

hidp-objs := core.o sock.o

ifdef CONFIG_MACH_MSM8960_MAKO_STRICT_ALIASING
CFLAGS_core.o := -fno-strict-aliasing
CFLAGS_sock.o := -fno-strict-aliasing
endif

