# Relativity.Processing.SDK Version Compatibility

[![nuget](https://img.shields.io/nuget/v/Relativity.Processing.SDK.svg)](https://www.nuget.org/packages/Relativity.Processing.SDK)

This package contains interfaces for the public APIs of the Relativity Processing application.

## 12.2.13

### Release Notes

* Updated DFV to properly populate Processing Deletion fields.
* Ported Post Publish Delete performance improvement changes from mayapple.
* Bumped the Invariant Services package for ARM statistics endpoint defect fix. Fixed error field removals.
* Fix adding index to zprocessingdochistory table.
* Advanced Picker pagination support in files tab.
* Removing toggle for Processing Profile Inclusion/Exclusion feature.
* ARM Processing: Do not throw exception for duplicate cancel requests for canceled or canceling workspaces and Fix Processing Exists readiness check defect.
* Replaced remaining WCF endpoints with Kepler endpoints.
* Added a NuGet package for Password Bank, renamed Password Bank tab, and moved from ApplicationBase.
* Added Dedupe Status Field to Files tab default view.
* Resolved dependency injection issues and removed low-use RSAPI code, along with legacy test projects.
* Removed redundant Kepler endpoint check for ValidateApiEndpoints API, removed ProcessingBase package and consolidated projects into Relativity.Eca.
* Added a new private endpoint for updating count after Post Publish Delete job.
* Added APM to PreMassDeleteEH.
* Enabled OI PowerPoint toggle.
* Moving Processing Set page interactions to web assets from MVC.
* Use Object Manager instead of RSAPI for Custodian, Processing Set and Processing Data Source updates.
* Updates for Error Workflow, unhide Document Errors tab.
* Fix CustodianPreCascadeDelete handler to avoid deletion of custodians with associated processing sets.
* Started using new Shared.ApplicationBase package with contract changes to IContextContainer.
* Fixed defect with activation key and decoupled from Processing Set Manager.
* Updatied application schema to include readiness check URL for Inventory custom page.

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
12.1.0.0 | Latest

### Supported RAP Version Range

Lowest Version | Highest Version
--- | ---
12.1.0.0 | Latest