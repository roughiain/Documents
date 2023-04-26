---
tags: [Security]
title: Security Cameras
created: '2023-04-26'
modified: '2023-04-26'
---

# Security Cameras

## Hik Vision PVR Camera

**IP Address**

`192.168.0.161`

**Streams:**
* High Quality: `rtsp://{Ip of DVR}/ISAPI/Streaming/channels/{camera_number}01/`
  * videoCodecType: `H.264`
  * videoResolutionWidth: `960`
  * videoResolutionHeight: `1080`
  * videoQualityControlType: `VBR`
  * fixedQuality: `60`
  * vbrUpperCap: `2048`
  * vbrLowerCap: `32`
  * maxFrameRate: `0`
  * snapShotImageType: `JPEG`
  * SmartCodec : `Enabled`
* Low Quality: `rtsp://{Ip of DVR}/ISAPI/Streaming/channels/{camera_number}02/`
  * videoCodecType: `H.264`
  * videoResolutionWidth: `352`
  * videoResolutionHeight: `288`
  * videoQualityControlType: `VBR`
  * fixedQuality: `60`
  * vbrUpperCap: `512`
  * vbrLowerCap: `32`
  * maxFrameRate: `0`
  * snapShotImageType: `JPEG`
  * SmartCodec : `false`


  **SnapShot:** 

  `http://{Ip of DVR}/ISAPI/Streaming/channels/{camera_number}01/picture`