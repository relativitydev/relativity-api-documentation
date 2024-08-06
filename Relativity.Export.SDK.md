# Relativity.Export.SDK

[![nuget](https://img.shields.io/nuget/v/Relativity.Export.SDK.svg)](https://www.nuget.org/packages/Relativity.Export.SDK)

The Relativity Export SDK package contains interfaces for interacting with Relativity Export APIs via .NET.

## 3.4.1

### Release Notes

* Added IsOutputDeleted property to ExportJob
* Added DeleteAsync endpoint in IExportJobManager

## 3.3.5

### Release Notes

* Added MsAccessMappingSettings to ExportJobSettings
* Added LoadfileNameFormat  to LoadFileSettings

## 3.3.1

### Release Notes

* Add TransferJobID to ExportOutputSettings
* Enable saving export results using provided transfer service job
* Add new properties ExportedFiles and TotalSizeOfExportedFiles to exportJob related to exported files
* Move IHealthManager to Relativity.Export.SDK

## 3.2.7

### Release Notes

- Implemented `DateTimeFormat` to `LoadFileSettings` to allow for custom date time formats.

## 3.2.1

### Release Notes

* Initial Version Release

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
14.8 | Latest