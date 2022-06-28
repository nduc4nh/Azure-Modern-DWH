# Data Storage

## Azure Datalake

### Structure

1. Raw data section - staging

2. Curated data - governed - smaller type of file

* data for model coming from this section

3. Result section: output of model stored in this section

## Synapse - Dataware house solution

### Structure

Computing engine & Data storage

* SQL pools

Tables
 
* Pipelines

Data mapping - handle unstructure data also

Unstructure: more appropriate if they're in character delemiter separated files (CSV, tsv.. )

## Flow 

raw -> lake -> Dataware house -> Analytics engines
