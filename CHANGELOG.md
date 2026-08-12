# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [5.22.10+2.0.0]
### Fixes
- **BREAKING:** Raise the iOS deployment target from 9.0 to 16.0. Xcode 27 rejects pods below the SDK's minimum supported deployment target, which turned the inherited 9.0 value into a build error [RDMR-1423](https://outsystemsrd.atlassian.net/browse/RDMR-1423)

## [5.22.10+1.0.0]
### Changes
- Toolbar is smaller [RNMT-3280](https://outsystemsrd.atlassian.net/browse/RNMT-3280) [RNMT-3515](https://outsystemsrd.atlassian.net/browse/RNMT-3515) [RNMT-5718](https://outsystemsrd.atlassian.net/browse/RNMT-5718)
- Toolbar button now navigates directly to network screen [RNMT-3598](https://outsystemsrd.atlassian.net/browse/RNMT-3598) [RNMT-5718](https://outsystemsrd.atlassian.net/browse/RNMT-5718)

### Removals
- **BREAKING:** Remove buttons for features we do not support [RNMT-3280](https://outsystemsrd.atlassian.net/browse/RNMT-3280) [RNMT-5718](https://outsystemsrd.atlassian.net/browse/RNMT-5718)
- **BREAKING:** Disable simulator keyboard shortcuts [RNMT-3280](https://outsystemsrd.atlassian.net/browse/RNMT-3280)

### Fixes
- Remove string references to FLEX [RNMT-3597](https://outsystemsrd.atlassian.net/browse/RNMT-3597) [RNMT-5718](https://outsystemsrd.atlassian.net/browse/RNMT-5718)

[Unreleased]: https://github.com/OutSystems/FLEX/compare/5.22.10+2.0.0...outsystems
[5.22.10+2.0.0]: https://github.com/OutSystems/FLEX/compare/5.22.10+1.0.0...5.22.10+2.0.0
[5.22.10+1.0.0]: https://github.com/OutSystems/FLEX/compare/5.22.10...5.22.10+1.0.0
