
  If you wanna use current working version, use below donate button (minimum $5). 
  Please write an issue , if you have any problem to use it.

[![Donate](https://img.shields.io/badge/Donate-PayPal-ff69b4.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=C6BU555NMQJD6)

![DPS](https://image.ibb.co/mpSFny/dps.jpg)

## Introduction

Tera DPS monitor.(TDM)

Internal/External dps UI

For those who have a problem to see dps in RAID

For those who have a problem with reset data upon dying

For those who have a lag when you press skill log analysis

## Prerequisite

- nodejs  [here](https://nodejs.org/en/)
- CaaliTeraProxy

## Install

1. Download the TDM via clicking in the button `Clone or Download` and then on `Download Zip`.

2. Uncompress TDM,

   place the resulting folder in `Tera-proxy\mods\`

3. Double click on the file npm_install.bat in TDM folder

4. Set region in config.json

## Optional - module manager ui (for dev)

   module manager [manager](https://github.com/Mathicha/manager)

## Functions

- Enraged notifier
- Notify high damage on screen with skill image and number
- DPS history records(circular history: max 30)
- Simple skill log and analysis
- rank system (The system is unstable because poor network and server system - arm processor )

## Usage

- Type "!dps u" if you want to open UI or reload ui
- If you don't want the dps meter to pop up, press NoPupup or ExtUi. (X button on title is not the same)
- You can automate party leaving message by setting party_leaving_msg in config.json. Then press LeaveParty button.
- To whisper the lastest/records dps to a user, type one's name in the input then press the button

## Credits

Bluehole Studio

Meishu,Pinkipi,Caali

GIO/neowutran - for monster data, class image

