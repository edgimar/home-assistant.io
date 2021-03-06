---
layout: page
title: "Components"
description: "List of the built-in components of Home Assistant."
date: 2014-12-21 13:35
sidebar: false
comments: false
sharing: true
footer: true
is_homepage: true
---

Components add support for devices, automation and much much more to Home Assistant. The following things are supported out-of-the-box.

## {% linkable_title Entities %}

Entities are things that you want to observe within Home Assistant. Support for these things are provided by the entity components [Light](/components/light.html), [Switch](/components/switch.html), [Thermostat](/components/thermostat.html), [Media player](/components/media_player.html), [Device tracker](/components/device_tracker.html), [Sun](/components/sun.html).

<table>
<tr>
<th colspan='2'>Type</th>
<th>Description</th>
</tr>

<tr>
  <td><a href='/components/light.hue.html'><img src='/images/supported_brands/philips_hue.png' class='brand overview' /></a></td>
  <td><a href='/components/light.hue.html'>Philips Hue</a></td>
  <td>Turn lights on, control brightness and color.</td>
</tr>

<tr>
  <td><a href='/components/sensor.sabnzbd.html'><img src='/images/supported_brands/sabnzbd.png' class='brand overview' /></a></td>
  <td><a href='/components/sensor.sabnzbd.html'>SABnzbd clients</a></td>
  <td>Monitor queue and download speeds.</td>
</tr>

<tr>
  <td><a href='/components/sensor.systemmonitor.html'><img src='/images/supported_brands/utilities-system-monitor.png' class='brand overview' /></a></td>
  <td><a href='/components/sensor.systemmonitor.html'>System Monitor</a></td>
  <td>Track CPU, memory and disk usage on the host machine.</td>
</tr>

<tr>
  <td><a href='/components/thermostat.nest.html'><img src='/images/supported_brands/nest_thermostat.png' class='brand overview' /></a></td>
  <td><a href='/components/thermostat.nest.html'>Nest thermostats</a></td>
  <td>See current temperature and control target temperature and away mode.</td>
</tr>

<tr>
  <td></td>
  <td><a href='/components/thermostat.heat_control.html'>Heat Control</a></td>
  <td>Turn home Assistant into your own thermostat by reading a temperature sensor and controlling a switch connected to a heater.</td>
</tr>

<tr>
  <td><a href='/components/switch.wemo.html'><img src='/images/supported_brands/belkin_wemo.png' class='brand overview' /></a></td>
  <td><a href='/components/switch.wemo.html'>WeMo switches</a></td>
  <td>Control WeMo switches and read the usage statistics from Insight switches.</td>
</tr>

<tr>
  <td><a href='/components/sensor.mysensors.html'><img src='/images/supported_brands/mysensors.png' class='brand overview' /></a></td>
  <td><a href='/components/sensor.mysensors.html'>MySensors</a></td>
  <td>Integrate MySensors sensors.</td>
</tr>

<tr>
  <td><a href='/components/device_tracker.ddwrt.html'><img src='/images/supported_brands/ddwrt.png' class='brand overview' /></a></td>
  <td><a href='/components/device_tracker.ddwrt.html'>DD-WRT routers</a></td>
  <td>Offers presence detection by looking at connected devices.</td>
</tr>

<tr>
  <td><a href='/components/device_tracker.luci.html'><img src='/images/supported_brands/openwrt.png' class='brand overview' /></a></td>
  <td><a href='/components/device_tracker.luci.html'>OpenWRT routers</a></td>
  <td>Offers presence detection by looking at connected devices.</td>
</tr>

<tr>
  <td><a href='/components/device_tracker.netgear.html'><img src='/images/supported_brands/netgear.png' class='brand overview' /></a></td>
  <td><a href='/components/device_tracker.netgear.html'>Netgear routers</a></td>
  <td>Offers presence detection by looking at connected devices.</td>
</tr>

<tr>
  <td><a href='/components/device_tracker.tomato.html'><img src='/images/supported_brands/network-wired-disconnected.png' class='brand overview' /></a></td>
  <td><a href='/components/device_tracker.tomato.html'>Tomato routers</a></td>
  <td>Offers presence detection by looking at connected devices.</td>
</tr>

