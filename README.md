# Toyota CE96 Corolla — Windscreen Stress Analyzer

Interactive 3D wireframe stress analyzer for a Toyota CE96 Corolla wagon (RHD, FWD) with a growing windscreen crack.

## Features

- **3D Wireframe Model** — Three.js-powered accurate CE96 wagon wireframe with colour-coded zones (body, pillars, underbody, powertrain, interior)
- **Click-to-Mark Cracks** — Click anywhere on the windscreen to place crack markers
- **10 Reinforcement Options** — Toggle structural fixes and see real-time stress changes
- **12 Load Test Scenarios** — Including torsion, impact, braking, cornering, vibration, thermal, cargo, and a real-world lateral slope + open tailgate scenario
- **Parallel Test Mode** — Run multiple tests simultaneously with compound stress multipliers
- **Per-Zone Stress Accuracy** — Each zone gets its own multiplier during animations
- **Mobile Responsive** — Full touch support with tab-based navigation
- **Day/Night Mode** — Toggle between dark and light themes

## Deploy

Static HTML — just serve `index.html`. No build step needed.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/YasasWeerasinghe/toyota-ce96-stress-analyzer)

## Tech

- Three.js r128 (CDN)
- Single self-contained HTML file
- No dependencies, no build tools
