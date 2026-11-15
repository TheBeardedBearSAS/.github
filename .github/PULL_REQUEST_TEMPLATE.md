## Summary

<!-- What changes and why. Link the issue or the official URSSAF document if relevant. -->

## Checklist

- [ ] `make ci` is green (coverage 100 %, MSI 100 %, PHPStan max, Mago, Deptrac, hadolint...)
- [ ] Benchmarks added or updated when the change touches validation or wire encoding/decoding (`make bench`)
- [ ] `CHANGELOG.md` updated (`[Unreleased]`) for any user-visible change
- [ ] Documentation (`docs/`, README) updated when behaviour or configuration changes
- [ ] No real credentials or personal data anywhere (code, fixtures, logs)
