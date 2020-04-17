# Faqs #

## Why is Entity-bound important?

Entity-bound allows binding data to an Entity. It allows Entity-controlled access and results in 
privacy and better security of PII (Personal Identifying Information).

## What is D-ISP's access model based upon? 

D-ISP controls data access through a Relationship between the Entity whose data is queried (the Target) 
and the Entity that is requesting access (the Requestor).
Relationships are encoded in Relationship Distributed Identifier (RDID) that store the target and requestor's identity expressed
as Entity Distributed Identifiers (EDID) that where allocated when the Entity was registered with the platform.
RDIDs are required to be passed in all requests for data along with the passCode that was allocated
to the requestor when they registered with the platform.

## What is a Schema-agnostic Data Model?

Schema agnostic means that there is no requirement to define a schema to store and access data in D-ISP.
Additionally, there is no requirement to define indexes in order to speed up queries. Documents stored in
D-ISP have been parsed into a format called 'Common Hierarchical Format' (CHF). Structures in the CHF allow
query matches without consulting an index, basically, the index is in the CHF and goes with the document
wherever it may go. Any attribute/element/field and/or its value can be queried without an index.
 