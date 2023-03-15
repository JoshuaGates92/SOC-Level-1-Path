
Yet another open-source option for threat intelligence management...

## Objective

To create a comprehensive tool that allows users to capitalise on technical and non-technical information while developing relationships between each piece of information and its primary source. The platform can use the [MITRE ATT&CK framework](https://tryhackme.com/room/mitre) to structure the data. Additionally, it can be integrated with other threat intel tools such as MISP and TheHive.

![[OpenCTI Dashboard.png]]


## OpenCTI Data Model

Main data structure used is the Structured Threat Information Expression ([STIX2](https://oasis-open.github.io/cti-documentation/stix/intro)) standards.

STIX is a ==serialised and standardised language== format used in threat intelligence exchange. It allows for the data to be implemented as entities and relationships, effectively tracing the origin of the provided information.

The highlight services include:

-   **GraphQL API:** The API connects clients to the database and the messaging system.
-   **Write workers:** Python processes utilised to write queries asynchronously from the RabbitMQ messaging system.
-   **Connectors:** Another set of python processes used to ingest, enrich or export data on the platform. These connectors provide the application with a robust network of integrated systems and frameworks to create threat intelligence relations and allow users to improve their defence tactics.