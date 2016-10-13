include $(srctree)/drivers/misc/mediatek/Makefile.custom

# In case the platform does NOT support this type of sensors

obj-y   +=  accel.o accel_factory.o

ifeq ($(CONFIG_MTK_BMA222E),y)
obj-y   +=  bma222E/
endif
