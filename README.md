## Reproduce:

- Clone this repo.
- `cd` into the repo directory.
- Run `testem`

## Probs:

The js file has a syntax error, so browserify will fail.

`before_tests` runs browserify and fails and the testem interface just hangs rather than reporting an error.

In contrast, `testem ci` reports the `before_tests` error.
