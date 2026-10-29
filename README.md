# NN / Spider

A self-contained Three.js animation inspired by a glowing neural network and a spider made of light.

The same **26 nodes and 120 connections** move through four stages: a five-column network, descent onto the floor, transformation into an eight-legged spider, and continuous crawling. This is a visual morph, not a trained neural-network or physics simulation. Fine decorative filaments describe the body and legs in addition to the preserved graph.

## Run

Download `index.html` and open it in a current browser with WebGL enabled. Three.js r160 is embedded, so no internet connection, installation, server, or build step is required.

- Play/pause: button or **Space**.
- Replay: button or **R**.
- Jump between stages or drag the timeline to inspect the transformation.
- Orbit: drag the scene. Zoom: scroll or pinch.
- Reset the camera: camera button or **C**.
- Playback speed: cycle through 0.5×, 1×, 1.5× and 2×.

After the 26-second introduction the spider keeps exploring. The timeline stays at its final position; scrubbing or replaying returns to the introduction. Reduced-motion preferences start the animation paused. Hidden tabs pause advancement.

## Publish with GitHub Pages

In **Settings → Pages**, select **Deploy from a branch**, choose **main** and **/ (root)**, and click **Save**.

After GitHub finishes deploying, the site will be at:

https://sragnarsson.github.io/NN-spider/

## Dependencies

Three.js r160, MIT license, copyright the Three.js authors. The complete third-party license is included in `index.html` next to the bundled library. Everything else is authored HTML, CSS and JavaScript; there are no external fonts, images, tracking scripts, or runtime downloads.
