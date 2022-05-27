# Video SDK No Code Prebuilt App.
THIS REPO is DEPRECATED. Please refer to https://github.com/videosdk-live/videosdk-rtc-prebuilt-examples

## What is it?

This code sample demonstrates a one-to-one and group video call application built with [Video SDK RTC Prebuilt SDK](https://docs.videosdk.live/docs/guide/prebuilt-video-and-audio-calling/getting-started) and [Video SDK RTC JS SDK](https://docs.videosdk.live/docs/realtime-communication/sdk-reference/javascript-sdk/setup)

- Built for serverless video calling experience.
- Scale it upto 5,000 participants with low code.
- 10,000 minutes free on monthly basis.
- Inbuilt video and audio quality optimization.
- Inbuilt chat poll, whiteboard, Q and A support.


## Features

- [x] Completely Low code and serverless.
- [x] Video API with real-time audio, video and data streams
- [x] 5,000+ participants support
- [x] Chat support with rich media.
- [x] Screen sharing with HD and Full HD.
- [x] Play realtime video in meeting
- [x] Connect it with social media such as Facebook, Youtube etc (RTMP out support).
- [x] Intelligent speaker switch
- [x] Record your meetings on cloud
- [x] Inbuilt support of whiteboard, poll and Q & A.
- [x] Customize UI as per your needs.

## Browser Support

Visit our official guide for [Browser Support](https://docs.videosdk.live/docs/realtime-communication/see-also/device-browser-support)

## Prerequisites

- Web browser

## Getting started

1. Clone the repo

   ```sh
   git clone https://github.com/videosdk-live/videosdk-rtc-js-prebuilt-embedded-example.git
   cd videosdk-rtc-js-prebuilt-embedded-example
   ```

2. Update api key generated from [app.videosdk.live](https://app.videosdk.live/settings/api-keys) in `index.html`.

   ```javascript
   // ...

   // Set apikey, meetingId and participant name
   const apiKey = "<API KEY>"; // generated from app.videosdk.live
   const meetingId = "milkyway";
   const name = "John Doe";

   // ...
   ```

3. Install `live-server` or any other http server if you don't already have one.

   ```sh
   npm install -g live-server
   live-server
   ```

Visit, [https://www.videosdk.live/](https://www.videosdk.live/) to generate API key.

Related

- [Video SDK Prebuilt IOS SDK](https://github.com/videosdk-live/videosdk-rtc-ios-prebuilt-webview-example)
- [Video SDK Prebuilt ANDROID SDK](https://github.com/videosdk-live/videosdk-rtc-android-prebuilt-webview-example)
- [Video SDK Prebuilt REACT SDK](https://github.com/videosdk-live/videosdk-rtc-react-prebuilt-example)
- [Video SDK Prebuilt ANGULAR SDK](https://github.com/videosdk-live/videosdk-rtc-angular-prebuilt-example)
- [Video SDK Prebuilt VUE SDK](https://github.com/videosdk-live/videosdk-rtc-vue-prebuilt-example)
- [Video SDK Prebuilt React Native SDK](https://github.com/videosdk-live/videosdk-rtc-react-native-prebuilt-ui)
