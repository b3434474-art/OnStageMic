# OnStage Mic

A browser-based live microphone monitor that routes microphone audio to your device's speakers.

## Run locally

Open `index.html` from a local web server (microphone permission requires a secure context such as HTTPS or localhost).

## Deploy with GitHub Pages

1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the `main` branch and `/ (root)`, then save.
4. Visit `https://b3434474-art.github.io/OnStageMic/` after the deployment completes.

## Browser notes

- Microphone access requires permission and HTTPS (localhost is also treated as secure).
- Speaker output selection depends on browser support for `AudioContext.setSinkId`; otherwise audio uses the system default output.
- Use headphones when testing to reduce acoustic feedback. The app does not send audio to any server.
