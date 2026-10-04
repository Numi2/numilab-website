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

The newest medical clip, [stricter KKT synthetic wound-lip traction](public/media/synthetic-skin-traction-fgmres-20261004-inconclusive.mp4), contains six accepted native Apple Metal states from a planned 60-step synthetic-coupon run. At the last accepted state, the gap was 0.586943 mm versus the reused zero-force value of 0.600000 mm, a 13.06 µm change, at 0.176 mN per site. The matched 7-Newton control changed by 5.78 µm. The 2.26× response difference is solver sensitivity, not evidence of greater physical accuracy. The candidate still stopped at step 6 under the unchanged mixed-FEM volume-residual gate; it is inconclusive and shows no completed wound closure.

The earlier 7-versus-10 Newton diagnostic stopped at the same boundary with identical accepted lip geometry, while the higher budget took 33% longer. The stricter KKT candidate then used 9 of 20 available FGMRES iterations and still failed the same gate, so increasing that budget alone is not supported. Neither study relaxed acceptance thresholds. The [committed solver record](https://github.com/Numi2/numi-solver/blob/5d42b32/docs/assets/skin-volume-residual-diagnostic-20261004/fgmres-followup-20261004/README.md) contains the registered plan, source snapshots, raw outputs, videos, and checksums; media provenance is in [the source record](public/media/SOURCES.md).
