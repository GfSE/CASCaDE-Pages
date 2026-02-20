---
title: Validation and Examples
layout: default
parent: "Home"
nav_order: 30
---

# Validation

The concept for validating the standard to submit is proposed [here](./process/). [Discussion and suggestions](https://github.com/GfSE/CASCaDE-Pages/discussions/5) are welcome!


# Examples

## Small Examples Transformed to JSON-LD, RDF/Turtle and HTML

The following examples demonstrate how data according to the [Product Information Graph (PIG)](../results/Latest%20Metamodel/) looks like. The metamodel as well as the transformations are under construction, thus subject to change. We ask you to scrutinize the approach and to make suggestions!

| Online Demo | Data |
| --- | --- |
| [Very-simple-Model-with-Requirements (FMC)](https://specif.de/apps/edit#import=../examples/v1.2/09_Very-Simple-Model-FMC-with-Requirements.specif.zip) | [Link](https://github.com/GfSE/CASCaDE-Verification-and-Validation/tree/main/Very-simple-Model-with-Requirements%20%5BFMC%20-%20SpecIF%5D) |
| [Dimmer (FMC)](https://specif.de/apps/edit#import=../examples/Dimmer.specifz) | [Link](https://github.com/GfSE/CASCaDE-Verification-and-Validation/tree/main/Dimmer%20%5BFMC%5D) |
| [Small Autonomous Vehicle (SysML v1)](https://specif.de/apps/edit#import=../examples/Small%20Autonomous%20Vehicle.specif.zip) | [Link](https://github.com/GfSE/CASCaDE-Verification-and-Validation/tree/main/SmAV%20%5BSysML%20v1%20-%20Cameo%5D) |

Please note that for the time being the SpecIF tools are used for online demonstration. The PIG tools will be used as soon as available. However, the data in JSON-LD and RDF/Turtle reflects already the PIG metamodel. 


## Ontology-based Application: Libraries

A simple example showing the process of an ontology-based application:
1. Defining an application ontology, here library, asset and author,
2. Managing application data, here the libraries with their books and authors, 
3. Using the application data, for example querying the books available in a given library.

A [3-step process](https://gfse.github.io/CASCaDE-Reference-Implementation/design/Ontology-based%20Applications/) is described with links to web editors and the example data.

<!-- The referenced examples are stored here at ../examples/libraries/index.html -->