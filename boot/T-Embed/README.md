# 🎞️ T-Embed Exclusive Boot Animations 

This folder contains a collection of custom startup animations (**GIFs**) specifically curated and optimized for the **LilyGO T-Embed**.

> [!IMPORTANT]
> These animations are **exclusively designed for the T-Embed**. They are tailored to match the specific resolution and display characteristics of this device. Please do not attempt to use these on other hardware to avoid display errors.

## 🚀 How to Install

To set a custom boot animation, follow these steps:

1.  **Download:** Select your preferred `.gif` file from this folder and save it to your computer.
2.  **Access Storage:** Open your T-Embed's SD card or LittleFS partition on your computer.
3.  **Transfer:** Copy the `.gif` file to the **root directory** of your storage (do not place it inside any folders).
4.  **Rename:** You **must** rename the file to exactly `boot.gif` for the firmware to recognize it during startup.
5.  **Apply:** Power cycle your T-Embed. The device will automatically load the `boot.gif` upon the next reboot.

---
*Tip: If the animation does not appear, ensure that your Bruce Firmware version is updated and supports custom boot sequences.*
