# Asus Rog Strix B450-F Hackintosh
![Catalina Screenshot](Screenshot-Catalina.png)
![BigSur Screenshot](Screenshot-BigSur.png)
## OpenCore 0.6.5 Configuration for Asus Rog Strix B450-F Motherboard Ryzen 1000-2000-3000-5000
###
  Tested:
  macOS Mojave, Catalina, BigSur
  <br>
  * I did not bother to update the config to for macOS Monterey as there are stability problems with the on-board ethernet.
  [probable fix](https://github.com/donatengit/AppleIGB)
  - update: AppleIGB ethernet seems to be reasonably stable,  if you need an update for monterey, let me know<br>
  - update: [this](https://www.reddit.com/r/hackintosh/comments/uchsq6/i211_nic_fix_in_monterey/) may fix the ethernet issue too<br>
  * macOS Mojave may need some additional work.
####
  My Configuration:
      - Rog B450-F
      - Ryzen 3600x
      - MSI RX588
  Working:
      - Audio
      - Graphics
      - AMD Power Gadget
      - Xcode Emulation (Except Apple Watch)
      - Ethernet Connection
      - NVMe and Sata Drives
      - Almost Everything...

####
  Change "MLB" (Main Board Serial Number), "SerialNumber" and "UUID" with another one using [genSMBIOS](https://github.com/corpnewt/GenSMBIOS) tool<br>
  This configuration can also be used with B450i Motherboard from Asus (Audio pci root should be modified)
