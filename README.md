# Whisper ONNX models

[OpenAI Whisper](https://github.com/openai/whisper) speech recognition models, exported to to ONNX using the [Whisper ONNX Exporter](https://github.com/echogarden-project/whisper-onnx-exporter) tool.

Each model tarball includes an `encoder.onnx` and `decoder.onnx` model files. They are mainly intended to be used from [Echogarden](https://github.com/echogarden-project/echogarden), but can also be used from other applications.

All models except `large`, `large-v1` and `large-v2` are available. The larger models require a very high amount of memory to export, and cannot be uploaded to GitHub as they go over the 2GB file limit for an individual release file. However, you should be able to export them yourself using the tool.

You can download the tarballs from the repository's 'releases' section.
