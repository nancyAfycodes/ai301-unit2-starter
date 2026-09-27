# Rubric: is this reproduction package ready to post?

## Checks

| Environment recorded | Repro report's setup section | Environment details are present (Python version OR test framework OR system info) | required |
| Steps are complete | Repro report's steps section | Steps are provided and describe how to trigger the issue | required |
| Behavior matches issue | Repro report's output section | Output demonstrates the indent-as-code-block parsing problem: a fixture with eight-space indentation is parsed as a code block, causing the heading hierarchy test to fail | required |

## Verdict rule

Accept if: All required checks pass.
Reject if: Any required check fails.
Unclear: Treat as fail and reject.