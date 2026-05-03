# Instructions
- Check if OLED works with:

```dd if=/dev/random bs=1024 count=16 > /dev/fb1```


- Edit `/etc/wpa_supplicant.conf` to configure SSID and PSSWD for SSH

#### NOTE: This is configured for SH1106 OLED and uses the one of  the DTB provided with the rpi images. To use this with other displays, just change the dtb and the framebuffer driver in menuconfig (currently uses fb_sh1106). 

## Demo
<img width="600" alt="e4c82f24-4ee1-4dd7-8485-980fe8919c2e" src="https://github.com/user-attachments/assets/630e2446-7f63-4ed7-8abc-0bdc1dfa87a9" />
