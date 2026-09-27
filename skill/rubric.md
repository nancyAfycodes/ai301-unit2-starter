# Rubric: is this reproduction package ready to post?

## Checks

| Check | Evidence | Pass condition | Weight |
|---|---|---|---|
| Environment recorded | Repro report's environment section | Lists Python version, test framework, and file paths affected | required |
| Steps are complete | Repro report's reproduction steps | Steps are numbered and detailed enough to follow without the issue description | required |
| Behavior matches issue | Repro report's output/error section | Shows the indent-as-code-block parsing defect described in issue #71 | required |
| Outcome stated clearly | Repro report's conclusion | Explicitly states whether bug was reproduced and what was verified | required |
| Repo conventions respected | Claim comment and repro report text | Follows Path Review's comment style (no excessive formatting, clear structure) | preferred |

## Verdict rule

Accept if: All required checks pass.
Reject if: Any required check fails.
Unclear: Treat as fail and reject.