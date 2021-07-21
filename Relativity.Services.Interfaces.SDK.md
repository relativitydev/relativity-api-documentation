# Relativity.Services.Interfaces.SDK Version Compatibility

![Nuget](https://img.shields.io/nuget/v/Relativity.Services.Interfaces.SDK)

Contains interfaces for most Relativity legacy APIs.

## v13.5.0

### Release Notes
- Added properties to EventHandlerStatus to help debugging of failing event handlers during create and update
- Updated xml for Single Object and Multiple Object FieldValuePair as being RelativityObjectValue
- Added explicit conversion from RelativityObjectRef to RelativityObjectValue
- Added new method to enable caller to avoid issues with mapping groups between case and admin
- Added the object type name to the sublist identifier returned in the object rules API
- Drop unused dependency on Relativity.Kepler.Service

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
11.3.72.29 | Latest

## v13.2.8

### Release Notes

Initial Version

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
11.3.72.29 | Latest
