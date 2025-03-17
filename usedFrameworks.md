Used Frameworks and Libraries
=============================

Version
-------

Date: February 21\
Performed by: Steffen Lomholt Hansen\
Version: 1.0

Java
----

This section describes the frameworks and dependencies used in the Java code examples.

### cxf-rt-rs-client version 3.3.6

Part of Apache CXF, an open-source framework for developing web services that supports both JAX-RS (RESTful services) and JAX-WS (SOAP services). This dependency facilitates calls to RESTful web services using JAX-RS client APIs.

### cxf-rt-frontend-jaxws version 3.3.6

Used to implement and consume SOAP-based web services using JAX-WS (Java API for XML Web Services).

### cxf-rt-ws-security version 3.3.6

Implements WS-Security for SOAP-based web services, supporting authentication, authorization, signing, encryption, tokens, and security policies.

### cxf-rt-features-logging version 3.3.6

Provides logging functionality for both SOAP and REST web services, useful for debugging and monitoring.

### log4j-slf4j-impl version 2.13.3

Integrates Log4j 2 with SLF4J, allowing applications logging via SLF4J to use Log4j 2 as the actual logging backend.

### jaxb2-fluent-api version 3.0

A JAXB2 plugin that generates Fluent API methods for JAXB-generated classes, improving readability and reducing boilerplate code.

### junit-jupiter-api version 5.3.1

Part of JUnit 5, providing APIs for writing tests, requiring a test engine (junit-jupiter-engine) for execution.

### assertj-core version 3.9.1

A Java assertion library that allows for fluent and readable test assertions.

### junit-jupiter-engine version 5.3.1

Executes JUnit 5 tests, serving as the test engine.

### jaxb2-namespace-prefix version 1.3

A JAXB2 plugin that customizes namespace prefixes in XML output for better interoperability.

### jaxb2-basics version 1.11.1

Enhances JAXB-generated classes by adding equals(), hashCode(), toString(), and other useful methods.

### jaxb2-basics-annotate version 2.19.1

Allows adding custom annotations to JAXB-generated Java classes, automating metadata enrichment.

.NET 4.8
--------

### Digst.OioIdws.Common

Provides common functionality and helper classes used within the OIOIDWS.Net project, including utility functions, configuration handling, and error management.

### Digst.OioIdws.LibBas

Defines standard SOAP bindings and security mechanisms for web services in the OIOIDWS.Net project.

### Digst.OioIdws.OioWsTrust

Implements OIO-WST specification, facilitating secure communication between clients and web services via token issuance and validation.

### Digst.OioIdws.Soap

Handles secure SOAP-based communication between web service consumers and providers.

### MSTest.TestFramework version 2.1.1

Provides attributes and methods to write and execute unit tests in .NET applications.

.NET 6
------

### coverlet.collector version 3.1.2

Cross-platform code coverage library for .NET applications, supporting multiple output formats.

### Digst.OioIdws.WscCore version 4.0.70

A .NET Core-based implementation of OIOIDWS 1.1, facilitating secure communication with web services.

### Microsoft.NET.Test.Sdk version 17.1.0

Provides infrastructure for running unit tests with various test frameworks.

### MSTest.TestAdapter version 2.2.8

Enables discovery and execution of MSTest-based unit tests.

### MSTest.TestFramework version 2.2.8

Contains attributes and methods for writing and executing MSTest unit tests in .NET applications.
