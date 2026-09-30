<table>
<tr>
<td width="50%" valign="top">

## [open-spyro](https://github.com/theMagicalKarp/open-spyro)

<img align="right" width="40%" src="./docs/assets/open-spyro-progress.svg" alt="open-spyro C-match progress map, one tile per function, sized by code bytes" />

A byte-for-byte matching decompilation of
[Spyro the Dragon](https://en.wikipedia.org/wiki/Spyro_the_Dragon) _(PS1, NTSC,
`SCUS_942.28`)_. Every commit rebuilds the executable, all 37 overlays, and
`WAD.WAD` byte-identical to the original disc, and stays runnable in an
emulator. Functions not yet matched in C link in as the original assembly, so
progress is simply the fraction of code bytes expressed as verified-matching C.

<br clear="right" />

</td>
<td width="50%" valign="top">

## [wasmdoom](https://github.com/theMagicalKarp/wasmdoom)

<img align="right" width="35%" src="./docs/assets/wasmdoom.png" alt="wasmdoom logo" />

A small, portable WebAssembly build of the DOOM engine: a pure state machine you
feed inputs into and get video and audio out of, with little to no dependencies
to run. Play it at
[themagicalkarp.github.io/wasmdoom](https://themagicalkarp.github.io/wasmdoom/),
or check out
[wasmdoom-examples](https://github.com/theMagicalKarp/wasmdoom-examples) for
projects built on top of it, like emoji-doom, which plays DOOM in your terminal
rendered as emojis 😈.

<br clear="right" />

</td>
</tr>
</table>

## [wgsl-raytrace](https://github.com/theMagicalKarp/wgsl-raytrace)

A GPU path tracer written in Rust, running headless on
[wgpu](https://wgpu.rs/) with its tracing kernel written in
[WGSL](https://www.w3.org/TR/WGSL/). Features a Blender-style Principled BSDF
_(GGX metals, rough glass, emission, subsurface scattering)_, image and
procedural textures, HDRI lighting, multiple importance sampling over a BVH, and
an SVGF-style à-trous denoiser. It grew out of
[raytrace](https://github.com/theMagicalKarp/raytrace), my original CPU ray
tracer built while working through the
[_Ray Tracing in One Weekend_](https://raytracing.github.io/) series, and reads
the same TOML scene format.

<p align="center">
  <img width="32%" src="./docs/assets/raytrace1.jpg" alt="path-traced scene with a glass torus, chrome sphere, and draped cloth" />
  <img width="32%" src="./docs/assets/raytrace2.jpg" alt="grid of spheres sweeping roughness, metallic, IOR, alpha, and emission" />
  <img width="32%" src="./docs/assets/raytrace3.jpg" alt="textured stone cube and copper sphere on wood and woven carpet" />
</p>

## [shaders](https://github.com/theMagicalKarp/shaders)

A collection of
[GLSL](https://www.khronos.org/opengl/wiki/OpenGL_Shading_Language) shaders
written to explore the rendering pipeline: ray marching, volumetric clouds, and
refraction with chromatic dispersion. Runs in the browser at
[shaders.sheehy.network](https://shaders.sheehy.network/).

<p align="center">
  <img width="32%" src="./docs/assets/shaders1.png" alt="ray-marched scene with reflective spheres and shadows" />
  <img width="32%" src="./docs/assets/shaders2.png" alt="volumetric cloud rendering" />
  <img width="32%" src="./docs/assets/shaders3.png" alt="refractive gem with chromatic dispersion" />
</p>

## [blender-portfolio](https://github.com/theMagicalKarp/blender-portfolio)

A running log of my [Blender](https://www.blender.org/) work: 3D modeling,
shading, and lighting studies made in short daily bursts since 2024. Each
project keeps its references alongside a sequence of renders, so the repo reads
as a progression rather than a gallery of finished pieces.

<p align="center">
  <img width="32%" src="./docs/assets/blender1.jpg" alt="translucent shapes resting on sunlit dunes" />
  <img width="32%" src="./docs/assets/blender2.jpg" alt="gas station lit at night" />
  <img width="32%" src="./docs/assets/blender3.jpg" alt="sculpted head study, two views" />
</p>

<table>
<tr>
<td width="50%" valign="top">

## [pokemon-emerald-refined](https://github.com/theMagicalKarp/pokemon-emerald-refined)

<img align="right" width="40%" src="./docs/assets/emerald.png" alt="painted green sea under a pale sun" />

A Pokémon Emerald ROM hack built on the game's decompilation. Adds
quality-of-life improvements _(nature, EV, and IV display in the summary
screen)_, rebalanced moves, and increased challenge, while preserving the look
and feel of the original game.

<br clear="right" />

</td>
<td width="50%" valign="top">

## [dithering](https://github.com/theMagicalKarp/dithering)

<img align="right" width="35%" src="./docs/assets/dithering.png" alt="dither" />

An implementation of
[Floyd–Steinberg dithering](https://en.wikipedia.org/wiki/Floyd%E2%80%93Steinberg_dithering)
in Go, reducing images to a limited palette by diffusing each pixel's
quantization error onto its neighbors.

<br clear="right" />

</td>
</tr>
</table>

<table>
<tr>
<td width="50%" valign="top">

## [gameover](https://github.com/theMagicalKarp/gameover)

<img align="right" width="40%" src="./docs/assets/GAMEOVER.gif" alt="GAME OVER NES demo" />

A NES demo written in 6502 assembly, built to learn how the NES actually works.
The ROM shows off basic graphics and audio capabilities, and you can play it in
your browser at [nes.sheehy.network](https://nes.sheehy.network/).

<br clear="right" />

</td>
<td width="50%" valign="top">

## [donut](https://github.com/theMagicalKarp/donut)

<img align="right" width="40%" src="./docs/assets/donut.gif" alt="donut spinning in the terminal" />

A [ray-marched](https://en.wikipedia.org/wiki/Ray_marching) 3D renderer that
runs entirely in your terminal, written in [Zig](https://ziglang.org/). Orbit
the camera, zoom, and flip between multiple animated scenes, all in ASCII.

<br clear="right" />

</td>
</tr>
</table>

<table>
<tr>
<td width="50%" valign="top">

## [iter](https://github.com/theMagicalKarp/iter)

<img align="right" width="45%" src="./docs/assets/iter.png" alt="iter logo" />

A _simple_ and _ergonomic_ Go library for implementing and using iterators.
Ships an easy-to-implement `Iterable` interface plus an itertools-style toolset
for working with them.

<br clear="right" />

</td>
<td width="50%" valign="top">
</td>
</tr>
</table>
