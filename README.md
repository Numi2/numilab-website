# Numi Lab Website

The public research website for Numi Lab, including research papers and project records.

## Development

```sh
npm install
npm run dev
```

## Production build

```sh
npm run build
```

The newest native elastic volume video shows a standalone 81,920-tetrahedron Apple Metal run. Its independently audited numerical energy bounds are 0.254% at 25 µs and 0.122% at the half timestep, within the authored 1% budget. A matched 10,240-to-81,920-tetrahedron run at 25 µs differs by up to 9.34 mm at owning nodes against the 1 mm target, so spatial convergence fails. Coupled bag/fruit mechanics remain open. Provenance, the [matched-resolution audit](https://github.com/Numi2/numi-solver/blob/318bdc8/docs/assets/deformable-support-matched-25us/spatial.json), and archived media are recorded in [public/media/SOURCES.md](public/media/SOURCES.md).

A separate [64-step FP64 CPU elastic-body/yarn-endpoint study](https://github.com/Numi2/numi-solver/blob/93ccd2b/docs/assets/elastic-yarn-fem-endpoint-multistep/README.md) advances contact between a locally authored two-node yarn and an elastic body through two linked 32-step windows at 20 µs per step, covering 1.28 ms with exact replay from a bound checkpoint. Its final sampled minimum tetrahedron Jacobian is 0.3974 and endpoint gap is −1.59 µm; a +0.322 µJ combined physical energy residual remains open. This short-horizon component result does not qualify native Metal coupling, the full bag/fruit scene, or whole-scene work closure.

## Medical deformable preview

The newest medical clip, [synthetic wound-lip traction](public/media/synthetic-skin-traction-v5-inconclusive.mp4), contains six accepted native Apple Metal states from a planned 60-step synthetic-coupon run. The loaded gap changed from 0.600000 mm to 0.594221 mm at 0.176 mN per site before the solver rejected the next state at its existing mixed-FEM volume-residual limit. The result is inconclusive and shows no completed wound closure.

A bounded follow-up compared the default seven Newton iterations with ten. Both runs stopped at the same step with the same solver status and identical accepted lip geometry; the 10-iteration run took 36.55 seconds versus 27.44 seconds. This refutes the iteration cap as the sole cause and leaves the mixed-volume solve unresolved. Neither run changes the existing acceptance thresholds. The [committed solver record](https://github.com/Numi2/numi-solver/blob/d21bbf6/docs/assets/skin-volume-residual-diagnostic-20261004/README.md) contains the registered plan, probe source, raw outputs, and checksums; media provenance is in [the source record](public/media/SOURCES.md).
