# BigSur-11.2.1-OC-0.6.9-on-GIGABYTE-Z97M-D3H-AMD-R9-290-SUCCESS!!!
Big thanks to all for various inputs which have enabled to build the rig
as below. Max time taken to fire up good ol' R9 290 TRI-OC-X 4GB SAPPHIRE RADEON graphics card.

Motherboard: Gigabyte GA-Z97M-D3H
CPU: Intel Core i5-4460 @3.20 GHz
GPU: Sapphire Radeon R9 290 4GB GDDR5 Dual DVI-D/HDMI/DP TRI-X OC Version (UEFI) PCI-Express Graphics Card 
Audio: Realtek ACL892
RAM: 2x4GB RipJaw Ballistic DDR3 1600MHz
HDD: KINGSTON 120GB SSD
Ethernet: RealtekRTL8111 Ethernet


WIFI - AUSHA® USB WiFi Bluetooth Adapter - Wi-Fi Receiver & Wireless Bluetooth 2-in-1 Dongle - Works Natively
AMD Radeon R9 290 - Works fully 4096mb with a config mod
Intel i5 4460 - Recognized as i5 but all cores are active and good geekbench scores
Sound - Works well through Internal Speakers & R9 290 HDMI out 
Handoff and iMessage - Works (generate your own SMBios)

- Managed to get right installation in 2 stages
STAGE1: 
BigSur 11.2.1 OSX with OC 0.6.9 and attached config.plist (with original Z97 DSDT) settings as MacBookPro16.2 install.
(Clean install with Ethernet / audio working but only 7mb on R9 290 AMD card 
<https://drive.google.com/file/d/1FyI5gqw_lUm0ttvyZMBsjRqefdsfH0ob/view?usp=sharing>

STAGE2: Boot-args used for R9 install: keepsyms=1 alcid=3 -v debug=0x100 agdpmod=pikera -raddvi
EFI folder used only for firing up R9 290 AMD card AFter above install, Copy EFI folder for BigSur 11.2.1 OSX with OC 0.6.9 and attached config.plist (SSDTs + GPU Spoof) settings as MacBookPro17.1 install, AMD R9 290 now firing with 4GB as complete installation was failing midway with the 'GPU-Spoof SSDTs' but worked as a charm.
<https://drive.google.com/file/d/1D8LTOi54Du3LE9_egc5Z4mwyV8YXRRyf/view?usp=sharing>

![1](https://user-images.githubusercontent.com/15123801/121491382-84f7cb80-c9f3-11eb-8dcd-6d8e734e4085.jpg)
![2](https://user-images.githubusercontent.com/15123801/121491388-8628f880-c9f3-11eb-9534-8caae5e5094c.jpg)
![3](https://user-images.githubusercontent.com/15123801/121491392-86c18f00-c9f3-11eb-834f-ad2c08d9c753.jpg)
![4](https://user-images.githubusercontent.com/15123801/121491393-875a2580-c9f3-11eb-854d-d4bc32a7cac2.jpg)
![5](https://user-images.githubusercontent.com/15123801/121491395-87f2bc00-c9f3-11eb-998b-5ac62be4c669.jpg)
![6](https://user-images.githubusercontent.com/15123801/121491398-888b5280-c9f3-11eb-8996-41d78965096d.jpg)
![7](https://user-images.githubusercontent.com/15123801/121491399-888b5280-c9f3-11eb-930e-bda66c39fe5d.jpg)
![8](https://user-images.githubusercontent.com/15123801/121491402-8923e900-c9f3-11eb-8c2b-e46cb4ba64a8.jpg)

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
