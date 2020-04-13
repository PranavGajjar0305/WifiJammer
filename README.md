# WifiJammer

WifiJammer works on python3. It use the different library of python like threading, subprocess, time, tkinter etc. It also use Aircrack-ng tool.

Aircrack-ng is a complete suite of tools to assess WiFi network security. We can use it for scanning and sending different type of packets wirelessly. https://www.aircrack-ng.org/

## Requirement 
* Wifi Adapter (Support monitor Mode)
* python3
* Library of python: os, sys, subprocess, time, threading, random, csv, tkinter, time

## How to run WifiJammer:
* python3 WifiJammerGUI.py

## How it works!!
* First enter your wifi adapter name and click on start scan button. It will use airodump-ng tool to scan near by router and near by devices.
* It will show near by router and nearby devices in tabular form and in every row there is a button. If you click on that button it will disconnect that device using aireplay-ng tool.
* You can again click on start scan button for rescanning near by router and devices.
