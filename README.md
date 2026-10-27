# Traditional Chinese Hundred-Ke Clock

**InfiltratorOS clock resource** · **Stable ID:** `chinese-ke` · **Module:** `Traditional Chinese Hundred-Ke Clock.so`

Exactly one hundred kè divisions of the civil day.

**Historical scope/accuracy:** A Han-era-style model, not all historical 96-kè or variable traditions.

**Intended installation:** `/System/Resources/Clocks/Traditional Chinese Hundred-Ke Clock.so` (case-sensitive)

The clock owns both its notation and next-visible-tick scheduling. It does not require user-supplied geographic coordinates for its stated model. Elapsed-duration calculations in Common do not provide a fallback absolute clock-face implementation.

## Status

**Source copied and build verified.** This repository contains the implementation of `chinese-ke`, the supporting code it needs, a one-provider `Makefile` and focused regression fixtures. The copy is based on Common 1.19.78 at `8d60662114e3`; the original Common source remains unchanged.

Run `make` to produce `build/Traditional Chinese Hundred-Ke Clock.so` and `make check` to run this provider's checks. No Common checkout or Common archive is required. The current combined Common package and its installation ownership remain in place; this copy does not introduce an independent installer or release.

See [source provenance and build details](SOURCE.md), [source manifest](SOURCE-MANIFEST.json) and [recorded validation](VALIDATION-RESULTS.json).

## Documentation

- [Model and evidence](docs/MODEL.md)
- [Architecture and ownership](docs/ARCHITECTURE.md)
- [Validation requirements](docs/VALIDATION.md)
- [Roadmap](docs/ROADMAP.md)
- [Documentation index](docs/README.md)

## Existing authoritative sources

- [Libraries/Common temporal sources](https://github.com/Infiltrator-Projects/Libraries/tree/main/resources/temporal)
- [Current canonical build catalogue](https://github.com/Infiltrator-Projects/Libraries/blob/main/resources/temporal/Makefile)
- [Calendar chronology and clock models](https://github.com/Infiltrator-Projects/Calendar/blob/main/docs/MODELS.md)
- [Historical fidelity audit](https://github.com/Infiltrator-Projects/Libraries/blob/main/docs/TEMPORAL_HISTORICAL_FIDELITY.md)
- [Temporal discovery and executable provider ABI](https://github.com/Infiltrator-Projects/Libraries/blob/main/docs/TEMPORAL_PROVIDERS.md)
