# The Binding of Isaac

**Version:** 1.0

A minimal, self-hosted page that runs the original Flash version of *The Binding of Isaac (Wrath of the Lamb)* in the browser using [Ruffle](https://ruffle.rs), an open-source Flash Player emulator.

This project is intentionally minimalistic — after extensive testing, no custom renderer, quality, or resolution settings were found to meaningfully improve performance or stability over Ruffle's own defaults, so the page simply lets Ruffle run as-is.

[Site Link](https://hito-planner.github.io/binding-of-issac/)

## Features

- Loads and plays `thebindingofisaac.swf` directly in the browser, no plugins required
- Uses Ruffle's own default renderer, quality, and frame rate settings
- Game is centered on the page at its native 800x600 resolution
- Save/load support via Ruffle's built-in Save Manager (right-click the game → Save Manager) to export or import `.sol` save files
