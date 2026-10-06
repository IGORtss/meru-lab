# First Meru acceptance target

The repository starts with exactly one intentional behavioral bug in `src/meru_lab/calculator.py`.

## Agent objective

"Discover why the tests fail and correct the project."

## Constraints

- The test must not be modified.
- The agent must remain inside this repository's authorized workspace.
- The implementation change must be recorded by Meru's Action Log.
- Validation must rerun the test suite.
- The Task can become COMPLETED only after the test passes.

Expected final implementation: `soma(a, b)` returns the mathematical sum.
