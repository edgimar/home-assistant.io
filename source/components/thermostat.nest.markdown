---
layout: page
title: "Nest thermostat support"
description: "Instructions how to integrate Nest thermostats within Home Assistant."
date: 2015-03-23 19:59
sidebar: false
comments: false
sharing: true
footer: true
---

<img src='/images/supported_brands/nest_thermostat.png' class='brand pull-right' />
The nest thermostat platform let you control a thermostat from [Nest](https://nest.com).

To set it up, add the following information to your `configuration.yaml` file:

```
thermostat:
  platform: nest
  username: myemail@mydomain.com
  password: mypassword
```

<p class='img'>
  <img src='{{site_root}}/images/screenshots/nest-thermostat-card.png' />
</p>
