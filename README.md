# Neon Fluid 🐴

A black screen that bleeds neon. Click & drag to paint with glowing multicolored fluid.

Built on the GPU Navier-Stokes solver from [PavelDoGreat/WebGL-Fluid-Simulation](https://github.com/PavelDoGreat/WebGL-Fluid-Simulation) (MIT).

## Controls

- **Click & drag** — paint with neon fluid (mouse + touch, multi-touch on mobile)
- **Space** — random splats
- **P** — pause / resume
- **H** — toggle the settings panel (quality, diffusion, vorticity, bloom, …)

## Local dev

```bash
python3 -m http.server 8123
# open http://localhost:8123
```

Requires WebGL1/2 — works in all modern desktop and mobile browsers.
