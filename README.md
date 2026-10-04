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

The newest medical clip, [curved suture passage prefix](public/media/perfused-suture-passage-prefix-20261004.mp4), shows six exact accepted states through 16 curved-path microsteps on a synthetic four-layer coupon. The final tissue mesh moves by at most 1.338 µm (0.044 µm RMS) from pre-entry; thread nodes move by at most 0.042981 mm. Four-step device batches made intermediate states inspectable, but did not establish better total throughput: an earlier 32-step attempt returned no passage state after more than seven minutes on an idle Mac mini. This run stopped before through-wall clearance, distal needle exit, thread pull-through, suture retention, or wound closure. The needle is kinematically targeted; no Franka or dVRK arm is simulated. The clip is incomplete synthetic software evidence, not calibrated tissue behavior or clinical validation. Its source-bound build, snapshots, run limits, and hashes are in the [solver archive](https://github.com/Numi2/coupled-physics-solver/blob/5f11b57b8563f49731b8cb4f7c7c3e2d556cd222/docs/assets/perfused-suture-passage-prefix-20261004/README.md).

The earlier [puncture-entry prefix](public/media/perfused-suture-entry-prefix-20261004.mp4) shows the first accepted channel state. A separate [trace-guided wound-lip traction clip](public/media/synthetic-skin-traction-trace-guided-20261004-7step.mp4) shows seven accepted states from the first seven steps of a planned 60-step native Apple Metal run on one 2,304-tetrahedron synthetic coupon. The unchanged `1e-4` mixed-volume gate passed at `8.5955e-5`, while the stricter preregistered `5e-5` target was missed. Mean gap changed by 11.26 µm to 0.588743 mm; the greatest displacement was 8.83 µm, and force had reached only 0.253 mN per site of the planned 10 mN endpoint. It is a short traction prefix, not wound closure or completion of the protocol.

The prior needle-and-thread result demonstrates a model dVRK holding a GS21 needle and carrying a discrete elastic thread; neither study joins that tool to the synthetic tissue coupon or shows a needle pass, Franka manipulation, measured skin properties, healing, or clinical qualification. The [source-bound solver archive](https://github.com/Numi2/numi-solver/blob/8b2646f/docs/assets/skin-volume-residual-diagnostic-20261004/trace-guided-20261004/README.md) preserves the registered miss, source snapshots, FGMRES trace, exact outputs, and checksums. Earlier rejected runs remain in the [parent diagnostic archive](https://github.com/Numi2/numi-solver/blob/8b2646f/docs/assets/skin-volume-residual-diagnostic-20261004/README.md); media provenance is in [the source record](public/media/SOURCES.md).
