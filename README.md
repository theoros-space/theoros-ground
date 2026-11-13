<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/theoros-space/theoros-brand/main/logo/svg/mark-paper.svg">
  <img src="https://raw.githubusercontent.com/theoros-space/theoros-brand/main/logo/svg/mark-ink.svg" width="44" align="right" alt="Theoros">
</picture>

# theoros-ground

**04  Customer API and mission dashboard.** Part of the [Theoros](https://github.com/theoros-space) onboard AI product.

[![License: Theoros Source-Available 1.0](https://img.shields.io/badge/license-source--available-FF4B1F)](LICENSE)

> **Status: pre-release.** This repository is public so partners can follow our work. Source code lands here from December 2026.

## What it is

Where operators work with Theoros: register satellites and sensor profiles,
choose models, schedule deployments and see what their satellites found.

- **API:** satellites, sensor profiles, deployments, results.
- **Dashboard:** per-satellite results, downlink saved, model health in orbit.
- **Telemetry:** model performance from orbit feeds back into retraining.

## Planned layout

```
api/          OpenAPI specification
backend/      services
frontend/     dashboard
docs/         requirements and data model
```

## Requirements

Requirements are listed in [docs/REQUIREMENTS.md](docs/REQUIREMENTS.md) with
the prefix `GND-REQ`. Every requirement is verified by a test, an
analysis or an inspection, and referenced in the pull request that changes it.

## Contributing

See the organisation [contributing guide](https://github.com/theoros-space/.github/blob/main/CONTRIBUTING.md).
Outside contributions need a signed [CLA](https://github.com/theoros-space/.github/blob/main/CLA.md).

## License

Source-available under the [Theoros Source-Available License 1.0](LICENSE).
You may read and evaluate it; any use, copy or deployment needs a written
license from Theoros. Contact licensing@theoros.space.
