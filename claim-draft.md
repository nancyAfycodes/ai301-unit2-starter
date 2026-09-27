<!-- I'm claiming this issue to reproduce and fix it.

**Issue:** The heading hierarchy test fixture has an 8-space indentation 
that's being parsed as a code block instead of test content, causing the 
heading hierarchy check to fail.

**Repo status:** The repo is actively maintained — the last commit was 
on 2026-09-16, 11 days ago.

**What I'll do:**
1. Set up the repo environment
2. Reproduce the bug by running the failing test
3. Document the exact behavior in a detailed repro report
4. Submit a fix

I'm a CodePath student working on my first contribution. I'll follow the 
project's conventions and provide clear documentation of my work. -->

**Update**
I'm claiming this issue and have already reproduced the bug.

**Issue:** Issue #71 — The heading hierarchy test fixture has an 8-space indentation 
that's being parsed as a code block instead of test content.

**Repo status:** Last commit was on 2026-09-16, 11 days ago.

**Reproduction:** Successfully reproduced the bug. The test fixture's 8-space indent 
causes Markdown to parse it as a code block, breaking heading extraction.

**Next:** I will fix the indentation and remove the @pytest.mark.xfail marker (H-04).