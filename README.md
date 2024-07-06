# NDIMediaReceiver sample for BugReport

This project is an example project to reproduce the problem of missing sound
in NDI SDK for UnrealEngine (3.4 to 3.6) for UE5.3.

- Version 3.3 for UE5.2 seems working well with sound.
- Version 3.4 for UE5.3 has red square blinking issue and that with no sound.
- Version 3.5 and 3.6 for UE5.3 has the issue with no sound.

## Reproduction steps

### Download NDI SDK for UE

- Please get NDI SDK for UnrealEngine from https://ndi.video/for-developers/ndi-unreal-engine-sdk/ and install.
- Copy NDIIO folder from C:\Program Files\NDI\NDI SDK for Unreal Engine\PluginBuilds\UE_5.3

### Download VLC and NDI Tools

- Please get VLC MediaPlayer https://www.videolan.org/vlc/index.html and install.
- Please get NDI Tools from https://ndi.video/tools/download/ and install.
  (NDI plugin for VLC will be installed)

### Launch UE Editor

- Double click at NDIReceiver53NDI6.uproject.
- Play in Editor.

### Play any movie for NDI

- Launch VLC, open Tools/Preference.
- Open Video settings, change Display/Output to NDI video output.
- Open Audio settings, change Output/Output module to NDI audio output.
- Open any movie and play.
