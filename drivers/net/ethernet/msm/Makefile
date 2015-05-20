#
# Makefile for the msm networking support.
#

obj-$(CONFIG_MSM_RMNET) += msm_rmnet.o
obj-$(CONFIG_MSM_RMNET_SDIO) += msm_rmnet_sdio.o
obj-$(CONFIG_MSM_RMNET_BAM) += msm_rmnet_bam.o
obj-$(CONFIG_MSM_RMNET_SMUX) += msm_rmnet_smux.o
obj-$(CONFIG_QFEC) += qfec.o

ifdef CONFIG_MACH_MSM8960_MAKO_STRICT_ALIASING
CFLAGS_msm_rmnet_bam.o := -fno-strict-aliasing
CFLAGS_msm_rmnet_smux.o := -fno-strict-aliasing
endif

