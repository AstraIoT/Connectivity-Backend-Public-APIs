---
tags: [APIs introduction]
---

# Overview

This repository contains information about the Astra IoT APIs. Each API is divided into a different section as you can see on the panel on the left. There are 5 different APIs, for the time being:

* **Astra API**: Performs Astra-specific functions like Driver ID.
* **Auth API**: Authenticates your requests. If you are accessing the backend through OAuth2, you have to go through this API to obtain an authorization token first.
* **Devices API**: Manages your devices. This includes sending raw commands to them, obtaining their latest reports, querying them, configuring webhooks for when certain events occur, etc.
* **Geofences API**: Configure geofences and webhooks that will notify you when enter or exit events happen.
* **Vehicles API**: The vehicles API is a generalised & simplified down version of the Astra API, where devices are treated as vehicles. All typical operations that you would perform on a fleet of vehicles are implemented here (power on, power off, open topcase, de/activate blinkers, de/activate horn...)