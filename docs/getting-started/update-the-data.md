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
The HR application contains the logic, that during every displaying the screen, the update mechanism contacts the server and updates the users. But the user has also an option for manually updating the **Clocked-in users screen**.

## How to manually update
If the **Clocked-in users screen** is not displaying any users, then the _empty status_ is displayed. The only way, how to update the data manually is with the mechanism called. **pulled to refresh** - this means, that in the area of orders you need to **swipe down {% include icon.html name="arrow_downward" %} with a finger** till the refresh icon <span class="text-blue-100">{% include icon.html name="refresh" %}</span> in the center top of the screen will display, then release the finger and the application will trigger manually update (indicating by rotating refresh icon).

{% include img_tablet.html name="update_data_1.png" %}

{% include img_tablet.html name="update_data_2.png" %}

## Manually updating specific type of data
The list of currently available option for updating the specific type of data in the application:
1. **Update account settings** - account settings that only the account administrator can change
1. **Update users** - a list of users with current status
1. **Update restaurants** - a list of restaurants the user has permission work with

{% include img_tablet.html name="settings_update_1.png" %}

{% include img_tablet.html name="settings_update_2.png" %}