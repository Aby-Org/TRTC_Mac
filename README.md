# TRTC SDK

_[简体中文](README-zh_CN.md) | English_
## Overview

Leveraging Tencent's many years of experience in network and audio/video technologies, Tencent Real-Time Communication (TRTC) offers solutions for group audio/video calls and low-latency interactive live streaming. With TRTC, you can quickly develop cost-effective, low-latency, and high-quality interactive audio/video services. [Learn more](https://www.tencentcloud.com/document/product/647/35078).

> We offer SDKs for web, Android, iOS, macOS, Windows, Flutter, WeChat Mini Program, and [other mainstream platforms](https://github.com/LiteAVSDK?q=TRTC_&type=all&sort=).



## Changelog
### Version 10.8 @ 2022 10.31

**New features**

- All platforms: Added scratch sound effects to provide a more comprehensive online karaoke experience, see: TXAudioEffectManager.[setMusicScratchSpeedRate](https://cloud.tencent.com/document/product/647/79623#314ea310a5f8f3a7c2d51599a47a4c99).

**Function optimization**

- Android: Optimize the video decoding startup speed, effectively improve the screen opening speed in seconds, the fastest can reach 50ms.
- All platforms: Optimize the accuracy of NTP time, see: TXLiveBase.updateNetworkTime.

**Bug fixes**

- All platforms: In a specific scene (no audio and video upstream) [Mixed Streaming Robot](https://cloud.tencent.com/document/product/647/79626#ff59c8b94f588385a0ed3b39f6b6184a) In the TRTC room scene, the occasional occurrence Pull stream exceptions and callback errors.
- All platforms: Fixed the occasional audio and video upload failure due to network type changes when the audience switches roles after entering the room.
- All platforms: Fixed the problem that the sound quality switch does not take effect during the disconnection and reconnection process.
- All platforms: Fixed the occasional uplink silent problem during disconnection and reconnection.
- Android & iOS: Fixed an issue where the last video frame would be removed when calling muteRemoteVideoStream.

For the release notes of earlier versions, click [More](https://www.tencentcloud.com/document/product/647/39426).


## Contact Us
- If you have questions, see [FAQs](https://www.tencentcloud.com/document/product/647/36057).

- To learn about how the TRTC SDK can be used in different scenarios, see [Sample Code](https://www.tencentcloud.com/document/product/647/42963).

- For complete API documentation, see [SDK API Documentation](https://www.tencentcloud.com/document/product/647/35119).

- Communication & Feedback   
Welcome to join our Telegram Group to communicate with our professional engineers! We are more than happy to hear from you~
Click to join: [https://t.me/+EPk6TMZEZMM5OGY1](https://t.me/+EPk6TMZEZMM5OGY1)   
Or scan the QR code   
  <img src="https://qcloudimg.tencent-cloud.cn/raw/79cbfd13877704ff6e17f30de09002dd.jpg" width="300px">    
