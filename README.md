# ABCdabra transcription models

Weight files for on-device transcription in ABCdabra. They are data, not the app.

Release **v1** is immutable. Do not replace or delete its files. A changed file gets a new tag.

| File | Bytes | SHA-256 |
|---|---:|---|
| `ggml-small-q5_1.bin` | 190085487 | `ae85e4a935d7a567bd102fe55afc16bb595bdb618e11b2fc7591bc08120411bb` |
| `ggml-silero-v6.2.0.bin` | 885098 | `2aa269b785eeb53a82983a20501ddf7c1d9c48e33ab63a41391ac6c9f7fb6987` |

Pinned download URLs:

- https://github.com/trytos/abcdabra-models/releases/download/v1/ggml-small-q5_1.bin
- https://github.com/trytos/abcdabra-models/releases/download/v1/ggml-silero-v6.2.0.bin

`ggml-small-q5_1.bin` is the multilingual Whisper small model, quantized q5_1, converted by [whisper.cpp](https://github.com/ggml-org/whisper.cpp). The original weights are OpenAI Whisper. Both are MIT.

`ggml-silero-v6.2.0.bin` is Silero VAD v6.2.0, MIT, from [ggml-org/whisper-vad](https://huggingface.co/ggml-org/whisper-vad).

The app checks the size and the SHA-256 above before it keeps a download.
