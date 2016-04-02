DRIVER_NAME := hdmi_audio

# Diwic
ccflags-y += -I../i915

$(DRIVER_NAME)-objs += \
	intel_mid_hdmi_audio.o \
	intel_mid_hdmi_audio_if.o

obj-m += $(DRIVER_NAME).o
