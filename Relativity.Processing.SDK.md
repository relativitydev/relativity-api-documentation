# Relativity.Processing.SDK Version Compatibility

[![nuget](https://img.shields.io/nuget/v/Relativity.Processing.SDK.svg)](https://www.nuget.org/packages/Relativity.Processing.SDK)

This package contains interfaces for the public APIs of the Relativity Processing application.

## 12.2.13

### Release Notes

* Bumped the Invariant Services package for ARM statistics endpoint defect fix. Fixed error field removals.
* Added a NuGet package for Password Bank, renamed Password Bank tab, and moved from ApplicationBase.
* Resolved dependency injection issues and removed low-use RSAPI code, along with legacy test projects.
* Removed redundant Kepler endpoint check for ValidateApiEndpoints API, removed ProcessingBase package and consolidated projects into Relativity.Eca.
* Added a new private endpoint for updating count after Post Publish Delete job.
* Use Object Manager instead of RSAPI for Custodian, Processing Set and Processing Data Source updates.
* Started using new Shared.ApplicationBase package with contract changes to IContextContainer.
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