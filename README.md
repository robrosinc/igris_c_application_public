# IGRIS-C Application

Android application for operating the IGRIS-C humanoid robot.

This repository only hosts release builds. Each robot software release has a
matching tag here.

## Download

Open [Releases](../../releases) and download the `.apk` attached to the
release that matches your robot software version.

## Install

1. Copy the `.apk` to the Android tablet.
2. Open the file on the tablet and allow installation from this source when
   Android asks.
3. If an older version is installed, the new one replaces it and keeps its
   settings.

Alternatively, with the tablet connected over USB and USB debugging enabled:

```bash
adb install -r igris_c_application_prod_<version>.apk
```
