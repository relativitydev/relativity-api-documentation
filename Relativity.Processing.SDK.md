# Relativity.Processing.SDK Version Compatibility

[![nuget](https://img.shields.io/nuget/v/Relativity.Processing.SDK.svg)](https://www.nuget.org/packages/Relativity.Processing.SDK)

This package contains interfaces for the public APIs of the Relativity Processing application.

## 12.2.13

### Release Notes

* WCF endpoints have been replaced with Kepler equivalents, and no WCF is used by the Processing APIs.
* Removed the Processing Profile Manager API endpoint, consumers should now use Object Manager API.
* Addition of a versioned v1 API surface, consumers are highly encouraged to transition to these APIs.

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
12.1.0.0 | Latest

### Supported RAP Version Range

Lowest Version | Highest Version
--- | ---
12.1.0.0 | Latest