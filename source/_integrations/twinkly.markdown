---
title: Twinkly
description: Instructions on how to integrate Twinkly LED string to Home Assistant.
ha_category:
  - Light
ha_release: 0.119
ha_config_flow: true
ha_domain: twinkly
ha_iot_class: Local pull
---

The Twinkly integration allows you to control [Twinkly](https://twinkly.com/) LED string from Home Assistant.

The Twinkly devices does not store the effects locally, they are instead re-sent from the Twinkly application each time.
This means that this integration does not support to change the LED string effect.
It only supports to configure the brightness and to turn the device on and off.

## Configuration

You can setup this integration from the Home Assistant user interface:

1. In Home Assistant, go to **Configuration > Integrations**.
1. At the bottom right, click on the **+** button.
1. In the list select the **Twinkly** integration.
1. Configure the host (or IP address) of your twinkly device.

   _If configured using an IP address, on your router / DHCP, you should assign a static IP to your Twinkly device._

