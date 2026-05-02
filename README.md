# Instructions
- Check if OLED works with:

```dd if=/dev/random bs=1024 count=16 > /dev/fb1```


- Edit `/etc/wpa_supplicant.conf` to configure SSID and PSSWD for SSH

#### NOTE: This is configured for SH1106 OLED and uses the one of  the DTB provided with the rpi images. To use this with other displays, just change the dtb and the framebuffer driver in menuconfig (currently uses fb_sh1106). 
