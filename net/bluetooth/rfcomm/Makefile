#
# Makefile for the Linux Bluetooth RFCOMM layer.
#

obj-$(CONFIG_BT_RFCOMM) += rfcomm.o

rfcomm-y			:= core.o sock.o
rfcomm-$(CONFIG_BT_RFCOMM_TTY)	+= tty.o

ifdef CONFIG_MACH_MSM8960_MAKO_STRICT_ALIASING
CFLAGS_core.o := -fno-strict-aliasing
CFLAGS_sock.o := -fno-strict-aliasing
CFLAGS_tty.o := -fno-strict-aliasing
endif

