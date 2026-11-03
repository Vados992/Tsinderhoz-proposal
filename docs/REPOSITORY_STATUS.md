# Repository recovery record

Author / architect: Vadym Tsinderhoz. Checked: 3 November 2026.

## Evidence

- Initial commit: `423875dc3d665adfdf28aeaf817e352f61da5ef7` contained only `LICENSE`.
- Pre-correction main: `f9f6ddb175c0f9ba8f5931713d223be9220d2eb6` contained `README.md` and `LICENSE`.
- Only available branch: `main`; no releases or workflow runs were found.
- A title search of saved project material found the architecture PDF, but no matching source archive. This is a scoped search, not proof that no other copy exists anywhere.
- The previous README referenced missing `docs/API.md`, `schemas/`, `docs/SAFETY_CASE.md`, `docs/REAL_WORLD_LIMITS.md`, `NOTICE.md` and `CITATION.cff`.

## Correction

The root README now states the actual repository condition and links only to existing local files. The historical software description is retained in `IMPLEMENTATION_PLAN.md` as an unimplemented contract. Unsupported CI badges and executable installation instructions were removed from the root README. License text was preserved.

## Still required

- Authenticated source recovery or a clearly identified new implementation.
- Actual code, tests, configuration, registries, schemas and controlled reference assets.
- Real build and test evidence tied to a commit.
- A consistent, explicitly chosen licensing policy for future work.

Documentation accuracy is repaired. Application implementation remains open.
