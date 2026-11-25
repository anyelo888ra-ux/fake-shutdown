# Fake Shutdown Simulator v0.5

A lightweight, responsive browser-only visual shutdown simulation for desktop and mobile.

## Features

- Approximate detection for Windows, macOS, Linux, iPhone/iPad and Android.
- Desktop shutdown-style screen followed by a black screen and a bouncing **NO SIGNAL** label.
- Mobile-specific iOS and Android-inspired screens with a dark screen-off transition.
- Touch, mouse or keyboard activity wakes the simulation.
- Fullscreen helper for supported browsers; iOS guidance is shown where browser fullscreen is restricted.
- Reduced-motion support and responsive portrait/landscape layouts.
- Visible notice that this is only a visual simulation.

## Run locally

Open `index.html` in a modern browser. No installation, build step, framework or server is required.

## GitHub Pages

This repository is configured for the project URL:

https://anyelo888ra-ux.github.io/fake-shutdown/

In GitHub, open **Settings → Pages** and select **Deploy from a branch**, branch **main**, folder **/(root)**.

## Safety

This project only displays a browser animation. It does not shut down or restart the computer, imitate a real system crash, lock input, change system settings, or modify files.

## Limitations

Operating-system detection is approximate because browsers may hide or reduce platform information. The visual style is an imitation, not a native operating-system screen.
