TTSKY26A Demoscene – Minimal MilkDrop Shader

Procedural visualization reduced to a Tiny Tapeout–compatible model:

color = f(x, y, t)

Concept

- no framebuffer
- no feedback
- purely analytic shader
- directly mappable to hardware

Equation

c = sin( sin(3x+t) + sin(3y−t) + 1/(r+ε) + t )

with r = x² + y²

Run

Open "index.html" locally or enable GitHub Pages.
