# DORMANT

**An ancient troll has become part of a living forest.**

**[▶ Open the live artwork](https://bongdoe.github.io/Dormant/)**

*Dormant* is an interactive 3D artwork that runs in the browser. A giant troll, big as a hill, has slept so long that the forest has grown over it. Roots creep across its cheeks and shoulders, trees grow from its crown, and moss covers the stone of its skin. Its eyes still glow. It still breathes, very slowly.

The scene is drawn as chaotic digital art in cyan, electric green and deep blue, with sparks of magenta. Surfaces dissolve into point clouds and wireframe, and short glitches reveal the structure underneath.

---

## Experience

| Action | Desktop | Mobile |
| --- | --- | --- |
| Orbit around the troll | drag | one-finger drag |
| Zoom | scroll | pinch |
| Pan | right-drag | two-finger drag |

Move your cursor and the forest shifts. The troll's gaze drifts toward you. Leave it alone and the camera slowly drifts and breathes by itself.

### Controls

A small control strip sits in the bottom-left corner.

| Button | Key | Effect |
| --- | --- | --- |
| pause | `Space` | Freeze the scene in place |
| reset view | `R` | Glide the camera back to the troll's face |
| particles | `P` | Show or hide floating spores |
| glitch | `G` | Turn the digital glitch layer on or off |
| fragments | `F` | Turn the dissolving wireframe / point-cloud effect on or off |
| ambient | `A` | Turn idle camera drift and parallax on or off |

---

## About the work

- **Generated, not modelled.** No 3D models or textures are loaded. When the page opens, the troll is sculpted from mathematical shapes. Roots are grown across its surface, avoiding its eyes, nose and mouth. Every crooked tree is built by a branching algorithm.
- **Alive, but slowly.** The troll breathes, yawns now and then, and turns its head. Its eyes flicker and dart. Branches sway, and light travels down the roots like sap. The animation loops forever with no visible beginning or end.
- **Rendered as signal.** Stippled surfaces, fragmented outlines, scanlines, chromatic separation and stray magenta pixels. The glitch comes in short, rare bursts, never as a constant filter.
- **One file.** Everything, including the 3D engine, is in a single HTML file of about 600 KB. It makes no network requests and works offline.
- **Runs anywhere.** Desktop gets the richest version. Phones get fewer particles and lighter effects, and the quality adjusts itself if a device struggles.

---

## Run it locally

Download `index.html` and double-click it. That's all.

It needs a browser with **WebGL2** support: any recent version of Chrome, Edge, Firefox or Safari.

Optional URL settings:

- `?quality=high`, `?quality=medium` or `?quality=low`: force a quality level
- `?seed=12`: grow a different forest (any number works)

Example: `https://bongdoe.github.io/Dormant/dormant.html?quality=low`

---

## Built with

- [Three.js](https://threejs.org), the WebGL 3D engine (MIT license), bundled inside the file
- Custom GLSL shaders for the stippled shading, dissolving surfaces and glitch effects

---

© bongdoe. All rights reserved.
