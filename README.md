Hand Web Lab

A real-time, full-screen, high-FPS webcam experiment that uses MediaPipe Hands to generate dynamic, elastic web-like connections between fingers across both hands.

Inspired by TouchDesigner-style generative visuals, built entirely for the browser in a single HTML file.

✨ Features

Full-screen live webcam background

Real-time hand tracking (left + right hands)

Finger-to-finger web generation

Within the same hand

Across both hands

Elastic, spring-based line behavior

Procedural motion using math and noise

TouchDesigner-inspired UI overlays

Optimized rendering loop targeting ~120 FPS

🕸️ How It Works

Webcam feed fills the entire viewport

MediaPipe tracks 21 landmarks per hand

Finger tips act as dynamic anchor points

Elastic web lines connect:

Finger to finger

Hand to hand

Line tension, density, and motion respond to:

Hand distance

Finger spread

Movement speed

Math-driven UI elements float in the scene for visual context

🧠 Tech Stack

HTML5

Vanilla JavaScript

Canvas 2D (high-performance rendering)

MediaPipe Hands

requestAnimationFrame (optimized loop)

No frameworks. No build tools. No dependencies beyond MediaPipe.

🚀 Getting Started

Clone the repo

git clone https://github.com/your-username/hand-web-lab.git


Open the HTML file in a modern browser

index.html


Allow webcam access

Use both hands in front of the camera

That’s it.

🎛️ Interaction Guide
Gesture	Effect
Spread fingers	Expands the web
Close fingers	Tightens the web
Move hands apart	Increases tension
Move hands closer	Densifies connections
Fast motion	Adds wave ripples
📈 Performance

Designed for high refresh rates

Target: 120 FPS on capable hardware

Minimal object allocation per frame

Adaptive rendering based on device performance

🧪 Experimental

This project is a visual experiment, not a production library.
Expect rapid iteration, visual tweaks, and math-driven chaos.

🧩 Ideas for Expansion

WebGL or shader-based rendering

Audio-reactive web tension

Gesture-controlled modes

TouchDesigner / OSC bridge

Recording and export support

📄 License

MIT License
Use it. Break it. Remix it.