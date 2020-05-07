# Home Assistant Configuration - MColeman
This is my [Home Assistant](https://home-assistant.io/) configuration. I am currently running HA on [Docker](https://www.docker.com) [Container](https://hub.docker.com/r/homeassistant/home-assistant) on a [Raspberry pi 4](https://raspberrypi.org/products/raspberry-pi-4-model-b).

<div align="center">
<h2> Info </h2>
  <h4>
    <a href="https://github.com/colemamd/homeassistant/commits/master"><img src="https://img.shields.io/github/last-commit/colemamd/homeassistant"> <a href="https://github.com/colemamd/homeassistant/issues"><img src="https://img.shields.io/github/issues-raw/colemamd/homeassistant"></a>
  </h4>
</div>

## Design 
I have one main Lovelace config that I use on my desktop to administer and monitor status throughout the day. Screenshots are posted under [Lovelace](https://github.com/colemamd/homeassistant#lovelace).

I also have three Fire tablets running Fully Kiosk Browser. Two have their own dashboard (as of HA 0.108). One of these is used as a remote control for my main entertainment center. It interfaces with my Harmony Hub. I custom built the interface with heavy inspiration from the [forums](https://community.home-assistant.io/t/apops-home-assistant-setup-and-other-resources/119938). The second tablet is in my bedroom and displays information that I use right before going to bed and upon waking up in the morning. I can check the weather forecast, turn on or off lights, and lock the front door. The third tablet displays my custom alarm panel using [BWAlarm (ak74 edition)](https://github.com/akasma74/Hass-Custom-Alarm). 

Screenshots for each are under [Dashboards](https://github.com/colemamd/homeassistant#dashboards).

### Lovelace
![screenshots/lovelace-security.png](https://github.com/colemamd/homeassistant/blob/master/screenshots/lovelace-security.png)
![screenshots/lovelace-home.png](https://github.com/colemamd/homeassistant/blob/master/screenshots/lovelace-home.png)
![screenshots/lovelace-den.png](https://github.com/colemamd/homeassistant/blob/master/screenshots/lovelace-den.png)
![screenshots/lovelace-living_room.png](https://github.com/colemamd/homeassistant/blob/master/screenshots/lovelace-living_room.png)
![screenshots/lovelace-kitchen.png](https://github.com/colemamd/homeassistant/blob/master/screenshots/lovelace-kitchen.png)
![screenshots/lovelace-outside.png](https://github.com/colemamd/homeassistant/blob/master/screenshots/lovelace-outside.png)
![screenshots/lovelace-environment.png](https://github.com/colemamd/homeassistant/blob/master/screenshots/lovelace-environment.png)
![screenshots/lovelace-sysmon-1.png](https://github.com/colemamd/homeassistant/blob/master/screenshots/lovelace-sysmon-1.png)
![screenshots/lovelace-sysmon-2.png](https://github.com/colemamd/homeassistant/blob/master/screenshots/lovelace-sysmon-2.png)
![screenshots/lovelace-lock-1.png](https://github.com/colemamd/homeassistant/blob/master/screenshots/lovelace-lock-1.png)
![screenshots/lovelace-lock-2.png](https://github.com/colemamd/homeassistant/blob/master/screenshots/lovelace-lock-2.png)

### Dashboards

#### Remote
![screenshots/dashboard-remote-1.png](https://github.com/colemamd/homeassistant/blob/master/screenshots/dashboard-remote-1.png)
This is the display with the entertainment center off. These are buttons that activate and Activity on the Harmony Hub. That second row is a WIP, I just added some quick-select buttons for the kids. 
![screenshots/dashboard-remote-2.png](https://github.com/colemamd/homeassistant/blob/master/screenshots/dashboard-remote-2.png)
This is for watching TV from the cable box. This is a custom-built remote using button-cards.
![screenshots/dashboard-remote-3.png](https://github.com/colemamd/homeassistant/blob/master/screenshots/dashboard-remote-3.png)
This is for watching the Roku. I did have a similar page as the TV, but switched to the Roku Card as that has all the funcionality I needed.

#### Wall Tablet
![screenshots/dashboard-wall-tablet-1.png](https://github.com/colemamd/homeassistant/blob/master/screenshots/dashboard-wall-tablet-1.png)
Weather Forecast Card
![screenshots/dashboard-wall-tablet-2-1.png](https://github.com/colemamd/homeassistant/blob/master/screenshots/dashboard-wall-tablet-2-1.png)
Swiper Card - This is the first card.
![screenshots/dashboard-wall-tablet-2-2.png](https://github.com/colemamd/homeassistant/blob/master/screenshots/dashboard-wall-tablet-2-2.png)
Swiper Card - This is the third card. 
![screenshots/dashboard-wall-tablet-3.png](https://github.com/colemamd/homeassistant/blob/master/screenshots/dashboard-wall-tablet-3.png)
Security view