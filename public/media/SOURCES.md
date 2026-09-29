# Website media sources

These are copied, unmodified research renders; they are not generated concept art.

## numi-human-native.png

- Source: https://github.com/Numi2/numilab-human/blob/0eb103038572c268dddf7bdf92594d82b30452b1/Docs/media/unassisted-standing-20260922/oblique.png
- Record: https://github.com/Numi2/numilab-human/blob/0eb103038572c268dddf7bdf92594d82b30452b1/Docs/media/unassisted-standing-20260922/README.md
- Terminal-state render after a single ten-second native standing run. The image is not a video or evidence of biomechanical calibration, full-horizon force/energy closure, or Brain/Matter integration.
- BodyParts3D, © The Database Center for Life Science licensed under CC Attribution 4.0 International: https://creativecommons.org/licenses/by/4.0/
- MyoSim myofullbody source: Apache-2.0. Upstream notices: https://github.com/Numi2/numilab-human/blob/0eb103038572c268dddf7bdf92594d82b30452b1/THIRD_PARTY_NOTICES.md

## metal-cloth-replay.gif

- Source: https://github.com/Numi2/numi-solver/blob/81929096e12ed5285ccf1b0c2d457076da534817/docs/assets/cloth-metal-pickup-spill.gif
- Record: https://github.com/Numi2/numi-solver/blob/81929096e12ed5285ccf1b0c2d457076da534817/README.md
- Historical 49-frame visualization of a four-second Apple Metal solver trajectory, preceding the September 29 gravity, landing, and packing corrections. Retained as an archive; it does not qualify the changed source.

## fruit-mass-comparison.mp4 and fruit-mass-comparison-poster.png

- Source: https://github.com/Numi2/numi-solver/blob/84a1d5a/docs/assets/fruit-mass-1x-vs-3x-native-diagnostic.mp4
- Poster: https://github.com/Numi2/numi-solver/blob/84a1d5a/docs/assets/fruit-mass-1x-vs-3x-native-diagnostic.png
- Record: https://github.com/Numi2/numi-solver/blob/84a1d5a/docs/assets/fruit-mass-1x-vs-3x-native-diagnostic.json
- Exact input snapshots and rendering source: https://github.com/Numi2/numi-solver/blob/84a1d5a/docs/assets/fruit-mass-1x-vs-3x-native-diagnostic-inputs.tar.gz
- One simulated second of first-replay native Apple Metal frames with original and 3× fruit mass. Initial geometry matches exactly, but the runs used different Apple hosts and binaries. This is a visual diagnostic, not a matched same-host control, independently audited contact certificate, or Franka arm result.

Historical Numi Lab, Automata, and BirdFlow media remain linked to their original public repositories. The ARDY asset is explicitly captioned as kinematic replay.

## fruit-bag-fp64-20260929.mp4 and fruit-bag-fp64-20260929.png

- Video: https://github.com/Numi2/numi-solver/blob/da4f4ff/docs/assets/cloth-pickup-spill.mp4
- Poster: https://github.com/Numi2/numi-solver/blob/da4f4ff/docs/assets/cloth-pickup-160.png
- Qualification log: https://github.com/Numi2/numi-solver/blob/da4f4ff/docs/assets/cloth-pickup-qualified.log
- Source, binary, and frame fingerprints: https://github.com/Numi2/numi-solver/blob/da4f4ff/docs/assets/cloth-pickup-evidence.json
- Corrected four-second CPU FP64 trajectory, two full replays passing with physical hash `0x23465c2d4a1627f4`. All four released fruit finish at their contact radii with zero vertical velocity and continue rolling. The 49-frame video displays at 12 fps; its 4.083-second playback represents four simulated seconds.
- Files are byte-for-byte copies of the published solver assets. Full Metal qualification, physical material calibration, and real-time performance remain separate.

## elastic-mesh-native-20260929.mp4 and elastic-mesh-native-20260929.png

