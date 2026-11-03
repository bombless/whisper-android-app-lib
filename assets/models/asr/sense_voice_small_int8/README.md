# SenseVoice Small Int8

中文、英语、日语、韩语和粤语多语言语音识别模型，适用于 16 kHz 音频输入。

## 模型信息

- 模型类型：Offline SenseVoice
- 语言：中文、英语、日语、韩语、粤语
- 采样率：16 kHz
- 量化：INT8
- 文件：`model.int8.onnx`、`tokens.txt`

## 上游来源

- 原始模型项目：[`FunAudioLLM/SenseVoice`](https://github.com/FunAudioLLM/SenseVoice)
- 上游模型仓库：[`iic/SenseVoiceSmall`](https://modelscope.cn/models/iic/SenseVoiceSmall)
- 本模型文件对应的上游整理版本：`2024-07-17`
- sherpa-onnx 发布地址：<https://github.com/k2-fsa/sherpa-onnx/releases/download/asr-models/sherpa-onnx-sense-voice-zh-en-ja-ko-yue-int8-2024-07-17.tar.bz2>
- 上游制品 SHA256：`7d1efa2138a65b0b488df37f8b89e3d91a60676e416f515b952358d83dfd347e`
- 上游制品大小：`163,002,883` bytes

本仓库发布的是上游模型的 ONNX INT8 整理版本，不是新的训练成果。模型权重、词表和原始项目的版权归其各自权利人所有。

## 许可证与再分发

请以 SenseVoice 原始模型仓库、sherpa-onnx 发布页及随附的 LICENSE/NOTICE 为准。推理项目的许可证不当然等于模型权重的许可证；公开上传前应确认模型权重和词表允许第三方平台分发，并保留必要的版权、NOTICE、归属文本和原始链接。未完成核验前，不应擅自声明 Apache-2.0 或其他许可证。

## 完整性

下载后请核对文件大小和 SHA256。正式使用时应固定仓库版本或 commit，不建议依赖可变的默认分支。
