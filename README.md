# March Madness TV Control
An PVR Kodi controller for when you want to simultaneously watch 3 televisions. You know, during March Madness! Uses bootstrap and websocket to control 3 separate Kodi instances and is formatted for use on an iPad.

![Screenshot](/assets/img/screenshot.png)

## Setup
1. clone the code and use with a webserver (i.e. nginx)
2. Set the variables (Kodi IP addresses, PVR channels, and colors) at the beginning of the script on index.html

## Features
1. Pulls the data independently from all 3 Kodi instances
2. Assumes the 4 desired channel names are the same for each Kodi instance
3. Pulls channel data, EPG data, logos, active status, and volume information
4. It's live basketball so we don't want to watch any game on more than 1 TV! If a channel is chosen that is already active on another TV, those two TVs swap channels

## Controls
1. Click a channel logo or EPG data to play a channel
2. Click the green box above or below a TV to listen to that TV
3. Click the center logo to mute all TVs
4. Volume up and volume down buttons control all unmuted TVs

## Hidden controls
In the Upcoming Games section
1. Click channel 1 to refresh the page
2. Click channel 3 to set the volume to 100% on all 3 Kodi instances
3. Click channel 4 to stop playback on all 3 Kodi instances

Forks and pull requests are welcome!
