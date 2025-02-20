# HomeLab - Home Server
This repository serves as documentation for learning to setup and customize a home lab on a [RaspberryPi 3 B+](https://www.raspberrypi.com/products/raspberry-pi-3-model-b-plus/).

![image](https://github.com/user-attachments/assets/7ee7b072-f4de-41ff-91fe-748761d248d6)

## Minimum Hardware Required
- [RaspberryPi 3 B+](https://www.raspberrypi.com/products/raspberry-pi-3-model-b-plus/)
- MicroSD Card ([64GB](https://www.amazon.com/SanDisk-Ultra-microSDXC-Memory-Adapter/dp/B0B7NXBM6P/ref=asc_df_B0B7NXBM6P?mcid=b11e282abd153ad59597bb26ad4c7b82&hvocijid=8018304586228664257-B0B7NXBM6P-&hvexpln=73&hvadid=730434177080&hvpos=&hvnetw=g&hvrand=8018304586228664257&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=1017161&hvtargid=pla-2281435179778), or [128GB](https://www.amazon.com/SanDisk-Ultra-microSDXC-Memory-Adapter/dp/B0B7NTY2S6/ref=asc_df_B0B7NXBM6P?mcid=b11e282abd153ad59597bb26ad4c7b82&hvocijid=8018304586228664257-B0B7NXBM6P-&hvexpln=73&hvadid=730434177080&hvpos=&hvnetw=g&hvrand=8018304586228664257&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=1017161&hvtargid=pla-2281435179778))
- [Heatsink](https://www.amazon.com/LoveRPi-Performance-Heatsink-Set-Raspberry/dp/B018BGRDVS)
- [Power Supply](https://www.raspberrypi.com/products/raspberry-pi-universal-power-supply/)
- [Raspberry Pi 3 B+ Case](https://www.raspberrypi.com/products/raspberry-pi-3-case/)
- [HDMI Cable](https://www.amazon.com/AmazonBasics-High-Speed-HDMI-Cable-1-Pack/dp/B014I8SIJY/ref=zg_bs_g_202505011_d_sccl_3/144-2581314-6655903) 

## OS Installation
There are a variety of ways that you can go about installing the OS for a RPi (Raspberry Pi). My recommendation is to utilize the RPi Imager provided by Raspberry Pi to format a micro SD card and perform the OS install. The imager can be installed and used on macOS, Windows, and Linux devices alike as well as supported RPi devices.

### Install with RPi Imager
On a separate device, download the latest version of the [Raspberry Pi Imager](https://www.raspberrypi.com/software/). If you are using a RPi device, run the following command: 

`sudo apt install rpi-imager`.

Once you've installed the RPi Imager, run the application. You'll then be prompted with the following:

![image](https://github.com/user-attachments/assets/78c1f9ec-7752-4016-8d79-711c6fc3af41)

Click _Choose Device_ and select your corresponding hardware model. Then, click _Choose OS_ and select the desired RPi OS. The recommended option for most computers is the **Raspberry Pi OS (64-bit)**. Then, select the removable media where you want to store the OS. Once these options have been selected, click **Next**. You will be prompted with a window asking if you want to customize your OS. Click **Edit Settings** and customize the settings accordingly. Since we are customizing our RPi with creating a home lab environment in mind, 

More documentation for the imaging process can be found [here](https://www.raspberrypi.com/documentation/computers/getting-started.html#installing-the-operating-system).

## Post OS Installation 
After preparing your fresh install of your preferred RPi OS, you'll want to:
- Apply thermal paste to your heat sink, secure your heatsink to your CPU, and assemble the RPi inside of its case.
- Connect your micro SD card to your RPi.
- Connect your power supply and turn on your RPi.
- 
