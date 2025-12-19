# Relativity.Processing.SDK Version Compatibility

[![nuget](https://img.shields.io/nuget/v/Relativity.Processing.SDK.svg)](https://www.nuget.org/packages/Relativity.Processing.SDK)

This package contains interfaces for the public APIs of the Relativity Processing application.

## 13.29.261

### Release Notes

* Removes V1 IProcessingFilterManager and IProcessingDocumentManager APIs

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
25.12 | Latest 25.12

### Supported RAP Version Range

Lowest Version | Highest Version
--- | ---
13.29.261 | Latest 13.29

## 13.29.230

### Release Notes

* Add CreateExpressionFilterAsync and other filter related endpoints to V2 IProcessingFilterManager

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
25.11 | Latest 25.11

### Supported RAP Version Range

Lowest Version | Highest Version
--- | ---
13.29.230 | Latest 13.29

## 13.29.150

### Release Notes

* Added V2 for IProcessingDocumentManager and IProcessingFilterManager to support MDS release.

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
25.8 | Latest 25.8

### Supported RAP Version Range

Lowest Version | Highest Version
--- | ---
13.29.150 | Latest 13.29

## 12.5.870

### Release Notes

* Add endpoint to streamline data source creation.
* Public model for OCR language mapping.
* Upgrade package dependencies.

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
24.3 | Latest 24.3

### Supported RAP Version Range

Lowest Version | Highest Version
--- | ---
12.5.870 | Latest 12.5

## 12.5.41

### Release Notes

* Updated package references to target Relativity Yarrow release.

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
13.2.2 | Latest 13.2

### Supported RAP Version Range

Lowest Version | Highest Version
--- | ---
12.5.37 | Latest 12.5

## 12.3.30

### Release Notes

* Updated package references to target Relativity Sundrop release.

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
12.3.0.0 | Latest 13.1

### Supported RAP Version Range

Lowest Version | Highest Version
--- | ---
12.3.30 | Latest 12.3

## 12.2.58

### Release Notes

* Removed the ability to clear the Field Mapping cache.
* Updated package references to target Relativity Osier release.

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
12.1.256.8 | Latest 12.1

### Supported RAP Version Range

Lowest Version | Highest Version
--- | ---
12.2.58 | Latest 12.2

## 12.2.19

### Release Notes

* WCF endpoints have been replaced with Kepler equivalents, and no WCF is used by the Processing APIs.
* Removed the Processing Profile Manager API endpoint, consumers should now use Object Manager API.
* Addition of a versioned v1 API surface, consumers are highly encouraged to transition to these APIs.

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
12.1.0.0 | 12.1.256.8

### Supported RAP Version Range

Lowest Version | Highest Version
--- | ---
12.2.0 | 12.2.57