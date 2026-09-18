# CADET Anonymous Review Artifact

This repository hosts the anonymous review artifact for a SANER 2027 submission.

The release asset contains the implementation snapshot, recorded configurations, raw experimental results, and analysis scripts. It contains no API credentials.

## Verification

Download both release assets and verify the archive before extraction:

```bash
shasum -a 256 -c CADET_SANER2027_review_artifact_v2.zip.sha256
```

After extraction, run `sh reproduce_analysis.sh` from the artifact root to audit the stored RQ2--RQ4 analyses without an LLM credential. See `README.md`, `ARTIFACT.md`, and `RESULTS_MAP.md` inside the archive for details.
