# Fake Shutdown Simulator v0.7

A lightweight browser-only shutdown and monitor OSD simulator for desktop and mobile.

## Main experience
- Approximate OS detection. Browsers often hide the Linux distribution, so the simulator uses a generic Linux profile unless the browser explicitly identifies a distro.
- Distinct shutdown identity SVGs and text for Windows XP/7/10/11, macOS, iOS, Android and Linux distributions.
- Selectable demo profiles for Ubuntu, Fedora, Debian, Arch Linux, Linux Mint, Manjaro, Kali Linux, openSUSE, Pop!_OS, elementary OS, Zorin OS, Alpine Linux, NixOS and EndeavourOS.
- Different simulated shutdown sequences and durations per OS profile.
- Black-screen transition and bouncing **NO SIGNAL** display.
- NOVA DISPLAY fictional monitor brand with a custom SVG mark.
- Circular monitor OSD with brightness, contrast, picture modes, input sources, advanced settings and system information.
- Simulated HDMI 1, HDMI 2, DisplayPort and USB-C profiles. Inputs are labels for experimentation, not real hardware detection.
- Resolution presets are visual profiles only. The browser viewport measurement is informational; the page cannot change the device's real resolution or refresh rate.
- Double-click the monitor power control to switch the simulated display off/on.
- Keyboard shortcut **M** opens the monitor menu; **Esc** closes the menu or exits the simulation.
- Touch, mouse or keyboard activity wakes the simulated screen.
- Fullscreen helper, reduced-motion support and responsive layouts.

## NOVA DISPLAY concept store
Open the [NOVA DISPLAY store](https://anyelo888ra-ux.github.io/fake-shutdown/nova). It includes a fictional monitor collection, category filters, product details and a small comparison tool. All model names and specifications are fictional; no products are sold.

## Contributing
Use the GitHub issue chooser to report bugs, suggest features or leave feedback. Pull requests have a checklist template. See [CONTRIBUTING.md](CONTRIBUTING.md).

## Run locally
Open `index.html` in a modern browser. No installation, build step, framework or server is required.

## GitHub Pages
https://anyelo888ra-ux.github.io/fake-shutdown/

In GitHub, open **Settings → Pages** and select **Deploy from a branch**, branch **main**, folder **/(root)**.

## Safety and technical limits
This project only displays browser animations. It does not shut down or restart the computer, imitate a real system crash, lock input, change physical monitor settings, alter the real display resolution, or modify files. A visible notice and exit control remain available. The NOVA OSD controls and input changes affect only the simulation.
