# Reproduction inventory

## Current state

The repository includes the final report and documentation. It does not currently include the source files needed to reproduce the questionnaire analysis or maps. This inventory records what to recover, rather than implying that those files already exist here.

| Required input | Current status | What to establish |
|---|---|---|
| Original GIS project | Not supplied | Project format, software version, layer paths |
| Spatial layers | Not supplied | Source, edition/date, geographic extent, reuse terms |
| Attribute tables | Not supplied | Field definitions, units, join keys, missing values |
| GPS field observations | Not supplied | Observation dates, recording protocol, positional accuracy |
| Raw questionnaire responses | Not supplied | Coding, missing-response rules, consent and permitted reuse |
| Analysis files | Not supplied | Statistical steps, scripts or saved workflows, settings |
| Map layouts | Available only inside the report | Original symbology, classifications, scales, exports |
| Data dictionary | Not supplied | Meaning, units, provenance, and valid values for each field |

## Recovery and validation sequence

1. Recover a copy of the original project folder and inventory files before changing them.
2. Establish data sources, dates, reuse terms, and the geographic units used in each layer.
3. Document the coordinate reference system and transformation of each spatial input.
4. Check attribute types, missing values, duplicate identifiers, and join coverage.
5. Reproduce the questionnaire counts and denominators from an appropriate non-identifying dataset, if available.
6. Regenerate one map with documented settings and compare it with the report.
7. Explain discrepancies before expanding the workflow or publishing additional conclusions.
8. Save the completed workflow, environment details, and instructions alongside its outputs.

## Completion criteria for a later reproducible edition

- Each published output links to identifiable input data and documented processing steps.
- An appropriate user can reproduce the output using the supplied instructions and accessible inputs.
- Checks address join completeness, units, missingness, and the numerical summaries that matter to the findings.
- Differences from the original report are recorded, including changes in data vintage or study area.
- Any replacement data or newly written workflow is clearly labelled as a later recreation.

Until those criteria are met, describe this repository as a report archive with a reproduction roadmap.
