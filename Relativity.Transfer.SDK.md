# Relativity.Transfer.SDK Version Compatibility

[![nuget](https://img.shields.io/nuget/v/Relativity.Transfer.SDK.svg)](https://www.nuget.org/packages/Relativity.Transfer.SDK)

The Relativity Transfer .NET SDK package.

## v2.0.0

### Release Notes

#### Breaking changes:
- `AzureTransferFullPathClientBuilder` and `AzureTransferJobClientBuilder` now require a workspace context, which can be specified by the workspace's ID or using Staging Explorer privileges.
- Cancelled directory transfers will no longer throw `OperationCancelledException`. Instead, a result with a "Cancelled" state will be returned.
- If the client's implementation of `IRelativityAuthenticationProvider` throws an exception, the SDK will now throw a `FailedToAcquireCredentialsException`.

#### New Features:
- Introduced `OvewritePolicy` in `OptionsBase` for implementing policies to handle file skipping and overwriting at the destination.
- `AzureTransferJobClient` now supports uploading a list of files to the fileshare.
- Added the ability to specify the location of journal files in transfer options.

#### Improvements:
- Improved handling of I/O errors on Windows for better reliability and troubleshooting.
- Transfer SDK will now automatically remove journal files older than 28 days to optimize storage.

#### Other:
- Support for legacy fileshares has been discontinued since all clients have successfully migrated to the new storage.

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
13.2.0.0 | Latest

## v1.28.0

### Release Notes

- Introducing new way of storage authentication
- Added SkipTransferringEmptyDirectories setting for directory-based transfers
- Enhancements in telemetry area

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
13.2.0.0 | Latest

## v1.23.0

### Release Notes

- Progress updates have a new property - `StepType` that strongly defines from which step progress report comes from
- TransferSDK throws meaningful exception when it fails to acquire storage path
- Set of improvements in observability area

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
13.2.0.0 | Latest

## v1.21.0

### Release Notes

- Fixed an issue that caused `OutOfMemoryException` when multiple fails or skips occur during a transfer.
- Set of internal changes that improve TransferSDK observability.

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
13.2.0.0 | Latest

## v1.20.1

### Release Notes

Added `JobBasedWorkflow` to `TransferJobClient` it allows to create client that will require only one path to be provided.
Removed vulnerable package `Cleary.AsyncExtensions`.

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
13.2.0.0 | Latest

## v1.18.0

### Release Notes

Minor improvements around statistics reporting

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
13.2.0.0 | Latest

## v1.16.0

### Release Notes

Added functionality to download a file or a directory from Relativity fileshare (legacy and ADLS based)
Added support for reporting of skipped/failed/succeeded files during synchronizations
Fixed numerous security vulnerabilities
Fixed a few minor issues

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
13.2.0.0 | Latest

## v1.8.1

### Release Notes

Fixed possible runtime issue with assembly version

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
13.2.0.0 | Latest

## v1.8.0

### Release Notes

Added support to download data directly to a drive as well as upload from a drive

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
13.2.0.0 | Latest

## v1.6.0

### Release Notes

Added support for exclusion policy
Fixed status translation of a cancelled transfer job

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
13.2.0.0 | Latest

## v1.3.0

### Release Notes

Improved job registration and exposed retry policy option

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
13.2.0.0 | Latest

## v1.2.0

### Release Notes

Fixed issue where transfer got stuck

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
13.2.0.0 | Latest

## v1.1.1

### Release Notes

Added skip top level directory

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
13.2.0.0 | Latest

### Supported RAP Version Range

Lowest Version | Highest Version
--- | ---
1.2.13.0 | Latest

## v1.0.3

### Release Notes

Initial Version

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
13.2.0.0 | Latest

### Supported RAP Version Range

Lowest Version | Highest Version
--- | ---
1.2.13.0 | Latest
