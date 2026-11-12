# Sand Dissolve

Turn your webcam image into drifting particles, then bring it back together.

[Live demo ↗](https://michmich02.github.io/sand-dissolve/) · [Michelle Guan](https://github.com/michmich02)

## Try it

Allow camera access and show one open hand to trigger the dissolve. Move your hand to influence the particles, spread two hands apart to scatter them, or pinch to accelerate their return.

## How it works

Canvas 2D samples the webcam image into colored particles. Hand openness, pinch distance, velocity, and two-hand separation change the forces applied to those particles.

**Stack:** JavaScript, Canvas 2D, MediaPipe Hands.

The camera setup, gesture detection, particle simulation, and rendering are all in [index.html](index.html).

## Run locally

From the repository root:

```sh
python3 -m http.server 8000 --directory docs
```

Open [localhost:8000](http://localhost:8000). Use localhost or HTTPS for camera access. Tracking models and CDN scripts need an internet connection.
