This repository includes the binary file for installing openwrt on DIR-853 on hardware A3, after the 2023 stock firmware update (as the factory bin from firmware selector doesn't work).</br>
</br>
Installation steps:</br>
1. Install the openwrt-22.03.0-ramips-mt7621-dlink_dir-853-a3-squashfs-factory-patched.bin as an upgrade file in dlink.</br>
2. Upgrade openwrt to openwrt-22.03.0-ramips-mt7621-dlink_dir-853-a3-squashfs-sysupgrade.bin , it contains the EEPROM patch for WiFi</br>
3. Then you can upgrade to the latest sysupgrade from firmware selector.</br>
