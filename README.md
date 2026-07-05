# Frame Puzzle

A hand-gesture-controlled puzzle game using your webcam and MediaPipe.

Frame a scene with both hands (pinch), solve the 3×3 puzzle by dragging pieces with pinch gestures, then fist to save. Captures build up in a film strip gallery! download the strip when it's full.

## How it works

1. **Frame** — Pinch with both hands to define a capture area. Hold for 3 seconds.
2. **Capture** — A photobooth-style snapshot (B&W, high contrast, film grain) is taken.
3. **Solve** — The image is shuffled into 9 tiles. Pinch a tile and drag it to its correct position.
4. **Save** — Make a fist to save the completed puzzle. The tiles shatter and the result lands in the film strip.
5. **Strip** — Up to 3 captures per strip. Download the full strip as PNG or reset.

## Run locally

```bash
npx serve .
```

Open the URL shown in your terminal. Chrome or Edge recommended (requires WebGL for MediaPipe).

## Tech

- [MediaPipe HandLandmarker](https://developers.google.com/mediapipe/solutions/vision/hand_landmarker) — hand tracking
- Vanilla JS (ES modules) — no framework
- CSS custom properties — theming

made by talha
