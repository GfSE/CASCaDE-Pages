---
title: Results
layout: default
parent: "Home"
nav_order: 90
---

# Results

### 2026-01-12 Metamodel Implemented in RDF/Turtle and JSON-LD with JSON Schema

The last quarter's work on the 'Magic Tetrahedron' has been finalized. That is, the PIG metamodel defines patterns for RDF/Turtle, JSON-LD
and Javascript. The 'Magic Tetrahedron' describes the sweet spot, where a Knowledge Graph,
a Property Graph and a data-structure in an object-oriented programming language are designed in a way that lossless transformations
between any of the data formats are easily possible. Of course, this means that the expressivity is tailored for their purpose. 
This approach will be validated in the next step with (near to) real world scenarios and data.

The current proposal does not use JSON-LD as an essentially redundant representation of OWL/RDF, but takes 
best advantage of its features, namely the power of JSON Schema and the mature multi-user operations of existing document databases. 
Rather than separate class and shape definitions in RDF, unified JSON objects are used: 
Usually between 10 and 30 RDF tripels are combined to a single object facilitating transaction management and versioning. 
The information content is exactly the same, but the respective strengths of the formats and their respective ecosystems are exploited.
- For PIG data using RDF, SHACL shapes for each metamodel class define the correct pattern of the instances/individuals, 
i.e. the graph representing the unified product data; see the examples below.
- For PIG data using JSON-LD, JSON schemata for all item types as defined by the metamodel are available [here](https://product-information-graph.org/schema/2026-01-12/jsonld/).

Example data is available in RDF/Turtle and JSON-LD formats:
- Very Simple Model with Requirement (FMC): [RDF/Turtle](https://github.com/GfSE/CASCaDE-Verification-and-Validation/tree/main/Very-simple-Model-with-Requirements%20%5BFMC%20-%20SpecIF%5D/6_JSONLD) and [JSON-LD](https://github.com/GfSE/CASCaDE-Verification-and-Validation/tree/main/Very-simple-Model-with-Requirements%20%5BFMC%20-%20SpecIF%5D/7_RDF);
- Small Autonomous Vehicle (SysML v1): [RDF/Turtle](https://github.com/GfSE/CASCaDE-Verification-and-Validation/tree/main/SmAV%20%5BSysML%20v1%20-%20Cameo%5D/6_JSONLD) and [JSON-LD](https://github.com/GfSE/CASCaDE-Verification-and-Validation/tree/main/SmAV%20%5BSysML%20v1%20-%20Cameo%5D/7_RDF);
- Dimmer (FMC): [RDF/Turtle](https://github.com/GfSE/CASCaDE-Verification-and-Validation/tree/main/Dimmer%20%5BFMC%5D/6_JSONLD) and [JSON-LD](https://github.com/GfSE/CASCaDE-Verification-and-Validation/tree/main/Dimmer%20%5BFMC%5D/7_RDF).

The data has successfully passed the schema and and instantiated Javascript classes representing the metamodel items. 
So we are all set to implement the transformations from the source formats and to validate the concept.
There is still lots to do, so any help in time or budget is appreciated!


### 2025-12-08 CASCaRA: Initial Standard Submission at OMG

The CASCaRA Submission Team has prepared an [initial submission of the standard]
(https://gesellschaftf.sharepoint.com/:b:/s/SpecIf-DDPCollaboration2/IQByyzIgfUjjTr1vucGXs50XAd8ZcPnQixTxqA4puNaSWZ4?e=nNjmi9) (link opens for the contributors to the submission team)_. 
Both the Product-Information-Graph metamodel as well as the first revision of the ontology are included.
The document has been discussed at the OMG TC Meeting in San Francisco CA and has received a lot of attention
among other OMG initiatives.

Please note the the project has been renamed to 'CASCaRA' (Collaborative Artifact, Specification, Context and Resource Access) 
to avoid misunderstandings: As far as we know, CASCaRA 
is not used by any other initiative or product. This website and the GiHub repositories will be moved to corresponding internet addresses.


### 2025-03-25 Metamodel Discussed at OMG TC Meeting in Reston VA

In Q1, the team of CASCaDE work-package 1 has prepared a draft metamodel for a knowledge graph 
containing interrelated product information from different sources. 
A major design goal is to reduce the graph's power of expression as much as permitted by the real world data,
so that the choice of technologies is as wide as possible. Requirements have been identified
to assess potential solutions. A simple example has been prepared for illustration and review.

The discussions last week in Reston with other OMG initiatives such as SysML v2, RAS, SPDX and others 
have shown a lot of potential for cooperation and reuse. For good reason, users expect complementary standards.

Please have a look:
- Product Information Graph Metamodel (draft): <a href="https://specif.de/apps/edit#import=https://cascade.gfse.org/results/2025-03-25%20Metamodel/Product%20Information%20Graph.specif.zip" target="_blank" >Online with Relations</a> and transformed to <a href="./2025-03-25%20Metamodel/" target="_blank" >HTML</a>.
- Very Simple Model with Requirements: <a href="https://specif.de/apps/edit#import=..\examples\v1.2\09_Very-Simple-Model-FMC-with-Requirements.specif.zip" target="_blank" >Online with Relations</a> and transformed to <a href="https://github.com/GfSE/CASCaDE-Verification-and-Validation/blob/main/Very-simple-Model-with-Requirements%20%5BFMC%20-%20SpecIF%5D/7_RDF/Project%20'Very%20Simple%20Model%20(FMC)%20with%20Requirements'.ttl" target="_blank" >RDF</a> according to the metamodel.

As a next step, an ontology shall be developed to map the concepts of different domains to the integrated graph 
and the metamodel shall be verified and validated with real world data. Towards this end we 
**urgently need help by companies developing and offering mechatronic products (the 'users') and interested software vendors**: 
CASCaDE is for you!

Contact
- Uwe Kaufmann via <a href="https://www.linkedin.com/in/uwekaufmann/" target="_blank">linkedIn</a> or [e-mail](mailto:uwe.kaufmann@gfse.org)
- Dr.-Ing. Oskar von Dungern via <a href="https://github.com/odungern" target="_blank">GitHub</a>, <a href="https://www.linkedin.com/in/odungern/" target="_blank">linkedIn</a> or [e-mail](mailto:oskar.dungern@gfse.org)

### 2024-12-13 OMG approves RFP

We are pleased to announce that the CASCaDE Request for Proposal (RFP) has been approved 
by the OMG Architecture Board (AB) and Technical Committee (TC). 
This is a major milestone on the way to standardize the collaboration in the 
product lifecycle from end to end.
A controlled vocabulary and a common context for so far partial product data are in focus.

Major ideas behind the RFP are explained <a href="../files/documents/2024-12%20CASCaDE-Introduction%20OMG.pdf" target="_blank" >here</a> 
and the RFP itself ist published on the <a href="https://www.omg.org/cgi-bin/doc?mantis/24-12-03.pdf" target="_blank" >OMG website</a>.

Members of prostep ivip and GfSE have prepared the RFP document in the past months.

As a next step, a submission team for a standard will be formed. The associations GfSE, 
prostep ivip and VDA have agreed to sponsor the effort. The team is looking for further funding to 
accurately verify and validate the concepts to be submitted.

<!-- Pattern: <a href="..." target="_blank" >...</a> -->