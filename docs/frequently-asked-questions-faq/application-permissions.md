---
layout: default
title: Application permissions
nav_order: 9
has_toc: false
parent: Frequently asked questions (FAQ)
permalink: /frequently-asked-questions-faq/application-permissions
---

# Application permissions
{: .no_toc }

1. TOC
{:toc}

---

## List of permission
For the purposes of 100% usage of the app, the HR application requires these permissions:
- **Internet/Access network state/Access wifi state** - check, if the connection with the internet is available, running or disconnected, and for updating mechanism of the users
- **Get accounts** - during sending log report, list of added google accounts will be provided as a "Sender" for the [**Report the problem**]({{site.baseurl}}{% link docs/troubleshooting/report-your-problem.md %}) functionality
- **Install shortcut** - once the application is installed from the [Google Play link]({{site.baseurl}}{% link docs/getting-started/how-to-install-the-application.md %})
- **Read/Write external storage** - this permission is used for local backup of the settings, which are set up in the settings section for the user
- **Wake lock** - for the purpose of long-running background services

Optional permissions:
- **Camera module** - front or back camera is needed (depending on the account setting), for purposes of taking a photo during clock-in/out of the user

## First installation
During the logging first time on the login screen, the user will be prompted to **Accept Read/Write external storage** and **Camera permission** ([usage](#list-of-permission)). Once the user accepts this permission, he will be logged in. _This process is only one-time_, he must repeat it only when <span class="text-red-200">_the application was uninstalled and installed again_</span> or when the <span class="text-red-200">_application cache was deleted_</span>.

{% include img_tablet.html name="faq_application_permissions_1.png" %}