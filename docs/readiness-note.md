# Release Readiness Note

The default branch's audit workflow writes a small text file on every push
and uploads it as the `audit-evidence` artifact, so retention is
verifiable rather than assumed. This note is intentionally short, so the
release manager can quickly confirm that the artifact produced by the
release-readiness-audit-5 workflow is reachable.

Issue #1 (the release checklist) documents the documentation step; issue #2
covers confirming artifact retention. A review comment will be left on this
note as part of the evidence trail.
