# SenseVoiceSmall model attribution

- Model name: **SenseVoiceSmall** (retain this model name when redistributing).
- Original model authors/project: FunAudioLLM / Alibaba Group, `iic/SenseVoiceSmall`.
- Runtime conversion: sherpa-onnx, release artifact dated `2024-07-17`.
- Packaged variant: `model.int8.onnx` (INT8), with the matching `tokens.txt`.
- Languages: Mandarin Chinese (`zh`), Cantonese (`yue`), English (`en`), Japanese (`ja`), Korean (`ko`).
- Original model card: https://www.modelscope.cn/models/iic/SenseVoiceSmall
- Runtime release: https://github.com/k2-fsa/sherpa-onnx/releases/tag/asr-models
- Model license: see the bundled upstream `LICENSE` pointer and the current FunASR model-license terms: https://github.com/modelscope/FunASR/blob/main/MODEL_LICENSE

The FunASR repository states that pretrained weights are licensed separately from the toolkit source; the SenseVoice model card's license controls the weights. Do not infer that the runtime's MIT license applies to the model weights.

The model license requires attribution to the source/author and retention of the model name. The runtime project's license is separate from the model-weight license. Review the current upstream model card and license before publishing or redistributing an APK containing the weights.