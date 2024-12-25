# OpenCore-X99-RS9-Xeon-2680V4-RX570-EFI

# Specs:

|         Hardware       |                   Model                     | 
|-------------------:|:------------------------------------------|
|               Motherboard | Maschinist X99-RS9 (rev. 1.1)            |
|             CPU | Intel Xeon 2680 V4                           |
|             RAM | Samsung ECC 16GB DDR4 2400MHz |
|               GPU | Sapphire Pulse RX 570                   |
|               SSD |  Samsung 870 EVO                         |
|        Network | Realtek RTL8111  |



## Making the Bootable USB

### From macOS:
[**Link to Apple's Guide**](https://support.apple.com/en-us/101578)


1. Connect a >=16 GB pendrive.
2. Open *Disk Utility* and Erase the USB with the name: *MyVolume*.
3. Open *Terminal* and use the proper commands for your macOS installer:

- Sonoma: `sudo /Applications/Install\ macOS\ Sonoma.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume`
- Ventura: `sudo /Applications/Install\ macOS\ Ventura.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume`
- Monterey: `sudo /Applications/Install\ macOS\ Monterey.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume`
- Big Sur: `sudo /Applications/Install\ macOS\ Big\ Sur.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume`
- Catalina: `sudo /Applications/Install\ macOS\ Catalina.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume`
- Mojave: `sudo /Applications/Install\ macOS\ Mojave.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume`
- High Sierra: `sudo /Applications/Install\ macOS\ High\ Sierra.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume`

![macos-big-sur-terminal-create-bootable-installer](https://user-images.githubusercontent.com/70513735/138585740-c3b1c801-a946-40d2-9a1f-7584b5e04af2.jpg)


### From Windows:

[**Link to Dortania's Guide**](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/winblows-install.html)

### From Linux:

[**Link to Dortania's Guide**](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/linux-install.html)
