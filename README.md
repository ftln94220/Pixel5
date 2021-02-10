# Pixel 5
 Pixel 5 Enable 5G

# Important Links

- Modify Bands Tutorial https://mt-tech.fi/en/modify-oneplus-7-pro-5g-8-and-8-pro-nr-lte-a-band-combos/ 
- Qualcom tools a drivers https://freebox.lear.ovh/share/evKn9vDPX_19qT4l/Mi5_Qualcomm_Drivers.zip / https://freebox.lear.ovh/share/f95F3r5V_eKVjlej/QPST_2.7.496.zip

# XDA Threads
- Success Stories https://forum.xda-developers.com/t/how-to-add-5g-configurations-to-your-pixel-5-solved.4187025/
- Enable Qualcom Diagnostic to access EFS https://forum.xda-developers.com/t/network-signal-guru.4005511/page-4#post-83499679

# How to enable qualcom diag
- Root device
- Enable usb debugging
- Install google phone drivers
- Connect phone to PC
- Download ADB https://developer.android.com/studio/releases/platform-tools
- Unzip folder and open cmd prompt in folder
- #adb shell <for opening shell>
- #su <for gaining root access in shell, accept pop up on phone>
- #resetprop ro.bootmode usbradio
- #resetprop ro.build.type userdebug
- #setprop sys.usb.config diag,diag_mdm,adb
- #diag_mdlog
- Press ctrl+c when shell output freezes on "failed to open diag socket"
- On phone enable file transfer, wait 2 seconds and then disable file transfer
- Open QPST and follow steps mentioned in this blog: https://mt-tech.fi/en/modify-oneplus-7-pro-5g-8-and-8-pro-nr-lte-a-band-combos/

- If you see unrecogonized pixel device in device manager, right click and install driver in above Qualcom drivers link: https://freebox.lear.ovh/share/evKn9vDPX_19qT4l/Mi5_Qualcomm_Drivers.zip


Intention is to use above information to enable 5G on Pixel 5 with Free Mobile in France


