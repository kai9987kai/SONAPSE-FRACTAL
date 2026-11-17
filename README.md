# SONAPSE — Fractal Connectome Laboratory

An offline, single-file research simulator exploring embodied agents controlled by adaptive neural connectomes with configurable fractal-inspired topologies.

## Run

Open `sonapse_embodied_world_lab.html` in a modern browser. The simulation is self-contained and requires no build step, server, package manager, or external assets.

## Research systems

- Procedurally generated explorable environment with terrain, vegetation, water, landmarks, resources, hazards, weather and day/night variation.
- Autonomous embodied agent with energy, health, movement, exploration and waypoint behaviour.
- Twenty sensory inputs spanning directional vision, target bearing and proximity, resource/hazard cues, directional audio, terrain, energy, damage, velocity, memory and ambient light.
- Neural populations for sensory, association, memory, integration, motor and modulatory processing.
- Configurable DSAG, multi-compartment, LIF, WireType-inspired, FlyHash-inspired and hybrid neuron variants.
- Fractal-inspired Sierpiński, Mandelbrot-inspired, Cantor, Vicsek and Hilbert-like connectivity, plus small-world, random and hierarchical controls.
- Reward-modulated synaptic plasticity, inhibitory populations, telemetry, experiment snapshots and CSV/JSON exports.

## Research caveats

This is an exploratory computational model. Fractal geometries are finite approximations; the simulator does not instantiate an actually infinite graph. Neural dynamics and sensory modalities are simplified abstractions, not validated biological models. Metrics are internal comparative proxies and should be validated against formal graph-theoretic and behavioural benchmarks before making scientific claims.

## Suggested protocol

1. Fix the world seed, agent starting state, sensory configuration and simulation horizon.
2. Compare one topology at a time while holding neuron architecture and plasticity parameters constant.
3. Repeat each condition across multiple seeds.
4. Record navigation success, resource collection, collision rate, energy efficiency, memory recall, graph modularity, clustering, path length and propagation statistics.
5. Report distributions and uncertainty, not only the best run.

## Project status

Initial public prototype. See the standalone simulator for interactive controls and live diagnostics.
