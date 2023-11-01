# Relativity Kepler Client SDK Version Compatibility

[![nuget](https://img.shields.io/nuget/v/Relativity.Kepler.Client.SDK.svg)](https://www.nuget.org/packages/Relativity.Kepler.Client.SDK)

The Relativity Kepler Client SDK for our Kepler Client APIs.

### Release Notes

## v2.21.0

- When a .NET consumer is rate limited and receives an HTTP 429 from Kepler's rate limiter, a generic ServiceException is thrown.
- New exception type provides Retry-After header value.

## v2.20.0
- Multitarget Relativity.Services.Proxy to netstandard2.1
- Multitarget Kepler to netstandard2.0
- Pool HttpClient connections.
  - Controlling Toggles:
    - Relativity.Data.Toggles.DisableServiceProxyHttpClientPooling
    - Relativity.Data.Toggles.DisableServiceProxyHttpCompression
- Add HTTP status code to the kepler error logging
- Set the MaxDepth default for JSON serialization and deserialization
- Reduce Kepler timeout to 20 min from 1 hour
- Replaced System.Management.Automation library with PowerShellStandard.Library
- Add RequestController. Allows reading of headers within a service.
- Updates to support CookieCollection as to prevent improper loadbalancing.
- Fixed errors when providing alternate IKeplerStream implementations.
- Update Owin dependencies from 3.0.1 -> 4.2.0
- Update YamlDotNet from 3.3.1 -> 5.1.0.

## v2.14.4

Initial Version

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
11.3.185.7 | Latest
