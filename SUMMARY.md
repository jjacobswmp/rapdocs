# Table of contents

* [Welcome to RAP!](README.md)
* [Getting Started Guide](getting-started-guide/README.md)
  * [RAP Basics](getting-started-guide/rap-basics/README.md)
    * [How it Works](getting-started-guide/rap-basics/how-it-works-2.md)
    * [Navigation and Interface](getting-started-guide/rap-basics/navigation-and-interface.md)
    * [Prerequisites](getting-started-guide/rap-basics/prerequisites.md)
  * [Data Integration Example](getting-started-guide/data-integration-example/README.md)
    * [Setting up](getting-started-guide/data-integration-example/setting-up.md)
    * [Connection](getting-started-guide/data-integration-example/connection.md)
    * [Source](getting-started-guide/data-integration-example/source.md)
    * [Validation and Enrichment](getting-started-guide/data-integration-example/validation-and-enrichment.md)
    * [Output](getting-started-guide/data-integration-example/output.md)
* [Logical Architecture](logical-architecture-overview/README.md)
  * [RAP Agent](logical-architecture-overview/rap-agent.md)
  * [User Interface](logical-architecture-overview/user-interface.md)
  * [Data Storage](logical-architecture-overview/data-processing.md)
  * [Data Processing Engine](logical-architecture-overview/data-processing-engine/README.md)
    * [Data Processing Steps](logical-architecture-overview/data-processing-engine/data-processing-1.md)
* [Physical Architecture](introduction-to-rap/README.md)
  * [!! Infrastructure Components](introduction-to-rap/rap-infrastructure-components/README.md)
    * [Authentication Engine](introduction-to-rap/rap-infrastructure-components/user-and-machine-authentication.md)
    * [RAP Agent](introduction-to-rap/rap-infrastructure-components/on-premise-agent.md)
    * [Data Lake](introduction-to-rap/rap-infrastructure-components/raw-data-lake.md)
    * [Data Hub](introduction-to-rap/rap-infrastructure-components/data-hub.md)
    * [Docker Containers](introduction-to-rap/rap-infrastructure-components/virtual-machine-instances.md)
    * [Databricks](introduction-to-rap/rap-infrastructure-components/databricks.md)
    * [User Interface](introduction-to-rap/rap-infrastructure-components/user-interface.md)
    * [PostgreSQL Database](introduction-to-rap/rap-infrastructure-components/metadata-and-intermediate-processing-storage.md)
    * [Resource Sizing](introduction-to-rap/rap-infrastructure-components/resource-sizing.md)
  * [Metadata Model](introduction-to-rap/metadata-model.md)
  * [Data Storage](introduction-to-rap/storage-data-model.md)
* [Deployment](deployment/README.md)
  * [Deployment to a New Environment](deployment/code-deployment.md)
  * [Installing a New RAP Agent](deployment/installing-a-new-rap-agent.md)
  * [Environment Migration Process](deployment/migrations-across-environments.md)
* [Configuration Guide](configuring-the-data-integration-process/README.md)
  * [Connections](configuring-the-data-integration-process/connections-configuration.md)
  * [Sources](configuring-the-data-integration-process/source-configuration/README.md)
    * [Details](configuring-the-data-integration-process/source-configuration/source-details.md)
    * [Dependencies](configuring-the-data-integration-process/source-configuration/dependency-configuration.md)
    * [Relations](configuring-the-data-integration-process/source-configuration/relations-1.md)
    * [Enrichments](configuring-the-data-integration-process/source-configuration/enrichment-rule-configuration.md)
    * [Inputs](configuring-the-data-integration-process/source-configuration/source-inputs.md)
    * [Process](configuring-the-data-integration-process/source-configuration/process.md)
    * [Data View](configuring-the-data-integration-process/source-configuration/source-data-view.md)
    * [Importing and Exporting Configurations](configuring-the-data-integration-process/source-configuration/importing-and-exporting-source-configurations.md)
  * [Templates](configuring-the-data-integration-process/validation-and-enrichment-rule-templates.md)
  * [Outputs](configuring-the-data-integration-process/output-configuration/README.md)
    * [Output Details](configuring-the-data-integration-process/output-configuration/output-details.md)
    * [Output Mapping](configuring-the-data-integration-process/output-configuration/output-mapping.md)
    * [Manual Output](configuring-the-data-integration-process/output-configuration/manual-output.md)
    * [Output History](configuring-the-data-integration-process/output-configuration/output-history.md)
