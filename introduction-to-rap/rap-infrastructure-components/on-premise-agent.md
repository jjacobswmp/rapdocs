# RAP Agent

As most source data will reside in on-premise or private cloud environments, RAP requires a method to transfer that data into AWS for processing.  To achieve this, RAP leverages an agent architecture in order to ingest data into RAP from the various on-premise networks.  On each source system environment, a lightweight Scala-based Agent is installed for the purpose of pulling data from the source system and uploading it to AWS.  The major benefit of this approach is that no VPN needs to be set up into each of the on-premise or private networks.  The only requirement for the Agent is access to initiate connections to the public internet.

If exact domains are required for specific networks because of restrictive firewalls for external network connections, please reach out to the RAP support team for the following domains:

* Auth0
* RAP API endpoint
* S3 landing bucket

### Supported Source Data Types

The RAP Agent currently supports ingestion of the following source data types out of the box.

* Flat files \(CSV, pipe-delimited, etc\) via file share, local drive or SFTP
* SQL Server
* PostgreSQL
* Snowflake

RAP also supports the following proprietary source systems.  However, since those drivers are under proprietary licenses and may require a licensing fee from the associated vendor, support is not provided directly out of the box.  Instead, the client requiring support for one of the following source systems will need to acquire the appropriate JDBC driver \(and license file if appropriate\) from the appropriate vendor and provide a copy to the RAP development team so the appropriate driver can be built into the RAP Agent.

* Oracle
* Quickbooks
* SAP HANA
* Pervasive SQL

### Data Flow into AWS

The RAP Agent pulls data from the source system and generates a CSV.  That CSV is then uploaded to the landing area in the data lake.

TODO - arch diagram, point out HTTPS connection
