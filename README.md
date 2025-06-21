# sd-edge-tts
Speech dispatcher module that uses Microsoft Edge's TTS service as backend.

## Dependencies

1. **speech-dispatcher** package installed and properly configured (socket activation enabled, etc).
2. **mpv** installed (used by default as the backend to play audio).
3. [**edge-tts**](https://github.com/rany2/edge-tts) Python module installed and available in `PATH`.

## Installation

1. Clone or download this repository.  
2. Copy the `speech-dispatcher` folder into your home config directory.
3. Restart Speech Dispatcher (kill it, then start again).

Once the folder is in ~/.config, the module should start working immediately.

## Verification
- Open Firefox, enable Reader Mode on any article, and check that TTS playback works.
- Or run a test in the terminal:

    ```bash
    spd-say "Hello, this is a test using Microsoft Edge TTS."
    ```
And you should hear the text spoken.
