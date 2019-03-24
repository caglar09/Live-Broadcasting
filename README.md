React native live streaming using RTMP.


## Teachnology using

Using react-native-nodemediaclient. Connect with RTMP server

- [RTMP Server](https://github.com/sieuhuflit/live-tream-rtmp-server) - Node media server using NodeJS
  Server

## Config

- Config the SocketIO ip address and RTMP server path, change to your IP_ADDRESS, PORT, and PATH_LIVE_STREAM

```js
const socketIOIP = 'http://IP_ADDRESS:PORT';
const rtmpPath = 'rtmp://IP_ADDRESS/PATH_LIVE_STREAM/';
```

## Install package

```bash
npm install
```

## Running the App

### iOS

```bash
react-native run-ios
```

### Android

```bash
react-native run-android
```
