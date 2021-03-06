[![CI](https://github.com/AncientCatz/LADB/actions/workflows/build.yml/badge.svg?branch=main&event=push)](https://github.com/AncientCatz/LADB/actions/workflows/build.yml) [![stable release](https://img.shields.io/github/v/release/AncientCatz/LADB.svg?maxAge=3600&label=release)](https://github.com/AncientCatz/LADB/releases)

# Important - Read these points first
- Original repo is https://github.com/tytydraco/LADB
- Credits goes to original repo holder, not to me.
- So, if you have any issue then check first that issue is in official repo or not, You are only allowed to report that issue in official repo.

<a href="https://github.com/AncientCatz/LADB"><img src="/.github/readme-images/LADB-icon.png" width="128px" align="right"/></a>

# LADB
A local ADB shell for Android!

![screenshot of app](./.github/readme-images/preview.png)

# How does it work?
LADB bundles an ADB server within the app libraries. Normally, this server cannot connect to the local device because it requires an active USB connection. However, Android's Wireless ADB Debugging feature allows the server and the client to speak to each other locally.

# Initial Setup:
1. About -> Build Number -> Click 7 times
2. Developer Settings -> Wireless ADB Debugging -> On
3. Developer Settings -> ADB Debugging -> On

# Troubleshooting:
If you encounter "device unauthorized" or "multiple devices connected", try this:
1. Enable Airplane Mode
2. Disconnect any USB devices
3. Kill and restart LADB

Still not working? Try this:
1. Close LADB completely
2. Developer Settings -> Wireless ADB Debugging -> Off
3. Developer Settings -> ADB Debugging -> Off
4. Developer Settings -> Revoke authorizations
5. Reboot
6. Developer Settings -> Wireless ADB Debugging -> On
7. Developer Settings -> ADB Debugging -> On
8. Enable Airplane Mode
9. Open LADB

Still confused? Email to tylernij@gmail.com.
