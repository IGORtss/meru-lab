# Meru Lab

Small intentionally broken Python project used as the first end-to-end target for the Meru Developer Agent.

## Expected initial state

`soma(2, 2)` incorrectly returns `0`, while the test expects `4`.

The Developer Agent should diagnose and fix the implementation without modifying the test or leaving the authorized workspace.
