obj-$(CONFIG_CONNECTOR)		+= cn.o
obj-$(CONFIG_PROC_EVENTS)	+= cn_proc.o

cn-y				+= cn_queue.o connector.o

ifdef CONFIG_MACH_MSM8960_MAKO_STRICT_ALIASING
CFLAGS_cn_queue.o := -fno-strict-aliasing
CFLAGS_connector.o := -fno-strict-aliasing
CFLAGS_cn_proc.o := -fno-strict-aliasing
endif

