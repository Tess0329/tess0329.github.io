---
title: StreamPhone Privacy Policy
---

# StreamPhone Privacy Policy

Effective: 2026-11-24 · Operator: Tess0329 · Contact: jts112804@gmail.com

StreamPhone turns an Android phone into a control screen for a Windows PC on the same local network. The StreamPhone operator does not create user accounts and does not send data created by the app to the operator's servers. Ads and payments are handled by Google (see below).

## Information stored on the phone

| Information | Purpose | Retention |
| --- | --- | --- |
| Registered PC's address, certificate fingerprint, and access token | Reconnect only to the registered PC. | Stored encrypted in the app's storage on the phone. Removed when you disconnect the PC or uninstall the app. |
| Display, theme, and language settings, last chosen profile, Premium purchase status | Keep your preferences. | Stored only on the phone and excluded from automatic backup. |

## Information exchanged with the PC

The phone communicates with the registered PC on the same local network over TLS encryption. It exchanges the control screen layout, commands, touchpad and keyboard input, streaming and audio status, the phone's screen size, and Premium status (for the profile limit). This traffic does not pass through any operator server on the internet.

## Permissions

- **Camera**: Used only to scan the pairing QR code on the PC screen. Photos and videos are not saved or sent.
- **Internet, network state, keep awake**: Used only to keep the connection with the PC on the same network.
- Location permission is not requested.

## Ads and Premium purchase

The free app shows a Google AdMob banner ad below the control screen. To show ads, Google may collect and process the advertising ID, device information (model, OS version, language), approximate location (based on IP address), and ad view and click information. In regions where consent is required, the app asks for consent before showing ads and turns off personalized ads according to your choice. Google's processing follows the [Google Privacy Policy](https://policies.google.com/privacy) and [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites).

"Premium" (no ads, unlimited profiles) is purchased through Google Play billing. Payment information is handled by Google; the app only checks whether you have purchased it and stores that on the phone.

## Windows app

The Windows app stores the control screen layout, phone registration, and OBS/Twitch connection information in the PC's Windows user folder. When you connect Twitch, the Windows app communicates directly with Twitch. This information is not sent to the operator.

## Update checks

To check for new versions, the Windows app requests the latest version information from GitHub (`api.github.com`) and, if there is a new version, downloads the installer from GitHub. The app version and the PC's IP address are sent to GitHub in the process. GitHub's processing follows the GitHub Privacy Statement.

## Deleting data

Disconnecting the PC in the phone app or uninstalling the app removes the information on the phone. On Windows, disconnect the phone, uninstall the app, and delete the `%LOCALAPPDATA%\StreamPhone` folder to remove the information on the PC. The operator keeps no user information.

## Changes

If this policy changes, the effective date on this page will be updated. The Korean version is the original; if versions differ, the Korean version prevails.
