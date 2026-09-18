# whisper-android-app-lib

Frozen model and Android runtime payload for Snapdragon Voice Lab.

```text
assets/models/          APK assets/models/...
runtime/jniLibs/        arm64-v8a native libraries
runtime/*.aar           local Sherpa Android dependencies
runtime/voiceai_sdk/    optional VoiceAI SDK payload
```

The app repository consumes this repository as its `lib` Git submodule. Keep
the paths under `assets/models` stable because the application opens model
files using `models/...` asset paths at runtime.
