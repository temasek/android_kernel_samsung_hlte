ccflags-y += -Idrivers/media/platform/msm/camera_h
ccflags-y += -Idrivers/media/platform/msm/camera_h/sensor/io
ifeq ($(CONFIG_MSM_CSI20_HEADER),y)
  ccflags-y += -Idrivers/media/platform/msm/camera_h/sensor/csid/include/csi2.0
else ifeq ($(CONFIG_MSM_CSI30_HEADER),y)
  ccflags-y += -Idrivers/media/platform/msm/camera_h/sensor/csid/include/csi3.0
endif
obj-$(CONFIG_MSM_CSID) += msm_csid.o
