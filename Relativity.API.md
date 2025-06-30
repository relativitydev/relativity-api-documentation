# Relativity.API Version Compatibility

[![nuget](https://img.shields.io/nuget/v/Relativity.API.svg)](https://www.nuget.org/packages/Relativity.API)

The interfaces and data objects for Relativity Extensibility Points.
## v19.5.2

### Release Notes

Introduced packaging scripts for kCura.Agent and kCura.EventHandler as Relativity.Agent and Relativity.EventHandler.
Enhanced agent execution with new interfaces (IAgentExecutionWrapper, IOperationalSpan) to allow greater control and flexibility.
Improved thread safety in ServiceBusEnabledAgentBase by using Interlocked for CurrentCallCount.
Updated logging in Agent Base to include agent name in context.
Expanded internal access to support integration with Relativity.Eca.ApplicationBase.Core and other projects.
Limited exposure of internals in Relativity.Threads to the data project for better encapsulation.
Added new contracts to the Foundation API to support merge mass operations.
Improved ServiceBusAgent reliability with longer AutoDeleteOnIdle times.
Enhanced DTO Serializer to handle documents with null batch status.
Updated obsolete tags and assembly configurations for better compatibility and maintainability.

## v17.0.4

### Release Notes

Changes to assembly internal visibility

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
11.3.185.7 | Latest

## v15.6.3

### Release Notes

Initial Version

### Supported Relativity Version Range

Lowest Version | Highest Version
--- | ---
11.3.185.7 | Latest
