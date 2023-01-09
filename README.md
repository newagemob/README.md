# 🐙 🤿 About Me

### I make software for working divers 🦯

  + Founder of [Melon](https://www.divemelon.com) and [Liquid](https://www.liquid.cards)
  + Radar / Radio Tech
  + Controls Engineer
  + Commercial Diver


### Melon Projects

  + Log Book - Digital log keeping system for NDT and Diving operations - for iOS and Web
  + Metatron - Speech-To-Text Industry-Specific Models (Divers, Pilots, Surgeons etc.)
  + PetLoc - Petroleum Leak Locator + Delta Pressure Alert System
  + Hatbox - Blackbox that sits inside the diver's hat, constantly recording in case of comms failure
  + WetNet - Subsea mesh network, collecting NDT data and improving awareness with 3D models

  + Liquid - Load gift cards directly into your bank account
  + Newman - Intelligent Automation for Photographers

## Open Source Projects
  + [WikiGrab](https://github.com/newagemob/wikigrab)
  + [blockwill](https://github.com/newagemob/blockwill)
  + [NFT Mod](https://github.com/newagemob/nft-mod)
  + [Coinmon](https://github.com/newagemob/coinmon)
  

## 🟣 Resource Wiki 🟣

### ***NVIDIA Drivers***

Update / Fix Missing NVIDIA-SMI Package

```sh
sudo ubuntu-drivers autoinstall
sudo reboot
```

### ***Linux Scripts***

+ WGET PDF Files to current directory*

```sh
wget --no-directories --content-disposition -e robots=off -A.pdf -r ${PDF URL}
```

### ***PowerShell Scripts***

+ Install SSHD server **Powershell**

```sh
Add-WindowsCapability -Online -Name OpenSSH.Server*

# Install the OpenSSH Client

Add-WindowsCapability -Online -Name OpenSSH.Client~~~~0.0.1.0

# Install the OpenSSH Server

Add-WindowsCapability -Online -Name OpenSSH.Server~~~~0.0.1.0
```

#### _Config OpenSSH Server_

+ Start the sshd service

```sh
Start-Service sshd

# OPTIONAL but recommended:

Set-Service -Name sshd -StartupType 'Automatic'
```

### ***Reading List***

### ***Quick Links***
+ [Is M1 Ready?](https://isapplesiliconready.com/for/developer)
+ [Decompression Schedule (6)](http://www.usu.edu/scuba/navy_manual6.pdf)
