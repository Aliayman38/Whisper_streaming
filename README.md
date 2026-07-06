## Key Features
* **Ultra-Low Latency:** Optimized using `faster-whisper` and `float16` quantization for fast inference.
* **Rolling Audio Window:** Implements a 3-second moving buffer mechanism to preserve speech context during continuous streaming.
* **Seamless Client-Server Integration:** Bridges client-side browser microphone input (Web Audio API) with backend Python inference.

## Target Environment
* **Platform:** Google Colab (with T4 GPU or higher enabled)
* **Integration:** Utilizes Colab's native `google.colab.output` kernel bridge for safe, cross-origin browser microphone streaming without complex WebSocket configuration.
