# WebRTC 16KB Build

This repository builds WebRTC Android libraries with 16KB page alignment for Android 15+ compatibility.

## Usage

1. Go to **Actions** tab
2. Click **"Build WebRTC 16KB"**
3. Click **"Run workflow"**
4. Wait 4-8 hours
5. Download the `webrtc-16kb-all-abis` artifact

## Output

The build produces 4 `.so` files:
- `arm64-v8a/libjingle_peerconnection_so.so` (16KB aligned)
- `armeabi-v7a/libjingle_peerconnection_so.so`
- `x86_64/libjingle_peerconnection_so.so` (16KB aligned)
- `x86/libjingle_peerconnection_so.so`

Copy these to your Android project's `jniLibs` folder.
