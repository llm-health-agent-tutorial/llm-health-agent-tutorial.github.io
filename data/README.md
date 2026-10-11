# Teaching data

The tutorial uses the official public GLOBEM sample: 10 participants and 481 feature-day rows per sensing table. The package includes the source notices and codebook; it does not include credentialed GLOBEM records. The lab package and sample data will be shared during the session.

## Archived notebook data profiles

The profiles below describe the earlier notebook edition. Its course, speaker and schedule documents are superseded by the current browser-based tutorial.

Two explicit profiles ship in the complete bundle:

- `starter/data/processed/`: 12 fully synthetic users over 112 days. This separate Module-5 scenario supports the reproducible sleep, screen-use and deadline-confound exercise.
- `starter/data/globem_hybrid/processed/`: the default main exercise: official public GLOBEM sample observations (10 users, 481 person-days) with separately labeled synthetic supplements. Every field has provenance. Observed missing values stay missing.

Both profiles include codebooks, data cards and reproducible builders. The GLOBEM sample night window is 00:00–06:00; the synthetic scenario uses 22:00–02:00. Do not silently pool them. This is the official public sample, not the full credentialed PhysioNet release. Synthetic additions are invented teaching values, not facts about source participants. Upstream files retain their license and attribution.
