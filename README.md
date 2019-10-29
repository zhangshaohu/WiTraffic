# WiTraffic
This is the csi tool notes  when I worked on my paper:
WiTraffic: Low-cost and Non-Intrusive Traffic Monitoring System Using WiFi
Shaohu Zhang, Myounggyu Won, Sang H. Son
Proceedings of the IEEE 26th International Conference on Computer Communications and Networks ( ICCCN'17)

This is the research project based on the CSI tools

http://dhalperi.github.io/linux-80211n-csitool/

The Ubuntu version I used:

Download website:
http://old-releases.ubuntu.com/releases/14.04.2/

Ubuntu-14.04.1-desktop-amd64.iso
   22-Jul-2014 22:36 1.0G Desktop image for 64-bit PC (AMD64) computers (standard download)

UBUNTU_KERNEL_TAG=Ubuntu-3.13.0-32.57

# Issues 

## ieee 80211 phy1 hardware restart
solution:
sudo rfkill unblock wifi
ref: https://blog.csdn.net/caichao08/article/details/53894510


