# Relativity.Productions.SDK Version Compatibility

[![nuget](https://img.shields.io/nuget/v/Relativity.Productions.SDK.svg)](https://www.nuget.org/packages/Relativity.Productions.SDK)

This package contains interfaces for the public APIs of the Relativity Production application.

## v12.6.1

### Release Notes

Added
* Added GetProductionPreviewAsync endpoint to Relativity.Productions.Services.V1.IProductionManager
* Added GetProductionWorkloadAsync endpoint to Relativity.Productions.Services.V1.IProductionManager
* Added a v2 copy Of IProductionDataSourceManager and IProductionManager
* Added Kepler Serializer for V2 Numbering objects
* Added PDF to production placeholder type
* Added PDF to production data source
* Added PDF to V1 PlaceholderType enum
* Added Copied status to RedactDocumentStatus enum
* Added DocumentsWithPdfs, PdfsRedacted, PdfsRemaining, PdfsErrored properties to the V2.DTOs.ProductionProgress model.
* Added DocumentsWithPdfs properties to the V2.DTOs.ProductionMetadata model.

Changed
* Updated the V2 IProductionDataSourceManager API contracts to include Native Redact specific fields.
* Updated the V2 ProductionProgress DTO to include fields for native redaction progress.
* Updated the RedactDocumentResult model to also store file size in bytes.
* Updated route and method name to GetCustomPlaceholderTextAsync
* Fixed file size field for native redacted files
* Updated PdfsRedacted to be PdfsBranded.

Removed
* Removed PDF from PlaceholderType enum

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
12.1.158.12 | Latest

### Supported RAP Version Range

Lowest Version | Highest Version
--- | ---
14.1.2 | Latest

## v12.1.13

### Release Notes

Contains Production Numbering serializer for V1 endpoints.

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
12.1.158.12 | Latest

### Supported RAP Version Range

Lowest Version | Highest Version
--- | ---
12.1.16 | Latest

## v12.1.11

### Release Notes

Initial Version

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
12.1.0.0 | Latest

### Supported RAP Version Range

Lowest Version | Highest Version
--- | ---
12.1.2 | Latest