- Video: https://github.com/Numi2/numi-solver/blob/166c904/docs/assets/deformable-mesh-drop.mp4
- Poster: https://github.com/Numi2/numi-solver/blob/166c904/docs/assets/deformable-mesh-drop-38.png
- Record: https://github.com/Numi2/numi-solver/blob/166c904/docs/DEFORMABLE_MESH.md
- Source, binary, geometry, and media fingerprints: https://github.com/Numi2/numi-solver/blob/166c904/docs/assets/deformable-mesh-drop-evidence.json
- Native shared-node nonlinear elastic volume: 13 nodes, 20 tetrahedra, 0.5 simulated seconds, two exact replays, a half-timestep run, and five whole-mesh rejection checks. It compresses and recovers on a frictionless inelastic plane. The video retains the exact faceted boundary; 101 native states play at 30 fps for 3.367 seconds.
- Files are byte-for-byte copies of the published solver assets. Woven-bag coupling, mesh-resolution convergence, frictional surface contact, physical fruit calibration, and total contact-work closure remain open.

## elastic-mesh-refined-20260929.mp4 and elastic-mesh-refined-20260929.png

- Video: https://github.com/Numi2/numi-solver/blob/97aba9a/docs/assets/deformable-mesh-refined-drop.mp4
- Poster: https://github.com/Numi2/numi-solver/blob/97aba9a/docs/assets/deformable-mesh-refined-drop-37.png
- Mechanics and refinement: https://github.com/Numi2/numi-solver/blob/97aba9a/docs/DEFORMABLE_MESH.md
- Source, binary, geometry, and media fingerprints: https://github.com/Numi2/numi-solver/blob/97aba9a/docs/assets/deformable-mesh-refined-drop-evidence.json
- Newest native shared-node nonlinear elastic volume: 309 nodes, 1,280 tetrahedra, 320 boundary triangles, 0.5 simulated seconds, two exact replays, half-timestep difference at most 135.85 µm, and five whole-mesh rejection checks. All three resolutions preserve the same authored piecewise-flat body and material. The 101 native states play at 30 fps for 3.367 seconds.
- The finer mesh has individually qualified replay/timestep/geometry checks, but spatial convergence remains open: the 160-to-1,280-element matched-node comparison differs by up to 36.39 mm and fails the 1 mm benchmark target. The exact native boundary is rendered without smoothing or posed deformation. Fruit calibration, woven-bag coupling, frictional surface contact, finite bench, and total contact-work closure remain open.
- Files are byte-for-byte copies of the published solver assets. The earlier coarse video remains available at its existing media URL.

## fruit-bag-repaired-cpu96-20260929.mp4 and fruit-bag-repaired-cpu96-20260929.png

- Video: https://github.com/Numi2/numi-solver/blob/33ca2d5/docs/assets/cloth-local-node-pickup.mp4
- Poster: https://github.com/Numi2/numi-solver/blob/33ca2d5/docs/assets/cloth-local-node-pickup-160.png
- Mechanics: https://github.com/Numi2/numi-solver/blob/33ca2d5/docs/FRUIT_FALL.md
- Source, binary, two terminal runs, state, and media fingerprints: https://github.com/Numi2/numi-solver/blob/33ca2d5/docs/assets/cloth-local-node-pickup-evidence.json
- Newest completed CPU FP64 plane-contact trajectory after the local cloth thickness repair: 480 frames, 96 substeps, 32 iterations, four simulated seconds, two matching final physical hashes `0x5496d0e5fd2c9611`. The knot maximum is 0.069257379 rad. Four released fruits finish outside the capped mesh at their support radii with zero vertical velocity, still rolling. All 49 exported states pass the independent contact audit including local node contacts. The 49-frame video plays at 12 fps for 4.083 seconds.
- The 48-substep run also passes but releases three different fruits. Matched fruit centers differ by up to 7.17 metres: passing gates does not establish timestep convergence. Native full-scene spill, fruit deformation, finite-bench full-scene qualification, material calibration, and complete energy closure remain open.
- Files are byte-for-byte copies of the published solver assets. Earlier media URLs remain available.

## Loaded-cloth stress test — September 29, 2026

