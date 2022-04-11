# Relativity.Transfer.Client Version Compatibility

[![nuget](https://img.shields.io/nuget/v/Relativity.Transfer.Client.svg)](https://www.nuget.org/packages/Relativity.Transfer.Client)

The Relativity Transfer Client .NET SDK package.

## 7.4.9

### Release Notes

## Changed

Exposed custom completion timeout to avoid never ending threads causing thread pool starvation.

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
11.2.0.0 | latest

## 7.4.8

### Release Notes

## Changed

Relativity.DataTransfer.Legacy.SDK updated to 0.2.16.

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
11.2.0.0 | latest

## 7.4.7

### Release Notes

## Changed

Improved logging in Direct Mode.

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
11.2.0.0 | latest

## 7.4.6

### Release Notes

#### Fixed

* TAPI no longer causes UI hangs when callled by an UI thread.

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
11.2.0.0 | latest

## 7.4.5

### Release Notes

#### Changed

* Performance improvements related to changes introduced in version 7.4.2.

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
11.2.0.0 | latest

## 7.4.2

### Release Notes

#### Changed

* This release introduce set of internal and backward compatible changes related to Relativity's journey to being cloud-native. There are no changes impacting the clients.

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
11.2.0.0 | latest

## 7.3.12

### Release Notes

#### Fixed

* Failing jobs when 100% of transferred files are missing but they were reported as warnings

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
11.2.0.0 | latest

## 7.3.11

### Release Notes

#### Fixed

* An issue that caused an error _failed to authenticate_ when Aspera credentials were modified during the transfer

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
11.2.0.0 | latest

## 7.3.10

### Release Notes

#### Fixed

* System.InvalidOperationException caused by the filter of statistics logs

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
11.2.0.0 | latest

## 7.3.9

### Release Notes

#### Fixed

* Unversioned libraries are no longer used

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
11.2.0.0 | latest

### Supported RAP Version Range

Lowest Version | Highest Version
--- | ---
N/A | N/A

## 7.3.8

### Release Notes

#### Fixed

* Preserve Last Accessed Timestamp in direct mode

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
11.2.0.0 | latest

### Supported RAP Version Range

Lowest Version | Highest Version
--- | ---
N/A | N/A

## 7.3.7

### Release Notes

#### Changed

* Reduced amounf of excessive logging in Aspera Provider

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
11.2.0.0 | latest

### Supported RAP Version Range

Lowest Version | Highest Version
--- | ---
N/A | N/A

## 7.3.5

### Release Notes

#### Changed

* Enhanced logging around fatal Aspera errors

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
11.2.0.0 | latest

### Supported RAP Version Range

Lowest Version | Highest Version
--- | ---
N/A | N/A

## 7.3.4

### Release Notes

#### Fixed

* The TCP port check when FISP-mode is enabled

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
11.2.0.0 | latest

### Supported RAP Version Range

Lowest Version | Highest Version
--- | ---
N/A | N/A

## 7.3.3

### Release Notes

#### Fixed

* Number of logs logged by TAPI to client logger is reduced
* System.OutOfMemoryException caused by the calculation of a relative path

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
11.2.0.0 | latest

### Supported RAP Version Range

Lowest Version | Highest Version
--- | ---
N/A | N/A

## 7.3.0

### Release Notes

#### Fixed

* Win32 FileTime issue.
* Enumeration results for network drive issue.

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
11.2.0.0 | latest

### Supported RAP Version Range

Lowest Version | Highest Version
--- | ---
N/A | N/A
