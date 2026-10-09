# Relativity.Analytics.Classification.SDK Version Compatibility

[![nuget](https://img.shields.io/nuget/v/Relativity.Analytics.Classification.SDK.svg)](https://www.nuget.org/packages/Relativity.Analytics.Classification.SDK)

This package contains interfaces for the public APIs of Analytics Core's Classification Indexes.

## v2.0.0

### Release Notes

* **Breaking:** the assembly and namespaces changed from `Relativity.Analytics.Classification` (`Relativity.Analytics.Classification.v1.Services`, `.v1.Models`) to `Analytics.Classification.Service.Interfaces.Public` (`Analytics.Classification.Service.Interfaces.Public.v1`, `.v1.Models`). Update your `using` statements. REST routes are unchanged.
* New `SubmitJobAsync` overload with an `originator` Guid.
* New `ClassificationIndex.PretrainedModel` property.
* Updated NuGet icon to current Relativity logo.

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
11.3.72.29 | Latest

### Analytics Core RAP Version Range

Lowest Version | Highest Version
--- | ---
3004.4.0 | Latest

## v1.0.1

### Release Notes

Initial Version

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
11.3.72.29 | Latest

### Analytics Core RAP Version Range

Lowest Version | Highest Version
--- | ---
3001.1.1 | Latest

