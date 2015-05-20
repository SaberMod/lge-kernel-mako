#
# Makefile for the key AF.
#

obj-$(CONFIG_NET_KEY) += af_key.o

ifdef CONFIG_MACH_MSM8960_MAKO_STRICT_ALIASING
CFLAGS_KERNEL := -fno-strict-aliasing
endif
