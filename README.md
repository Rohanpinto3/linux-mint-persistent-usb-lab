
# Linux Mint Persistent Live USB Setup Guide

## Overview

This project documents how I created a portable Linux Mint Live USB with persistence using a 16 GB USB drive.

## Hardware and Software Used

- 16 GB USB Flash Drive
- Windows Laptop
- Linux Mint Cinnamon ISO
- Rufus

### Features

- Persistent storage
- Portable Linux environment
- No changes to Windows installation
- Saves files and settings on  USB Flash Drive
- Great for learning Linux




---

## Step 1: Download Linux Mint

Visited the Linux Mint website and selected the Cinnamon edition.

![Step 1](https://files.catbox.moe/p7zmpl.png)

---

## Step 2: Select Download Mirror

Selected an India-based mirror to download the Linux Mint ISO.

![Step 2](https://files.catbox.moe/m4n20m.png)

---

## Step 3: Download Rufus

Downloaded Rufus to create the bootable USB.

![Step 3](https://files.catbox.moe/movevj.png)

---

## Step 4: Prepare the USB Drive

Inserted a 16 GB USB flash drive.

![Step 4](https://files.catbox.moe/j7nvdq.png)

---

## Step 5: Verify Downloads

Confirmed that both Linux Mint and Rufus were downloaded successfully.

![Step 5](https://files.catbox.moe/y7nqs2.png)

---

## Step 6: Create the Persistent Live USB

Configured Rufus with:

- Device: 16 GB USB
- Boot Selection: Linux Mint ISO
- Partition Scheme: GPT
- Target System: UEFI
- Persistence: 4 GB

Then clicked **Start**.

![Step 6](https://files.catbox.moe/s8eyxs.png)

---

## Step 7: Enter BIOS

Shut down the laptop and pressed **F2** during startup to enter BIOS.

![Step 7](https://files.catbox.moe/tqleuf.png)

---

## Step 8: Enable USB Boot

Enabled USB boot support.

![Step 8](https://files.catbox.moe/sz7j00.png)

---

## Step 9: Disable Secure Boot

Disabled Secure Boot Control.

<p align="center">
  <img src="https://files.catbox.moe/6029hk.png" width="45%">
  <img src="https://files.catbox.moe/ax416j.png" width="45%">
</p>


---

## Step 10: Disable Fast Boot

Disabled Fast Boot.

![Step 10](https://files.catbox.moe/snfe6j.png)

---

## Step 11: Save Changes

Saved BIOS settings and exited.

![Step 12](https://files.catbox.moe/r9wda0.png)

---

## Step 12: Set USB Boot Priority

Moved the USB drive above Windows Boot Manager.

![Step 12](https://files.catbox.moe/irf7ri.png)

---

## Step 13: Boot Linux Mint

Successfully booted into Linux Mint from the USB.



![Step 13](https://files.catbox.moe/pulxut.png)







<div align="center">

# 🚀 Mission Accomplished

<img src="https://files.catbox.moe/npyj0n.png" width="180">

### Windows is still safe!!!

Linux Mint now lives on a USB and carries its memories wherever it goes.

🐧 The penguin now travels with me.

</div>






