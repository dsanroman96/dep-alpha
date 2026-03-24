# dep-alpha

Generic dependency repository used to test cross-repository dependency propagation.

## Release process

- Run the `Release` GitHub Actions workflow manually.
- Choose a bump type: `patch`, `minor`, or `major`.
- The workflow updates `VERSION`, creates a commit, tags it as `vX.Y.Z`, and publishes a GitHub Release.
