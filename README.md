# Hauppauge HVR-5500 Linux DVB-C by ZZRAM
Hauppauge WinTV-HVR-5500 Linux DVB-C support, based on patch provided by ZZRAM.

See official patch here: https://patchwork.linuxtv.org/patch/25867/

All credits go to ZZRAM, just did a clean-up and update for Linux 4.2RC5.

## Update to latest firmware (required)
	wget https://raw.github.com/torvalds/linux/master/Documentation/dvb/get_dvb_firmware
	chmod a+x get_dvb_firmware
	./get_dvb_firmware si2165
	sudo cp dvb-demod-si2165.fw /lib/firmware/
	sudo depmod -a
