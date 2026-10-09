# Sand Dissolve

> A gesture-controlled particle transformation.

[**View live demo →**](https://michmich02.github.io/sand-dissolve/)

## Overview

Sand Dissolve explores touch without a screen. Hand movement breaks a visual field into drifting particles, creating a direct connection between physical motion and a delicate digital material.

## Interaction

- Allow camera access.
- Place a hand inside the camera frame.
- Move through the scene to disturb and dissolve the particles.

## Built with

`JavaScript` · `MediaPipe` · `Canvas` · `Particle systems`

## Run locally

```sh
python3 -m http.server 8000 --directory docs
```

Open [http://localhost:8000](http://localhost:8000) in a desktop browser. Camera and microphone APIs require localhost or HTTPS; external models and CDN dependencies require an internet connection.

## Design notes

- Immediate visual feedback keeps the gesture-to-effect relationship legible.
- The experience is designed as a focused, full-screen interaction.
- Processing happens in the browser; camera and microphone streams are not uploaded by this project.
