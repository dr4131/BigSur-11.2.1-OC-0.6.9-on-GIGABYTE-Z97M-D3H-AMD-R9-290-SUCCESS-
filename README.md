BigSur 11.2.1-OC 0.6.9 on GIGABYTE-Z97M-D3H /AMD-R9-290 SUCCESS!!!

Big thanks to all for various inputs which have enabled to build the rig
as below. Max time taken to fire up good ol' R9 290 TRI-OC-X 4GB SAPPHIRE RADEON graphics card.
But managed to do it in the end.

Motherboard: Gigabyte GA-Z97M-D3H
CPU: Intel Core i5-4460 @3.20 GHz
GPU: Sapphire Radeon R9 290 4GB GDDR5 Dual DVI-D/HDMI/DP TRI-X OC Version (UEFI) PCI-Express Graphics Card 
Audio: Realtek ACL892
RAM: 2x4GB RipJaw Ballistic DDR3 1600MHz
HDD: KINGSTON 120GB SSD
Ethernet: RealtekRTL8111 Ethernet

Boot-args used: keepsyms=1 alcid=3 -v debug=0x100 agdpmod=pikera -raddvi

WIFI - AUSHA® USB WiFi Bluetooth Adapter - Wi-Fi Receiver & Wireless Bluetooth 2-in-1 Dongle - Works Natively
AMD Radeon R9 290 - Works fully 4096mb with a config mod
Intel i5 4460 - Recognized as i5 but all cores are active and good cinebench scores
Sound - Works through Internal Speakers & R9 290 HDMI out 
Handoff and iMessage - Works (generate your own SMBios)
NOTE: Turn off -v in boot args after everything works.

- Managed to get right installation in 2 stages
STAGE1: 
BigSur 11.2.1 OSX with OC 0.6.9 and attached config.plist (with original DSDT) settings for MacBookPro16.2.
(Clean install with Ethernet / audio working but only 7mb on R9 290 AMD card 
<https://drive.google.com/file/d/1FyI5gqw_lUm0ttvyZMBsjRqefdsfH0ob/view?usp=sharing>

STAGE2: Only for firing up R9 290 AMD card 
AFter above install Copy EFI folder for BigSur 11.2.1 OSX with OC 0.6.9 and attached config.plist (SSDTs + GPU Spoof) settings for MacBookPro17.1 settings
(AMD R9 290 now firing with 4GB) as complete installation was failing midway with the 'GPU-Spoof SSDTs' but worked as a charm when full EFI folder was replaced after Stage1 install. 
<https://drive.google.com/file/d/1D8LTOi54Du3LE9_egc5Z4mwyV8YXRRyf/view?usp=sharing>

Big Thanks to below forums / links which immensely hepled to tweak at various levels.
- https://www.tonymacx86.com/threads/success-big-sur-on-ga-z87-d3hp-i5-4570-gt740.306442/
- https://www.tonymacx86.com/threads/success-big-sur-gigabyte-h110m-a-amd-r9-290.312301/
- https://www.tonymacx86.com/threads/opencore-fake-id-gpu-spoof-r9-290-failed.297248/
- https://www.tonymacx86.com/threads/guide-booting-the-usb-installer-using-opencore.302584/
- https://github.com/greenzone560
- https://github.com/insanelymacdiscord/Getting-Started-With-OpenCore
- https://www.insanelymac.com/forum/profile/1443325-swear/
- https://www.insanelymac.com/forum/topic/345397-big-sur-110-20a5384c-successfully-installed-and-perfectly-running-thanks-to-opencore/
- https://www.reddit.com/user/deejumpz9m/comments/84t35r/anyone_running_an_r9_290390_on_10133/
- https://www.youtube.com/watch?v=XAHSkwbIb7k
- https://www.youtube.com/watch?v=atnIrHlPqG8
- https://hackintosher.com/forums/thread/solved-catalina-vs-amd-radeon-r9-290x-cant-boot-after-installation.10218/#lg=thread-10218&slide=0
- https://www.elitemacx86.com/threads/how-to-enable-amd-rx-6800-rx-6800xt-and-rx-6900xt-on-macos-big-sur-and-later.709/
- https://www.reddit.com/r/hackintosh/comments/hpa06v/have_anybody_managed_to_get_the_amd_r9_290/
