# Home Assistant Addons: Silas Hansens repository

This repository contains a collection of custom Home Assistant addons that I have developed,
plus adopted copies of upstream addons that were abandoned but are still in use here.

## Installation

1. Click [here](https://my.home-assistant.io/redirect/supervisor_store/) to open ADD-ON STORE in settings
3. Click "Repositories" in the ... menu (top right)
4. Add the following URL: `https://github.com/silashansen/hass_addons`
5. Click "ADD"
6. Find the add-on you want to install and click "INSTALL"

## Addons

* [Cloudflare DDNS Updater](cloudflare_ddns_updater/DOCS.md) - Automatically updates one or more Cloudflare DNS records with your public IP address.
* [InfluxDB](influxdb/DOCS.md) - **Adopted fork.** Verbatim copy of the Home Assistant Community
  Add-on [`hassio-addons/addon-influxdb`](https://github.com/hassio-addons/addon-influxdb) at tag
  `v5.0.2`, which was archived on 2026-08-28. Pinned to the archived prebuilt image so nothing is
  built on-device. Adopted to keep the add-on attached to a live repository — see
  [its DOCS.md](influxdb/DOCS.md) for the full rationale and the exact diff from upstream.