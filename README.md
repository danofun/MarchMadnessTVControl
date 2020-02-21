# March Madness TV Control
An PVR Kodi controller for when you want to simultaneously watch 4 televisions. You know, during March Madness! Uses bootstrap and websocket to control 4 separate Kodi instances and is formatted for use on an iPad.

![Screenshot](/assets/img/screenshot.png)

## Setup
1. clone the code and use with a webserver (i.e. nginx)
1. Set the variables (Kodi IP addresses, PVR channels, and colors) at the beginning of the script on index.html

## Features
1. Pulls the data independently from all 4 Kodi instances
1. Assumes the 4 desired channel names are the same for each Kodi instance
1. Pulls channel data, EPG data, logos, active status, and volume information
1. It's March Madness so we don't want to watch any game on more than 1 TV! If a channel is chosen that is already active on another TV, those two TVs swap channels

## Controls
1. Press a channel logo or EPG data to play that channel
1. Press the blue box above or below a TV to listen to that TV
1. Press the center logo to mute all TVs
1. Press and hold the center logo to stop playback on all TVs and return their Kodi volumes to 100%
1. Volume up and volume down buttons control the unmuted TV

Forks and pull requests are welcome!