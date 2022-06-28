# Azure Modern Data Warehouse

The architecture provides users with `end-to-end` solution.

## Components:

There are overall 5 main components constructing Azure Modern Datawarehouse

* Data sources and data storage:

Data come from difference sources

Data storage for processing outcome consilidation

* Data processing module

hot path: streaming, real time data

cold path: batch processing

Azure Synapse pipeline

Data Factory <- mostly used for cold path

* Data analytic engine
Spark pools & SQL pools computing engine

Azure ML

* Serving layer

Deployment and automation <- AKS

On top of that is application for end users

* Data management and governance

* Data security

## Serving layer:

Close to end user solution

Microsoft Cognitive Services: provides AI solution for end user, AI package built by Microsoft including APIs to deal with serveral tasks:

* Vison

* Speech 

* Language 

* Knowledge 

* Search

* Labs


