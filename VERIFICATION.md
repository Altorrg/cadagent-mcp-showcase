# Verification scope

Updated: **30 October 2026**.

## Recorded CAD example

The five-minute video presents a specific cross-section and plan-annotation workflow prepared in October 2026. It is edited and includes labelled speed changes. It is evidence of the shown workflow, not a general reliability or performance benchmark and not a recording of the current R41 local-model acceptance test.

## Current local-model work

- The R41 development comparison used real model inference with a simulated CAD executor. Results from development scenarios are not an untouched benchmark and do not measure broad CAD competence.
- A separate Civil 3D process and a synthetic drawing were used for one native line-copy / readback / owned-undo sequence. Geometry in exported snapshots was checked after reopening them.
- A distinctly named assembly built from the project source was used in that isolated host. This does not establish final packaged-DLL installation acceptance across supported environments.
- The complete tool surface, all target Civil versions and broad visual engineering acceptance have not been validated by that one sequence.

## Fine-tuning

A small QLoRA experiment trained an adapter on synthetic tool-use trajectories. A loss reduction did not translate into demonstrated task-level improvement in the recorded strict evaluation. The adapter was not promoted or distributed. A later training attempt has no completed acceptance result; the latest local check found no active trainer.

## Publication boundary

Only four files are intended for this public showcase: `README.md`, `VERIFICATION.md`, `media/demo.mp4` and `media/preview.jpg`.

No application source code, executable, DLL, installer, tool-contract catalogue, credentials, local connection/session information, training dataset, model weights or editable drawing is included. Downloading this repository does not provide a working CadAgent installation.

The project remains under development. Human review of CAD changes and engineering results is required.