<tr>
  <td><a href='/components/device_tracker.tplink.html'><img src='/images/supported_brands/tp-link.png' class='brand overview' /></a></td>
  <td><a href='/components/device_tracker.tplink.html'>TP-Link routers</a></td>
  <td>Offers presence detection by looking at connected devices.</td>
</tr>

<tr>
  <td><a href='/components/device_tracker.nmap_scanner.html'><img src='/images/supported_brands/network-workgroup.png' class='brand overview' /></a></td>
  <td><a href='/components/device_tracker.nmap_scanner.html'>NMap network scanning</a></td>
  <td>Offers presence detection by scanning the network for connected devices.</td>
</tr>

<tr>
  <td><a href='/components/sensor.transmission.html'><img src='/images/supported_brands/transmission.png' class='brand overview' /></a></td>
  <td>
    <a href='/components/sensor.transmission.html'>Transmission sensor</a></br>
    <a href='/components/switch.transmission.html'>Transmission switch</a>
  </td>
  <td>Monitor status and download speeds. Change the speed limits.</td>
</tr>

<tr>
  <td><a href='/components/media_player.cast.html'><img src='/images/supported_brands/google_cast.png' class='brand overview' /></a></td>
  <td><a href='/components/media_player.cast.html'>Google Cast devices</a></td>
  <td>Track what is being played and control playback (temporarely disabled awaiting protobuf 3 release).</td>
</tr>

<tr>
  <td><a href='/components/media_player.kodi.html'><img src='/images/supported_brands/kodi.png' class='brand overview' /></a></td>
  <td><a href='/components/media_player.kodi.html'>Kodi</a></td>
  <td>Track what is being played and control playback.</td>
</tr>

<tr>
  <td><a href='/components/media_player.mpd.html'><img src='/images/supported_brands/mpd.png' class='brand overview' /></a></td>
  <td><a href='/components/media_player.mpd.html'>Music Player Daemon (MPD)</a></td>
  <td>Track what is being played and control playback.</td>
</tr>

<tr>
  <td><a href='/components/switch.command_switch.html'><img src='/images/supported_brands/utilities-terminal.png' class='brand overview' /></a></td>
  <td><a href='/components/switch.command_switch.html'>Command line Switch</a></td>
  <td>Switch that issues command line commands when turned on and off.</td>
</tr>

<tr>
  <td><a href='/components/light.limitlessled.html'><img src='/images/supported_brands/dialog-information.png' class='brand overview' /></a></td>
  <td><a href='/components/light.limitlessled.html'>LimitlessLED</a></td>
  <td>Control your LimitlessLED lights.</td>
</tr>

<tr>
  <td><a href='/components/switch.hikvision.html'><img src='/images/supported_brands/hikvision.png' class='brand overview' /></a></td>
  <td><a href='/components/switch.hikvision.html'>Hikvision</a></td>
  <td>Control the motion detection setting on your Hikvision camera.</td>
</tr>

<tr>
  <td><a href='/components/isy994.html'><img src='/images/supported_brands/insteon.png' class='brand overview' /></a></td>
  <td><a href='/components/isy994.html'>Insteon Devices</a></td>
  <td>Insteon devices can be controlled with the ISY994 controller.</td>
</tr>

<tr>
  <td><a href='/components/isy994.html'><img src='/images/supported_brands/x10.gif' class='brand overview' /></a></td>
  <td><a href='/components/isy994.html'>X10 Devices</a></td>
  <td>X10 devices can be controlled with the ISY994 controller.</td>
</tr>

<tr>
  <td><a href='/components/arduino.html'><img src='/images/supported_brands/arduino.png' class='brand overview' /></a></td>
  <td><a href='/components/arduino.html'>Arduino boards</a></td>
  <td>Controls your Arduino's digital pins and read from the analog pins.</td>
</tr>

<tr>
  <td><a href='/components/sensor.efergy.html'><img src='/images/supported_brands/efergy.png' class='brand overview' /></a></td>
  <td><a href='/components/sensor.efergy.html'>Efergy Engage hubs</a></td>
  <td>Monitors home energy use as measured by an Efergy engage hub.</td>
</tr>

<tr>
  <td></td>
  <td><a href='/components/camera.generic.html'>Generic IP cameras</a></td>
  <td>Integrate any IP camera or image url into a camera feed.</td>