* [Performance Tuning](performance-tuning.md)
* [Best Practices](best-practices/README.md)
  * [Onboarding New Sources](best-practices/onboarding-sources.md)
  * [Naming Conventions](best-practices/naming-conventions.md)
  * [Output Data Modeling](best-practices/output-data-modeling.md)
  * [Rollup Sources](best-practices/rollup-sources.md)
  * [Error Handling](best-practices/error-handling.md)
* [Operation Guide](operation-guide/README.md)
  * [Monitoring the Process](operation-guide/monitoring-the-process/README.md)
    * [Source Dashboard](operation-guide/monitoring-the-process/operational-dashboard.md)
    * [Checking Statuses](operation-guide/monitoring-the-process/checking-statuses.md)
    * [Checking Logs](operation-guide/monitoring-the-process/checking-logs.md)
    * [Common Errors](operation-guide/monitoring-the-process/common-errors.md)
    * [Example Daily Routine](operation-guide/monitoring-the-process/example-daily-routine.md)
    * [RAP Agent](operation-guide/monitoring-the-process/rap-agent.md)
* [Historical Reference](historical-reference/README.md)
  * [How it Works \(1.x\)](historical-reference/components-and-concepts.md)
* [Changelog](changelog/README.md)
  * [1.0](changelog/rap_patch_notes_1.0.md)
  * [1.1](changelog/1.1.md)
  * [1.2](changelog/rap_release_notes_1.2.md)
  * [1.3](changelog/rap_release_notes_1.3/README.md)
    * [1.3.7](changelog/rap_release_notes_1.3/rap_patch_notes_1.3.7_table.md)
    * [1.3.8](changelog/rap_release_notes_1.3/rap_patch_notes_1.3.8.md)
  * [1.4](changelog/rap_release_notes_1.4/README.md)
    * [1.4.1](changelog/rap_release_notes_1.4/rap_patch_notes_1.4.1.md)
    * [1.4.2](changelog/rap_release_notes_1.4/rap_patch_notes_1.4.2.md)
    * [1.4.3](changelog/rap_release_notes_1.4/rap_patch_notes_1.4.3.md)
    * [1.4.4](changelog/rap_release_notes_1.4/rap_patch_notes_1.4.4.md)
    * [1.4.5](changelog/rap_release_notes_1.4/rap_patch_notes_1.4.5.md)
  * [1.5](changelog/rap_release_notes_1.5/README.md)
    * [1.5.2](changelog/rap_release_notes_1.5/rap_patch_notes_1.5.2.md)
    * [1.5.3](changelog/rap_release_notes_1.5/rap_patch_notes_1.5.3.md)
    * [1.5.4](changelog/rap_release_notes_1.5/rap_patch_notes_1.5.4.md)
  * [1.6](changelog/1.6/README.md)
    * [1.6.1](changelog/1.6/1.6.1.md)
    * [1.6.2](changelog/1.6/1.6.2.md)
    * [1.6.3](changelog/1.6/1.6.3.md)
    * [1.6.4](changelog/1.6/1.6.4.md)
    * [1.6.5](changelog/1.6/1.6.5.md)
  * [1.7](changelog/1.7/README.md)
    * [1.7.5.1](changelog/1.7/1.7.5.1.md)
    * [1.7.5](changelog/1.7/1.7.5.md)
    * [1.7.4.2](changelog/1.7/1.7.4.2.md)
    * [1.7.4.1](changelog/1.7/1.7.4.1.md)
    * [1.7.4](changelog/1.7/1.7.4.md)
    * [1.7.3](changelog/1.7/1.7.3.md)
    * [1.7.2.3](changelog/1.7/1.7.2.3.md)
    * [1.7.2.2](changelog/1.7/1.7.2.2.md)
    * [1.7.2.1](changelog/1.7/1.7.2.1.md)
    * [1.7.2](changelog/1.7/1.7.2.md)
    * [1.7.1.1](changelog/1.7/1.7.1.1.md)
    * [1.7.1](changelog/1.7/1.7.1.0.md)
    * [1.7.0.7](changelog/1.7/1.7.0.7.md)
    * [1.7.0.6](changelog/1.7/1.7.0.6.md)
    * [1.7.0.5](changelog/1.7/1.7.0.5.md)
    * [1.7.0.4](changelog/1.7/1.7.0.4.md)
    * [1.7.0.3](changelog/1.7/1.7.0.3.md)
    * [1.7.0.2](changelog/1.7/1.7.0.2.md)
    * [1.7.0.1](changelog/1.7/1.7.0.1.md)