- `loaded-cloth-stress-20260929.mp4` and `.png` are byte-identical copies of Numi Solver's labeled six-second finite-bench stress media at commit `b467b82`.
- Actual physics source is frozen `4186cfa`; the authored grip CSV is `192aed1`. All source, binary, trajectory, 73 saved state, failed gate and media fingerprints are retained in [the receipt](https://github.com/Numi2/numi-solver/blob/b467b82/docs/assets/finite-bench-loaded-drop-48-evidence.json).
- Both complete 720-frame CPU48 replays match their accepted trajectory hash. After grip release at 3.8 s, saved cloth COM descends 1.739 m and 38 nodes end against the lower floor. Geometry alone does not qualify the scene: contact, strain, ground-correction and speed limits fail. Every video frame carries a persistent failure label.
- These are simulated cloth and rigid-sphere fruit paths. The authored input moves only the compliant seam grip. The newer support/load-response repair is a separate source-bound full run in progress; this video does not qualify it or imply calibrated fruit properties or whole-scene energy closure.

## elastic-mesh-support-10240-20260929.mp4 and .png

- Byte-identical copies of the new support-aware native replay and maximum-compression poster: https://github.com/Numi2/numi-solver/blob/8f344c8/docs/assets/deformable-support-10240.mp4 and https://github.com/Numi2/numi-solver/blob/8f344c8/docs/assets/deformable-support-10240-38.png
- Source, binary, state, renderer, video and independent energy fingerprints: https://github.com/Numi2/numi-solver/blob/8f344c8/docs/assets/deformable-support-evidence.json
- Physics source 6973631; Apple M4 Pro, 2,057 nodes, 10,240 tetrahedra, 0.5 simulated seconds, two exact replays, 307.00 micrometre half-timestep difference and six rejected-state/ledger rollback checks. The exact boundary plays 101 native states at 30 fps for 3.366667 seconds.
- Support-aware velocity Verlet passes the authored 1 percent numerical energy budget: 0.846 percent at 100 us, versus 144.949 percent for Euler at the same mesh and timestep. Its half-step budget is 0.330 percent. The 1,280-to-10,240-element spatial comparison fails at 14.927 mm against 1 mm. This earlier video remains available; the completed 81,920-tetrahedron result is recorded below.

## elastic-mesh-support-81920-20260929.mp4 and .png

- Byte-identical copies of the standalone native volume video and maximum-compression poster: https://github.com/Numi2/numi-solver/blob/5cba5a1/docs/assets/deformable-support-81920.mp4 and https://github.com/Numi2/numi-solver/blob/5cba5a1/docs/assets/deformable-support-81920-38.png
- Source, binary, all exported OBJ hashes, independent geometry and numerical energy audits, and media fingerprints: https://github.com/Numi2/numi-solver/blob/5cba5a1/docs/assets/deformable-support-81920-evidence.json
- The Apple M4 Pro advanced 14,993 shared nodes and 81,920 tetrahedra for 0.5 simulated seconds. The actual native and independent audit exits were both 0. Native replay matched exactly and the 40,000-step half-timestep run differed by at most 93.11 µm from the 20,000-step run. All 101 captured states in each run passed independent geometry and mass checks. The authored 1 percent numerical energy budget passed at 0.254% for the primary run and 0.122% for the half-timestep run.
- All 101 exact exported native boundary states render at 30 fps for 3.366667 seconds. The video uses a fixed camera, with no smoothing or posed deformation. It shows an authored volume and frictionless inelastic plane, not the deformable bag or fruit.
- The matched 25 µs 10,240-to-81,920-tetrahedron comparison differs by up to 9.340864644828101 mm at owning nodes, exceeding the unchanged 1 mm spatial target. Both captured trajectories pass independent geometry and mass audits; spatial convergence fails. Source-bound comparison and evidence: https://github.com/Numi2/numi-solver/blob/318bdc8/docs/assets/deformable-support-matched-25us/spatial.json
- Separate bounded CPU research reproduces a one-microsecond shared yarn/elastic-body normal-block step and studies preventive material-face area admission. Neither is a full cloth/fruit repair: https://github.com/Numi2/numi-solver/blob/634eae1/docs/assets/elastic-yarn-fem-normal-block/README.md and https://github.com/Numi2/numi-solver/blob/0334d79/docs/ELASTIC_YARN_AREA_ADMISSION.md
- Measured material, reciprocal cloth/fruit coupling and complete physical work closure remain open. The previously published 10,240-tetrahedron video stays at its existing URL.

## elastic-mesh-10240-20260929.mp4 and .png (archived)

- Original byte-identical Euler replay/poster at https://github.com/Numi2/numi-solver/blob/0fc556d/docs/assets/deformable-mesh-10240-drop.mp4 and https://github.com/Numi2/numi-solver/blob/0fc556d/docs/assets/deformable-mesh-10240-drop-38.png
- Source and original qualification record: https://github.com/Numi2/numi-solver/blob/0fc556d/docs/assets/deformable-mesh-10240-drop-evidence.json
- This earlier ABI1 video is retained at its existing URL. It does not qualify the later support-aware integrator or establish a small numerical energy bound.

## loaded-cloth-repaired-20260929.mp4 and .png

- Byte-identical six-second repaired CPU FP64 loaded-bag replay: https://github.com/Numi2/numi-solver/blob/0bdb7ca/docs/assets/finite-bench-loaded-drop-repaired.mp4
- Source, binary, all saved states and exact two-replay fingerprints: https://github.com/Numi2/numi-solver/blob/0bdb7ca/docs/assets/finite-bench-loaded-drop-repaired-evidence.json
- Source6f1e450: 720 frames, 48 substeps, 32 iterations, two exact replays, all 73 exported contact states and unchanged solver gates PASS. After grip release at 3.8 seconds, cloth COM descends 1.7166 m, 28 nodes finish on the floor and both spilled fruits land at their floor radii with zero vertical velocity.
- Authored-case qualification does not establish timestep convergence, measured material, native finite-bench execution or whole-scene energy/reaction closure. The earlier failed stress video is retained with its persistent failure label.


## September 29 finer-run and contact update

The loaded-cloth video remains the completed 48-substep `6f1e450` case.
The same-source 96-substep drop completes FAIL at 35.93 m/s versus the unchanged
30 m/s limit, despite all 73 regular saved contact states passing. The finer
pickup also completes FAIL at 56.7 micrometres of fruit/yarn overlap. The new
`bbf111a` coupled contact source reduces the retained peak projection to
0.851 micrometres in one certificate pass. The later complete CPU96 pickup
passed and is documented below.
A separate native Metal geometry probe passes 1,714 cases twice. This is CCD
geometry qualification, not full native cloth/bench execution.

- [Source-bound contact and geometry record](https://github.com/Numi2/numi-solver/blob/df1fd2a/docs/COUPLED_YARN_CONTACT.md)
- [Completed finer loaded-drop failure](https://github.com/Numi2/numi-solver/blob/df1fd2a/docs/assets/finite-bench-load-drop-96-failure.json)
- [Completed finer pickup failure](https://github.com/Numi2/numi-solver/blob/df1fd2a/docs/assets/finite-bench-load-pickup-96-failure.json)
- [Completed native ABI14 plane failure](https://github.com/Numi2/numi-solver/blob/df1fd2a/docs/assets/cloth-metal-local-node-failure.json)

Media bytes and their physical source provenance are unchanged by this text update.

## fruit-bag-coupled-cpu96-20260929.mp4 and .png

- Newest full CPU FP64 finite-tabletop/lower-floor pickup from physics source `bbf111ae4a761ea68b8906a0084120b805a59b9d`: 480 frames, 96 substeps, 32 iterations, two complete four-second replays, actual exit 0 / PASS.
- Record and source/binary/video receipts: https://github.com/Numi2/numi-solver/blob/09d8ca1/docs/assets/coupled-bench-pickup-96-evidence.json
- Both complete 481-frame fruit traces match. Released fruit 1, 4, 9, 10 and 11 finish supported on the lower floor; maximum final vertical speed is 5.492e-13 m/s. All 51 regular/peak saved states pass independent contacts.
- Worst accepted fruit/yarn overlap is 0.07988 micrometres, below the unchanged 2-micrometre limit; max certificate passes is 3, with 2,920 simultaneous contact blocks and zero fallbacks. Max speed is 14.0719 m/s.
- Video/poster are byte-identical copies of solver assets. Every regular saved state is rendered from one fixed trajectory camera without smoothing or dynamic interpolation. 49 saved states become 98 held video frames at 24 fps, duration 4.083333 seconds for four simulated seconds.
- This passing CPU cloth/rigid-sphere scene does not qualify deformable fruit, temporal convergence, calibrated material, native full spill or whole-scene work/reaction closure.
- Native focused response passes 104 cases twice. A separate Apple Metal finite-bench pickup then completed two exact 480-frame replays but returned actual exit 1 / FAIL. Released fruits 8 and 9 remain airborne at terminal frame 480, with static clearances +0.93057 m and +0.41773 m; the grounded released-fruit count is zero against a gate of at least two. All 49 unique saved states pass the independent contact audit, but the strict landing gate fails. [Complete source-bound native terminal audit](https://github.com/Numi2/numi-solver/blob/f713d8f/docs/assets/native-finite-repaired-pickup-audit/README.md).
- Research comparison targets are explicitly open: https://github.com/Numi2/numi-solver/blob/f713d8f/docs/DEFORMABLE_FRONTIER.md
