# gda2

## openmetadata exploration

### background

We are trying to see if we could use some of these open source products to compensate for short comings in AWS Data Zone and AWS Glue.
There are two layers we think this could be possible:
1. Data Lineage
2. Data Quality

Openmetadata has the ability to generate lineage information from various inputs it ingests. These includes Metadata ingestion, pipeline ingestion and direct lineage ingestion. Openmetadata then make sense of all the lineage information from different sources and incorporate them into a coherent lineage diagram.

### testing
We are going to test how openmetadata can be integrated, or data lineage information can be either extracted.