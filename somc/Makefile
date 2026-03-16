dtb-y += elbe-overlay.dtbo elbe.dtb

always-y	:= $(dtb-y)
subdir-y	:= $(dts-dirs)
subdir-y	+= $(addprefix ../qcom/,bt data dsp graphics video wlan)
subdir-y	+= audio camera display nfc
clean-files	:= *.dtb *.dtbo