</tr>

</table>

<p class='note'>
Support for these devices is provided by the Home Assistant community and not
the manufacturers of these devices.
</p>

## {% linkable_title Organization %}
| Type | Description
| ---- | -----------
| [Group](/components/group.html) | Allows grouping of entities
| [Scene](/components/scene.html) | Allow defining preferred state of a set of entities

## {% linkable_title Hubs %}

Home Assistant integrates with a variety of third party Home Automation hubs and networks. It allows you to control the connected switches, lights and sensors via Home Assistant. Click on the following logos for setup instructions:

[<img src='/images/supported_brands/z-wave.png' class='brand' />](/components/zwave.html)
[<img src='/images/supported_brands/telldus_tellstick.png' class='brand' />](/components/tellstick.html)
[<img src='/images/supported_brands/vera.png' class='brand' />](/components/vera.html)
[<img src='/images/supported_brands/wink.png' class='brand' />](/components/wink.html)
[<img src='/images/supported_brands/universal_devices.png' class='brand' />](/components/isy994.html)
[<img src='/images/supported_brands/modbus.png' class='brand' />](/components/modbus.html)
[<img src='/images/supported_brands/arduino.png' class='brand' />](/components/arduino.html)

<p class='note'>
Support for these devices is provided by the Home Assistant community and not
the manufacturers of these devices.
</p>

## {% linkable_title Services %}

<table>
<tr>
  <td><a href='/components/history.html'><img src='/images/supported_brands/x-office-presentation.png' class='brand overview' /></a></td>
  <td><a href='/components/history.html'>History</a></td>
  <td>Track the state of entities and allow users to browse through history.</td>
</tr>

<tr>
  <td><a href='/components/conversation.html'><img src='/images/supported_brands/system-users.png' class='brand overview' /></a></td>
  <td><a href='/components/conversation.html'>Conversation</a></td>
  <td>Process textual commands like ones received by speech-to-text engines.</td>
</tr>

<tr>
  <td><a href='/components/discovery.html'><img src='/images/supported_brands/system-search.png' class='brand overview' /></a></td>
  <td><a href='/components/discovery.html'>Discovery</a></td>
  <td>Scans the network for supported devices.</td>
</tr>

<tr>
  <td><a href='/components/logbook.html'><img src='/images/supported_brands/accessories-text-editor.png' class='brand overview' /></a></td>
  <td><a href='/components/logbook.html'>Logbook</a></td>
  <td>Provides a logbook-style view on the Entity history.</td>
</tr>

<tr>
  <td><a href='/components/notify.file.html'><img src='/images/supported_brands/text-x-generic.png' class='brand overview' /></a></td>
  <td><a href='/components/notify.file.html'>File</a></td>
  <td>Allow sending messages to a file.</td>
</tr>

<tr>
  <td><a href='/components/notify.nma.html'><img src='/images/supported_brands/nma.png' class='brand overview' /></a></td>
  <td><a href='/components/notify.nma.html'>Notify My Android (NMA)</a></td>
  <td>Allow sending messages using Notify My Android (NMA).</td>
</tr>

<tr>
  <td><a href='/components/notify.instapush.html'><img src='/images/supported_brands/instapush.png' class='brand overview' /></a></td>
  <td><a href='/components/notify.instapush.html'>Instapush</a></td>
  <td>Allow sending messages using Instapush.</td>
</tr>

<tr>
  <td><a href='/components/notify.pushbullet.html'><img src='/images/supported_brands/pushbullet.png' class='brand overview' /></a></td>
  <td><a href='/components/notify.pushbullet.html'>PushBullet</a></td>
  <td>Allow sending messages using PushBullet.</td>
</tr>

<tr>
  <td><a href='/components/notify.pushover.html'><img src='/images/supported_brands/pushover.png' class='brand overview' /></a></td>
  <td><a href='/components/notify.pushover.html'>PushOver</a></td>
  <td>Allow sending messages using PushOver.</td>
</tr>

<tr>
  <td><a href='/components/notify.smtp.html'><img src='/images/supported_brands/smtp.png' class='brand' /></a></td>
  <td><a href='/components/notify.smtp.html'>E-Mail</a></td>
  <td>Allow sending e-mail messages.</td>
