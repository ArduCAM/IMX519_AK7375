## Introduction

The driver for the IMX519 is already in the [Raspberry Pi kernel source](https://github.com/raspberrypi/linux/blob/rpi-5.15.y/drivers/media/i2c/imx519.c), so you don't need to compile it manually (unless you want to use it in a very old kernel).

However, the driver of the motor driver (AK7371/AK7375) on IMX519 needs to be updated, and the device tree of IMX519 also needs to be updated. 

This repository contains the above content.