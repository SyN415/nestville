# Nestville v3 — Sketch Studio

Draw a character with the mouse. That drawing becomes the in-game sprite.

## Flow
Title → New → **Draw a friend** → pencil on transparent paper → Bring to life → sketch birth → name → walk Nestville.

## Fields
- speciesId: custom
- birthType: sketch
- spriteData: trimmed PNG dataURL
- spriteW / spriteH
- walkStyleId still applies (default jiggle)

## Tools
Pencil, eraser, 8 colors, fine/med/bold, undo, clear.
Pointer events (mouse + touch).
Canvas pixels stay transparent; paper color is CSS.

Empty paper is rejected. Auto-outline + 96px cap on bake.
