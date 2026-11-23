GRIDFALL: Last Line is a complete grid-based tower defense game in one index.html file. Enemies path to your Core through a flow field that recalculates every time you build or sell - so every placement is a routing decision. Wall off the wrong lane and the horde finds a new way in. Seal the Core completely and the game refuses the placement. No build step, no libraries, no assets.

The premise: Hold the line. Every tower you place reshapes the route. Every route you open is a door you have to defend.

Features

Flow-field pathfinding - a BFS distance field from the Core to both spawns, recomputed on every build/sell, with live dashed route previews while you hover a ghost tower

5 tower classes - Pulse (balanced), Rail (piercing line beam), Arc (chain lightning, never misses), Cryo (area slow field), and Amplifier (buff aura, no attack)

Branching upgrades - 4 levels per tower, with a choice of 2 specialisations at level 3 (e.g. Rail -> Longshot or Armor Break)

6 enemy archetypes - Drifters, Runners, Swarms, armored Bulwarks, evasive Phantoms, and the Overlord boss that spawns adds and appears every 10th wave

Targeting priorities - First / Last / Strongest / Closest, per tower

EMP super - charge builds from kills; unleashes a Core-wide stun and damage burst

Maze defense with a guardrail - can't place blocks that would leave any spawn with no route to the Core

10-wave campaign into endless mode, with credit economy, sell refunds, and best-wave persistence via localStorage

Live range rings - selection, ghost preview, and Amplifier aura all show exact coverage

Readable, period-modern UI - credits, Core integrity, wave, and EMP charge in the header; tower roster on the left; contextual inspector on the right

Responsive layout - three-column desktop grid collapsing to a stacked mobile view; canvas letterboxes to a 5:3 aspect and rescales via ResizeObserver

Accessible - full keyboard shortcuts, prefers-reduced-motion support (disables particles, glow, and animation), and focus-visible outlines

Fixed 60 Hz simulation decoupled from render rate, with a speed toggle (1x / 2x / 3x)

Tech: vanilla JavaScript, HTML5 Canvas 2D. Zero dependencies, ~400 lines, one file.

Controls: 1-5 select tower . Click place . U upgrade . X sell . T cycle target . E EMP . Space start wave / pause . Esc cancel . Right-click cancel

Enemy counters: Pulse handles Drifters . Cryo handles Runners . Rail handles Bulwarks . Arc handles Swarms . Arc/Cryo handles Phantoms