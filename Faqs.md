# Faqs #

## Why is Entity-bound important?

Entity-bound allows binding data to an Entity. It allows Entity-controlled access and results in 
privacy and better security of PII (Personal Identifying Information).

## What is D-ISP's access model based upon? 

D-ISP controls data access through a Relationship between the Entity whose data is queried (the Target) 
and the Entity that is requesting access (the Requestor).
Relationships are encoded in Relationship Distributed Identifiers (RDID) that store the target and requestor's identity expressed
as Entity Distributed Identifiers (EDID) that where allocated when the Entity was registered with the platform.
RDIDs are required to be passed in all requests for data along with the JWT token from login containing tbe passCode that was allocated
to the requestor when they registered with the platform.

## What is a Schema-agnostic Data Model?

Schema agnostic means that there is no requirement to define a schema to store and access data in D-ISP.
Additionally, there is no requirement to define indexes in order to speed up queries. Documents stored in
D-ISP have been parsed into a format called 'Common Hierarchical Format' (CHF). Structures in the CHF allow
query matches without consulting an index; basically, the index is in the CHF and goes with the document
wherever it may go. Any attribute/element/field and/or its value can be queried without an index.
 
 ## What are use cases for D-ISP?
 Dataparency D-ISP Products/Use Cases
 
 -	Using D-ISP data controls to secure processes through data access
 
    1. Kubernetes (K8s) container security plugin
    2. Process security control plugins for other implementations
    3. Secure Access to Databases / Applications
        1. Single Sign on
        2. Identity Control Framework
    4. Remote Work / Pipeline Filter access to legacy applications
 -	Using D-ISP data controls to securely share information
 
    1. RDID controlled data access framework / platform
    2. Patient ‘system of record’ database to increase healthcare efficiency
        1. Provider / Hospital
        2. Insurance / Benefits Coordinator
    3. HHS / CMS
    4. Pharmaceutical Clinical Studies
    5. Supply chain networks to coordinate suppler processes
        1. DoD / Government
        2. Corporate
        3. NGO / Humanitarian
    6. DRM (digital rights) framework using RDID to allow control / purchase of copyrighted works
        1. Publishers
        2. Music 
        3. Blogs
        4. 3d designs
        5. Social Media
    7. Corporate Data Governance
    8. ‘Data Warehouse’
    9. Analytical Database
    10. Analytics Workstation using statistics from D-ISP
    11.	K8s D-ISP data framework supporting microservices
 -	Partnerships with Network providers e.g., Verizon, ATT, T-Mobile, etc.
 
    1. Build frameworks to provide B2B services as subscriptions
    2. Analytical platforms
    3. Distributed Data Networks
