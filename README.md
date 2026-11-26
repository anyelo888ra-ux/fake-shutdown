# Fake Shutdown Simulator v0.6

A lightweight browser-only shutdown and monitor OSD simulator for desktop and mobile.

## Features

- Approximate OS detection and distinct SVG identity marks for Windows versions, macOS, Ubuntu, Fedora, Debian, generic Linux, iOS, Android and unknown systems.
- OS-specific shutdown text and simulated shutdown sequences with different durations.
- Black-screen transition and bouncing **NO SIGNAL** display.
- NOVA DISPLAY fictional monitor brand with a custom SVG logo.
- Circular monitor OSD with quick controls for brightness, input source, picture mode and settings.
- Advanced display panel with live browser viewport resolution, pixel ratio, orientation, color temperature and sharpness controls.
- Simulated HDMI 1, HDMI 2, DisplayPort and USB-C inputs. Each input loads a different OS profile for experimentation.
- Double-click the power control to switch the simulated monitor off/on. The screen-off state displays NO SIGNAL.
- Keyboard shortcut **M** opens the monitor menu; **Esc** closes the menu or exits the simulation.
- Touch, mouse or keyboard activity wakes the simulated screen.
- Fullscreen helper, reduced-motion support and responsive portrait/landscape layouts.
- Persistent visible notice that this is only a browser simulation.

## Run locally

Open `index.html` in a modern browser. No installation, build step, framework or server is required.

## GitHub Pages

https://anyelo888ra-ux.github.io/fake-shutdown/

In GitHub, open **Settings → Pages** and select **Deploy from a branch**, branch **main**, folder **/(root)**.

## Safety and technical limits

This project only displays a browser animation. It does not shut down or restart the computer, imitate a real system crash, lock input, change physical monitor settings, alter the real display resolution, or modify files.

The OSD controls are fictional and affect only the simulation. The resolution shown is derived from browser/screen properties; browsers do not expose the physical monitor model or its exact refresh rate. OS detection is approximate because browsers may hide or reduce platform information.