</tr>

<tr>
  <td><a href='/components/notify.syslog.html'><img src='/images/supported_brands/applications-system.png' class='brand overview' /></a></td>
  <td><a href='/components/notify.syslog.html'>Syslog</a></td>
  <td>Allow sending messages to a local syslog.</td>
</tr>

<tr>
  <td><a href='/components/notify.xmpp.html'><img src='/images/supported_brands/xmpp.png' class='brand overview' /></a></td>
  <td><a href='/components/notify.xmpp.html'>Jabber (XMPP)</a></td>
  <td>Allow sending messages using Jabber (XMPP).</td>
</tr>

<tr>
  <td><a href='/components/browser.html'><img src='/images/supported_brands/web-browser.png' class='brand overview' /></a></td>
  <td><a href='/components/browser.html'>Browser</a></td>
  <td>Open URLs on the host machine.</td>
</tr>

<tr>
  <td><a href='/components/downloader.html'><img src='/images/supported_brands/emblem-downloads.png' class='brand overview' /></a></td>
  <td><a href='/components/downloader.html'>Downloader</a></td>
  <td>Allows downloading URLs to the host machine.</td>
</tr>

<tr>
  <td><a href='/components/keyboard.html'><img src='/images/supported_brands/input-keyboard.png' class='brand overview' /></a></td>
  <td><a href='/components/keyboard.html'>Keyboard</a></td>
  <td>Simulate key presses on the host machine.</td>
</tr>

<tr>
  <td><a href='/components/sensor.openweathermap.html'><img src='/images/supported_brands/openweathermap.png' class='brand overview' /></a></td>
  <td><a href='/components/sensor.openweathermap.html'>OpenWeatherMap</a></td>
  <td>Display current meteorological data from your location.</td>
</tr>

<tr>
  <td><a href='/components/sensor.forecast.html'><img src='/images/supported_brands/weather-few-clouds.png' class='brand overview' /></a></td>
  <td><a href='/components/sensor.forecast.html'>Forecast.io</a></td>
  <td>Display current meteorological data from your location.</td>
</tr>

<tr>
  <td><a href='/components/sensor.bitcoin.html'><img src='/images/supported_brands/bitcoin.png' class='brand overview' /></a></td>
  <td><a href='/components/sensor.bitcoin.html'>Bitcoin</a></td>
  <td>Display details about the Bitcoin Network and your Blockchain.info online wallet.</td>
</tr>

<tr>
  <td><a href='/components/sensor.swiss_public_transport.html'><img src='/images/supported_brands/appointment-new.png' class='brand overview' /></a></td>
  <td><a href='/components/sensor.swiss_public_transport.html'>Swiss Public Transport</a></td>
  <td>Display timetable data for traveling in Switzerland.</td>
</tr>

<tr>
  <td><a href='/components/sensor.time_date.html'><img src='/images/supported_brands/clock.png' class='brand overview' /></a></td>
  <td><a href='/components/sensor.time_date.html'>Time & Date</a></td>
  <td>Displays the time and the date.</td>
</tr>
</table>

<p class='note'>
Support for these services is provided by the Home Assistant community and not
the service providers.
</p>

## {% linkable_title Automation %}

| Type | Description
| ---- | -----------
| [Automation](/components/automation.html) | Allow for automating service calls when a specific state is met
| [Scheduler](/components/scheduler.html) | Allows for scheduling service calls when sun sets or it is specific time
| [Script](/components/script.html) | Allow user to define scripts to run from within Home Assistant
| [Device sun light trigger](/components/device_sun_light_trigger.html) | Slowly fade in the lights to compensate the setting sun. Also turns on lights when you get home after dark.
| [Simple alarm](/components/simple_alarm.html) | Let the lights blink red when the lights turn on while no one is home.

## {% linkable_title Misc %}

| Type | Description
| ---- | -----------
| [Configurator](/components/configurator.html) | Component used by other components to get configuration from the user.


{% comment %}
{% directory path:components exclude:index %}
  * [{{ file.slug | replace: '_',' ' | capitalize }}]({{ file.slug | prepend: '/components/' | append: '.html' }})
{% enddirectory %}
{% endcomment %}
