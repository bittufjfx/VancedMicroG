# Vanced MicroG

![Build Status](https://github.com/YTVanced/VancedMicroG/workflows/Debug%20APK%20Builder/badge.svg)
[![Github All Releases](https://img.shields.io/github/downloads/YTVanced/VancedMicroG/total.svg)]() [![Github All Releases](https://img.shields.io/github/release/YTVanced/VancedMicroG.svg)]() 

microG GmsCore is a FLOSS (Free/Libre Open Source Software) framework to allow applications designed for Google Play Services to run on systems, where Play Services is not available.

This fork tweaks MicroG to be usable by applications that require Google authentication such as Youtube Vanced.

## Notable changes

- No longer a system app
- Package name changed from `com.google.android.gms` to `com.mgoogle.android.gms` to support installation alongside the official MicroG
- Removed unnecessary features:
  - Ads
  - Analytics
  - Car
  - Droidguard
  - Feedback
  - Firebase
  - Games
  - Location
  - Maps
  - Recovery
  - SafetyNet
  - Self-Check
  - Search
  - TapAndPay
  - Wallet
  - Wear-Api
- Removed all permissions, as none are required for Google authentication
