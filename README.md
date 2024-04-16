# Node-Red Vigipool Config Generator 

[![en](https://img.shields.io/badge/lang-en-white.svg)](https://github.com/developer-ccei-pool/nodered-vigipool-config-generator/blob/master/README.md)
[![fr](https://img.shields.io/badge/lang-fr-white.svg)](https://github.com/developer-ccei-pool/nodered-vigipool-config-generator/blob/master/README.fr.md)

This script will allow you to quickly configure Node-Red to be able to make your Vigipool products accountable

This will allow you to add other MQTT products to your Home Assistant setup

List of Vigipool devices compatible with the installer:
- Tild
- Phileo VP
- Ofix
- AnteaM
- Zelia
- VigiBrio

## Prerequisites

### MQTT server

- Have created an MQTT server which will allow you to centralize all your data and note its IP address

### Vigipool product

- Have a Vigipool product
- Use the Vigipool mobile application to connect to the Vigipool product then configure the product to connect it to your Wi-Fi and know its IP

## Configuration

1. Connect to your Home Assistant interface (http://homeassistant:8123/)

1. Click “Settings” ![step 1](https://raw.githubusercontent.com/developer-ccei-pool/home-assistant-vigipool-installer/main/img/en/1.png)

1. Click “Add-ons” ![step 2](https://raw.githubusercontent.com/developer-ccei-pool/home-assistant-vigipool-installer/main/img/en/2.png)

1. Click “Add-ons Store” ![step 3](https://raw.githubusercontent.com/developer-ccei-pool/home-assistant-vigipool-installer/main/img/en/3.png)

1. Click “Terminal & SSH” (If the module does not appear, it is because your account is not in advanced mode, a message should automatically appear which will redirect you to the menu to activate this functionality if this is the case.) ![step 4](https://raw.githubusercontent.com/developer-ccei-pool/home-assistant-vigipool-installer/main/img/en/4.png)

1. Click “Install” ![step 5](https://raw.githubusercontent.com/developer-ccei-pool/home-assistant-vigipool-installer/main/img/en/5.png)

1. Click “Start” ![step 6](https://raw.githubusercontent.com/developer-ccei-pool/home-assistant-vigipool-installer/main/img/en/6.png)

1. Click "Open Web UI" ![step 7](https://raw.githubusercontent.com/developer-ccei-pool/home-assistant-vigipool-installer/main/img/en/7.png)

1. Copy the following line: 
######
    wget -q https://raw.githubusercontent.com/developer-ccei-pool/nodered-vigipool-config-generator/main/vigipool_installer.sh && chmod +x vigipool_installer.sh && bash vigipool_installer.sh

10. Paste the line into the terminal. To do this, you can use the following keyboard shortcut "Ctrl+shift+v" or this one "shift+ins"
![step 8](https://raw.githubusercontent.com/developer-ccei-pool/home-assistant-vigipool-installer/main/img/en/8.png)

11. Follow the terminal instructions.
