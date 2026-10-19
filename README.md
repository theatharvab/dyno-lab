# DYNO LAB

A standalone browser-based engine development and dyno simulation prototype.

## Run locally
Open `index.html` in a modern browser. The 3D engine viewer uses Three.js from a CDN, so an internet connection is needed for that visual.

## Publish with GitHub Pages
1. Open this repository's **Settings**.
2. Select **Pages** in the left sidebar.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Choose branch **main** and folder **/(root)**, then click **Save**.
5. After GitHub finishes deploying, the game should be available at:
   https://theatharvab.github.io/dyno-lab/

## Current prototype
- J35Z2-inspired V6 engine assembly visualization (procedural model, draggable and zoomable)
- Configurable intake, exhaust, cam profile, compression ratio, rev limit, fuel/calibration, and induction
- Simulated horsepower and torque curves
- Dyno run telemetry, saved browser configuration, and run history/comparison
- Responsive dark motorsport-workstation interface

## Important simulation note
This is an educational prototype using a simplified, illustrative model. It is **not** measured Honda J35Z2 dyno data, validated engine simulation, or a tool for making real-world engine modifications. The 3D model is illustrative, not a dimensionally accurate CAD model.
