# Validation record

Date: 2026-10-04. Cleanup baseline commit: `ee4a45285816b56f1c466de554bd939eeff1c806`.

## Preservation and structure

- 5 retained blobs are unchanged at their current paths.
- 0 generated build/cache/executable entries are omitted from the current tree; the baseline history remains available.
- New documents and required configuration/path adaptations are recorded in the cleanup pull request. No existing source history is rewritten.
- Current filenames have no case-insensitive collisions. Markdown file links and generated-output ignore rules are checked before publication.

## Checks and limits

- All four OpenMV/MicroPython scripts preserve the original Git blob bytes.
- Desktop syntax compilation is not a hardware test and was not substituted for an OpenMV run.
- External PID modules, board firmware, wiring, camera conditions, and serial-connected hardware remain reproduction requirements.

