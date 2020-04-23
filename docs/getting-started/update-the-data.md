---
layout: default
title: Update the data
nav_order: 5
has_children: true
has_toc: false
parent: Getting Started
permalink: /getting-started/update-the-data
---

# Update the data
{: .no_toc }

1. TOC
{:toc}

---

## Description
The Kitchen application contains the logic, that every 30 seconds, the update mechanism contacts the server and updates the orders and the meals to the latest one. But the cook has also an option for manually updating the **Kitchen screen**.

## How to manually update
There are 2 ways, how to manually update the data:
1. If the **Kitchen screen** is not displaying any orders and meals, then the _empty status_ is displayed. The cook just needs to click on the blue button <span class="text-blue-100">**RELOAD ORDERS**</span> and the device will try to contact the server and reload the screen.
2. There may be situations where there are orders and meals on the screen. In this case, the blue button <span class="text-blue-100">**RELOAD ORDERS**</span> is not visible. The only way, how to update the data manually is with the mechanism called. **pulled to refresh** - this means, that in the area of orders you need to **swipe down {% include icon.html name="arrow_downward" %} with a finger** till the refresh icon <span class="text-orange-200">{% include icon.html name="refresh" %}</span> in the center top of the screen will display, then release the finger and the application will trigger manually update (indicating by rotating refresh icon).

{% include img_tablet.html name="update_data_1.png" %}

{% include img_tablet.html name="update_data_2.png" %}

## Manually updating specific type of data
The list of currently available option for updating the specific type of data in the application:
1. **Update account settings** - account settings that only the account administrator can change
1. **Update users** - a list of couriers with current status and availability information
1. **Update restaurants** - a list of restaurants the user has permission work with

{% include img_tablet.html name="settings_update_1.png" %}

{% include img_tablet.html name="settings_update_2.png" %}