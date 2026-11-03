# Kokoro 82M ONNX assets

- Source: https://huggingface.co/soniqo/Kokoro-82M-ONNX
- Immutable revision: `b561586381f1b212a8d6bd2a46483e04f54f4ebf`
- License declared by the model repository: Apache-2.0
- Supported languages advertised by the model bundle: English, French, Spanish, Italian, Portuguese, Hindi, Japanese, and Chinese.
- Runtime sample rate: 24 kHz mono PCM16.
- Downloaded model files: 174,878,328 bytes (about 166.8 MiB).
- Checksums: `manifest.json` contains the SHA-256 of every downloaded file.

Only this manifest and this note are packaged in the APK. ONNX weights, external data, dictionaries, and voice embeddings are fetched on first Kokoro use into app-private storage. The downloader pins the revision, resumes partial downloads, and verifies each file's exact size and SHA-256 before marking the model ready.

The upstream G2P implementation consumes space-separated Pinyin for Chinese and kana for Japanese; raw Han characters are not reliably pronounced by its G2P. The app therefore normalizes Chinese Han text to numbered Pinyin and Japanese kanji to kana before synthesis. If the installed Android ICU cannot produce a reading for a rare Japanese proper noun, users should enter its kana reading explicitly.
