qcache-y	:=	qcache-main.o tmem.o fmem.o

obj-$(CONFIG_QCACHE)	+=	qcache.o

ifdef CONFIG_MACH_MSM8960_MAKO_STRICT_ALIASING
CFLAGS_qcache-main.o := -fno-strict-aliasing
endif
