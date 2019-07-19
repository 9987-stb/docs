---
layout: article
title: Install the System76 Driver
description: >
    Our System76 Driver can generate system logs, we'll also go over how to reinstall the NVIDIA Driver.
keywords:
  - system76
  - driver
  - NVIDIA
  - support
image: http://support.system76.com/images/system76.png
hidden: false
section: hardware-drivers

---

### System76 Driver

To install our Driver you need to run the following commands in the Terminal:

```
sudo apt-add-repository -y ppa:system76-dev/stable
sudo apt-get update
sudo apt-get install -y system76-driver
```

#### Generate Log Files

The System76 Driver can be opened by pressing the Ubuntu or Pop key and then search for 'system76', then click on the System76 Driver. 

Next click on the button outlined in red in the <u>System76 Driver</u> application and there will be a file called `system76-logs.tgz` placed in your Home directory (/home/username)

![CreateLogFiles](/images/system76-driver/CreateLogFiles.png)

### System76 NVIDIA Driver

Follow the above steps as well as this additional command if you have a NVIDIA GPU:

```
sudo apt-get install system76-driver-nvidia
```
