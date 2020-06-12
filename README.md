# halium-test-turbo
Test Images Prebuilt for Halium on Meizu Pro 5
---
- How to Install:
---
- Download rootfs from https://ci.ubports.com/job/xenial-rootfs-armhf/
- Download  halium-install-standalone.sh script https://github.com/JBBgameich/halium-install/releases
- $./halium-install-standalone.sh -p ut ./ubports-touch.rootfs-xenial-armhf.tar.gz ./system.img
- flash  halium-boot.img $ fastboot flash boot halium-boot.img
- On ubports recovery go to ubuntu actions wipe data and them boot the device.

---
- Meizu Pro 5 Halium 7.1 build
- Test build
---


- [ ] Booth image and system image build successfully
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
