# halium-test-turbo
#include <std_disclaimer.h>

/*
 * Your warranty is now void.
 *
 * We are not responsible for bricked devices, dead SD cards,
 * thermonuclear war, or you getting fired because the alarm app failed. Please
 * do some research if you have any concerns about features included in this ROM
 * before flashing it! YOU are choosing to make these modifications, and if
 * you point the finger at us for messing up your device, we will laugh at you.
 *
 */

Test Images Prebuilt for Halium on Meizu Pro 5
---
- How to Install:
---
- Download rootfs from https://ci.ubports.com/job/xenial-rootfs-armhf/
- Download  halium-install-standalone.sh script https://github.com/JBBgameich/halium-install/releases
- $./halium-install-standalone.sh -p ut ./ubports-touch.rootfs-xenial-armhf.tar.gz ./system.img
- flash  halium-boot.img $ fastboot flash bootimg halium-boot.img
- On ubports recovery go to ubuntu actions wipe data and them boot the device.

---
- Meizu Pro 5 Halium 7.1 build
- Test build
---


- [X] Booth image and system image build successfully
- [ ] Device boots into rootfs its hard to boot a second time
- [ ] LXC container starts and does not crash
- [ ] libhybris tests
- [ ] Wifi
- [ ] Bluetooth
- [ ] Flash Light
- [ ] Vibration
- [ ] WIDI
- [ ] Audio
- [ ] Audio on Calls
- [ ] Audio on Headphones
- [ ] Camera Pictures
- [ ] Camera Video Recording - Does not work
- [ ] Video Decode
- [ ] Light/Proximity
- [ ] Notidication LEDS
- [ ] Rotation
- [ ] RNDIS
- [ ] GPS
- [ ] MPT -Not Fully working

<!-- 
Other information goes below this comment. Possible topics of comment may 
include special flashing or building instructions, such as manual effort to
change vendor files.
-->
