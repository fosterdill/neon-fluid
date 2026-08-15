# Neon Fluid 🐴

A black screen that bleeds neon. Click & drag to paint with glowing multicolored fluid.

Built on the GPU Navier-Stokes solver from [PavelDoGreat/WebGL-Fluid-Simulation](https://github.com/PavelDoGreat/WebGL-Fluid-Simulation) (MIT).

## Controls

- **Click & drag** — paint with neon fluid (mouse + touch, multi-touch on mobile)
- **Space** — random splats
- **P** — pause / resume
- **M** — toggle the microphone
- **H** — toggle the settings panel (quality, diffusion, vorticity, bloom, …)

## Microphone (optional)

The sim can react to your microphone. Toggle it with **M**, the on-screen
**🎙 mic** button (bottom-right), or the Microphone folder in the settings
panel. It requests mic permission only when you turn it on.

- Overall audio level drives ambient fluid that drifts around the screen even
  when you're not touching it.
- A bass beat-detector fires a central neon shockwave + bloom flash on each
  kick.
- A small spectrum visualiser (bass → treble) sits along the bottom edge so
  you can see the mic is live.

Tune it in the settings → **Microphone** folder: sensitivity, ambient flow,
and bass boost.

## Local dev

```bash
python3 -m http.server 8123
# open http://localhost:8123
```

Requires WebGL1/2 — works in all modern desktop and mobile browsers.
