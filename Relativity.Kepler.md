# Relativity.Kepler Version Compatibility

[![nuget](https://img.shields.io/nuget/v/Relativity.Kepler.svg)](https://www.nuget.org/packages/Relativity.Kepler)

The Relativity Kepler SDK for our Kepler APIs.

## v2.14.4
- Created Relativity.Kepler.Client.SDK NuGet package.
- Fixed an issue where Kepler serializers cannot have the same name when used in different versioned/unversioned services.
- Add includeTransitiveAssemblies boolean optional setting to limit transitive dependency during open api doc build, fix output folder for version/unversioned api case
- Created Relativity.Kepler.Client.SDK NuGet package.
- Fixed an issue that would prevent using attributes on services which take a type argument. Previously, kepler code gen would output invalid syntax.
- Fix KeplerStream response headers copy method and add pinning tests for correct behavior.
- Update jQuery in Kepler SelfHost project to comply with security requirements. JQuery is being kept because it is used for an example to demonstrate streaming with Javascript.
- Remove old/unused API Explorer code to comply with JQuery security requirements.
- Fixed bug with 2.10.0 KeplerStream.ContentTypes change that was preventing Custom Headers from being applied when Content-Type header was null or empty.
- Set TypeNameHandling.None for KeplerCatalog deserialization

### Release Notes
Place new features and updates the user would like to know about here

### Supported Relativity Version Range
Lowest Version | Highest Version
--- | ---
11.3.185.7 | Latest

## v2.10.2

### Release Notes

Initial Version

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
11.3.185.7 | Latest