# HA DeskLink — Landing Page

Official landing page for **HA DeskLink**, the Home Assistant desktop companion for Windows, Linux & macOS.

Live: https://techflipsi.github.io/ha-desklink/

Source code per platform:
- Windows: https://github.com/TechFlipsi/ha-desklink-windows
- Linux: https://github.com/TechFlipsi/ha-desklink-linux
- macOS: https://github.com/TechFlipsi/ha-desklink-mac

## What is HA DeskLink?

HA DeskLink is a free, open-source desktop application (GPL-3.0) for Windows, Linux and macOS that connects a computer to a Home Assistant smart-home instance in both directions: it displays Home Assistant sensor values (temperatures, energy, lock states, motion) live on the desktop in the taskbar or system tray, and it feeds the computer's own status (CPU load, memory, disk space, uptime) back into Home Assistant as sensor entities. Users can toggle lights, switches and scenes from the tray menu, receive native desktop notifications when automations fire, and optionally view the full dashboard in an embedded WebView. It connects only to the user's own Home Assistant instance over the local network — no browser, no cloud, no subscription.