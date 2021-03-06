---
description: >-
  The Source Data View tab allows users to view Source data. Color coding and
  filtering options make it clear which data is newly loaded or enriched.
---

# Data View

## Data View Tab

The Data View tab allows users to view a Source's data. Users can filter and sort the data to validate proper execution of enrichment and validation rules.

![Data View](../../.gitbook/assets/image%20%2853%29.png)

Column headers are color coded to indicate Raw versus Enriched data.

* **Blue Header:** Raw data from the Source
* **Green Header:** Enriched data generated by Enrichment Rules
* **Gray Header:** System data tracking data lineage and results of Validation Rule execution

Rows are color coded to indicate a record's Validation flag.

* **White Row:** Records that pass Validation
* **Yellow Row:** Records warned during Validation
* **Red Row:** Records failed during Validation

## Filtering Results

Users can filter results in a number of ways.

### Typing SQL

In the top bar, users can type in PostgreSQL queries to filter records. The statements will be evaluated after a `WHERE` clause is added to a `SELECT *` query.

### Selecting Columns

Users can select columns by clicking Select Columns. Users can add Descriptions, see Data Types, and check off which columns appear in the View Data tab.

![Select Columns](../../.gitbook/assets/image%20%28135%29.png)

### **Sorting Data**

Clicking a column's name sorts the data in ascending order. Clicking again switches to descending order.

![Column Name](../../.gitbook/assets/image%20%2886%29.png)

## Analyzing Data

### Downloading Data

The Download button in the top right will download a `.csv` file of the data as it is filtered and sorted.

### Viewing Data Profiles

Clicking the Datatype icon brings up the data profile of that column. Different datatypes provide different data profile data.

![Column Datatype icon](../../.gitbook/assets/image%20%2851%29.png)

A modal appears showing the data profile when the datatype icon is clicked.

![Data Profile Modal](../../.gitbook/assets/image%20%28139%29.png)

Data profiles provide the following statistics:

### Common

* **Attribute Type**
  * Raw - Raw data from the Source
  * Enriched - Enriched data that has been transformed
* **Data Type**
  * Text
  * Numeric
  * Timestamp
* **Number of Rows**
* **Min**
* **Max**
* **Unique %**
* **Null %**
* **Top 5 Values**
* **Bottom 5 Values**
* **Distribution Percentiles \(10%, 25%, 50%, 75%, 90%\)**

### Text

* **Min Length**
* **Max Length**
* **Avg Length**
* **Numeric %**
* **Blank %**
* **Special Char %**

### Numeric

* **Average**
* **Median**
* **Standard Deviation**
* **Zero %**

### Timestamp

* **Average**
* **Median**
* **Standard Deviation**

