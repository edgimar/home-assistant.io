---
layout: page
title: "Swiss Public Transport support"
description: "Instructions how to integrate timetable data for travelling in Switzerland within Home Assistant."
date: 2015-06-02 21:45
sidebar: false
comments: false
sharing: true
footer: true
---

<img src='/images/supported_brands/appointment-new.png' class='brand pull-right' />
The swiss public transport sensor will give you the next two departure times from a given location to another one in Switzerland.

The [Stationboard](http://transport.opendata.ch/examples/stationboard.html) website can help to determine the exact name of the start and the end station. With the station names it's necessary to search for the ID of those stations:

http://transport.opendata.ch/v1/locations?query=[Station name]

If the score is 100 ("score":"100" in the response), it is a perfect match. Then add the data to your `configuration.yaml` file as shown in the example:

```yaml
# Example configuration.yaml entry
sensor:
  platform: swiss_public_transport
  from: STATION_ID
  to: STATION_ID

```

The public timetables are coming from [Swiss public transport](http://transport.opendata.ch).
