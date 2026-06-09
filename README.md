# Bitcoin NEXUS ⚡🔮

A real-time Bitcoin mempool visualizer and block explorer with a 3D rotating block cube, live particle physics, and procedural audio feedback when a new block is mined.

## 🌐 Live Demo

**[nwfella.github.io/bitcoin-nexus](https://nwfella.github.io/bitcoin-nexus/)**

## Features

- **🌀 3D Rotating Block Cube** — CSS 3D-transformed cube displaying the latest block height on every face
- **🌊 Live Mempool Visualization** — Particle system representing unconfirmed transactions orbiting a central vortex
- **📊 Real-Time Stats** — Current TPS, unconfirmed transaction count, and pending BTC volume
- **📋 Recent Blocks Feed** — Scrollable list of the 5 most recent blocks with hash, time, tx count, and size
- **⛏️ Force Mine Block** — Click to simulate mining: particles explode outward, screen flashes orange, block height increments, and a **procedural sound effect** plays
- **🔊 Block-Mined Sound** — 4-layer Web Audio API sound (sub-bass thump + metallic ping + noise burst + harmonic chime) — toggle on/off via the header switch
- **🔗 Live WebSocket** — Connects to `ws.blockchain.info` for real Bitcoin mainnet data, with graceful simulation fallback
- **📱 CRT Scanline Overlay** — Retro terminal aesthetic with animated scanline
- **🌙 Dark Cyberpunk Theme** — Bitcoin orange (#f7931a) on deep black, glass-morphism panels

## Tech Stack

- **Pure HTML/CSS/JS** — No frameworks, no build step, no dependencies
- **Web Audio API** — 4-layer procedural sound synthesis
- **CSS 3D Transforms** — Hardware-accelerated cube animation
- **Canvas API** — Particle physics, network lines, radial gradients
- **WebSocket** — Live blockchain data streaming

## Getting Started

Just open `index.html` in any modern browser. That's it.

```
git clone https://github.com/nwfella/bitcoin-nexus.git
cd bitcoin-nexus
open index.html
```

## Controls

| Control | Action |
|---------|--------|
| **Force Mine Block** button | Simulate mining a new block |
| **Sound toggle** (header) | Enable/disable block-mined sound effect |

## License

MIT © 2026 nwfella
