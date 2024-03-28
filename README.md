# AT-Home-server

Welcome to my home server setup! This guide will walk you through the steps of setting up a home server using Ubuntu and `etherwake`.

## Introduction

A home server is a great way to centralize resources and services within your home network. With Ubuntu as the operating system and `etherwake` for remote wake-on-LAN capabilities, you can create a powerful and versatile server for various tasks such as file storage, media streaming, and more.

## Prerequisites

Before getting started, make sure you have the following:

- A computer or dedicated hardware for the server
- Ubuntu installed on the server
- Basic understanding of the Linux command line
- Devices that support Wake-on-LAN (WoL)

## Installation

### Installing Ubuntu

1. Download the latest version of Ubuntu from the official website.
2. Follow the installation instructions to install Ubuntu on your server hardware.
3. Make sure to configure network settings properly during installation.

### Installing etherwake

`etherwake` is a command-line utility for sending Wake-on-LAN packets. You can install it using the following command:

```bash
sudo apt update
sudo apt install etherwake

Configuring Wake-on-LAN
Once etherwake is installed, you can configure Wake-on-LAN functionality on your server.

Ensure Wake-on-LAN is enabled in your server's BIOS settings.
Find the MAC address of the target device you want to wake up. You can usually find this in your router's connected devices list or by running ifconfig on the target device.
Use the following command to wake up the device:

sudo etherwake -i <interface> <MAC address>

Usage
Once your home server is set up and configured, you can use it for various purposes such as:

File storage and sharing using Samba or NFS.
Media streaming using Plex or Kodi.
Automated backups using rsync or other backup solutions.
Hosting personal websites or applications.
Conclusion
Setting up a home server with Ubuntu and etherwake provides a flexible and customizable solution for your home network needs. With Wake-on-LAN capabilities, you can remotely wake up your server as needed, ensuring it's available whenever you need it.

Feel free to explore additional software and services to enhance your home server experience!
