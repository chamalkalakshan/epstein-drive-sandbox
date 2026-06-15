# Epstein Drive Physics Sandbox

A browser-based physics simulator for space travel in the universe of *The Expanse* TV show and book series.
I’m a huge fan of The Expanse, so I built this as a fun way to explore Epstein drive travel, flip-and-burn trajectories, and the scale of the Solar System through the lens of the series.

Open `index.html` in any modern browser to run. No install or server required.

## Features

### Solar System Map
- 18 canonical bodies from The Expanse: Sol, Mercury, Venus, Earth/Luna, Mars, Eros, Ceres Station, Tycho Station, Pallas, Vesta, Jupiter, Ganymede Station, Europa, Saturn, Titan, Uranus, Neptune, The Ring Gate
- Power-law visual scale for readable planet spacing
- Orbit rings, asteroid belt haze, star field
- Zoom (scroll wheel), pan (middle/right-drag), keyboard shortcuts

### Epstein Drive Physics
- Flip-and-burn constant acceleration trajectory
- Configurable thrust (g), specific impulse (Isp), dry mass, fuel ratio
- Real delta-v and rocket equation calculations (Tsiolkovsky)
- Ship presets: Rocinante, Donnager, Canterbury, Razorback, Custom

### Flight Plan Panel
- Route info, flip-and-burn times (accel + decel phases)
- Peak velocity and percent of speed of light
- Propellant budget with feasibility check
- Velocity profile chart (triangle wave showing flip-and-burn shape)
- Fuel burn curve (exponential decay of propellant over time)

### Comparison Tools
- Hohmann transfer time vs Epstein drive (how many times faster)
- Communication signal lag and round-trip delay
- Orbital insertion delta-v and parking orbit calculator
- Emergency / combat burn at max thrust with Juice warning

### Crew Experience
- G-force description (Weightless to Combat burn)
- Juice requirement threshold (above 3g)
- Radiation dose calculator (GCR exposure, mSv, annual limit)
- Belter lore note for OPA routes
- Relativistic time dilation toggle (proper time vs coordinate time, Lorentz factor)

### Navigation Tools
- Multi-leg waypoint journeys (up to Origin + 2 waypoints + Destination)
- Closest approach / optimal launch window finder (searches 10-year window)
- Jump to optimal year button
- Cargo mass penalty calculator
- URL hash sharing - bookmark and share any route with all parameters

### Visual Overlays
- Expanse lore event markers (S1-S4 plot events with pulsing animations)
- Faction territory zone shading (UN, MCRN, OPA Belt, Outer Planets)
- Orbit animation (planets move at correct relative speeds)
- Animated ship flight simulation along trajectory

### Keyboard Shortcuts
- Space: toggle orbit animation
- F: toggle flight simulation
- Esc: clear current route
- R: reset zoom and pan

## Screenshot

Open index.html, select Earth as origin and Ceres Station as destination, then press F to simulate the flight.
