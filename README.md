# HGV Satnav app

Releases of the HGV Satnav Android app: an offline UK truck satnav. This repository holds only the
installable APK and a small `version.json` the app reads to update itself; there is no code here.

## Install

1. On an Android phone (Android 10 or newer, 64-bit), open the
   [latest release](https://github.com/CaptainChunck/hgv-satnav-app/releases/latest) and tap
   `HgvSatnav.apk`.
2. Open the download and allow installing from your browser or Files app when Android asks. If
   Play Protect says it does not recognise the app, tap **More details > Install anyway**.
3. Open **HGV Satnav**. It downloads its UK map data (about 4.8 GB) by itself on Wi-Fi from
   [hgv-satnav-data](https://github.com/CaptainChunck/hgv-satnav-data).

## Updates

The app checks this repository once a day on Wi-Fi. When a newer version has downloaded it asks
**Install now** or **Remind me later**, and never while you are navigating a route.

## Safety

Do not use the app while driving. Always obey road signs: map data can be incomplete or out of
date, and a missing warning does not mean a road is safe.

Map data © OpenStreetMap contributors (ODbL); see the data repository for all credits.
