FinOps Open Cost and Usage (FOCUS) Scope
-----

> **NOTE:**
> This is the official scope for the FinOps Open Cost and Usage Project. Scopes of FOCUS Working Groups will be found in the scope.md document in repositories of the respective FOCUS Working Groups.

The FinOps Open Cost & Usage Specification (FOCUS) Project will develop and maintain a common open billing schema with specifications of the measures, dimensions and metrics a cloud user would require to analyze cloud cost and usage in aggregate. 

Common specifications will be cloud neutral, service neutral, and vendor neutral. Specifications will include metadata about the common format dataset related to its delivery, structure, formatting, frequency, recency, content, file size, etc. The specification will provide source-specific mappings of the common format to specific cloud cost, usage or billing sources  (e.g. cloud vendors, software license vendors, etc.) including mappings, rationale for mappings, gaps where mapping cannot occur, recommendations for workarounds, methods of accessing the data, the source data format, etc. 

Cloud Service Provider (CSP) Service-specific versions of mappings will also be developed where required and feasible. These will include specific logic and mappings for specific types of services (e.g. EC2, S3, Google Compute Engine, BigQuery, etc.) usually required where the mapping of cost metrics requires combinations of multiple service cost measures or allocation of fixed and variable costs for a service to achieve compliance with the common format.

The Project will also provide, where appropriate mappings to other open source projects, such as the OpenTelemetry project data taxonomy, ITFM/TBM taxonomy, etc. 

The Project will produce Reference Implementations, including such things as software which can be used to ingest any supported source of cost or usage data and translate its content to the common format using the specification logic, software which can receive common format data and store it in a repository in one or more cloud environments, software which could be executed in an environment owned and operated by a customer, or operated by a third party, software which supports query access to the common billing format data once stored, etc.

The Project will produce Use Cases, examples of analysis you can do as a customer using the common format. Use Cases may cover Persona or Cloud or Service specific cases implemented in some specific way using the specifications and reference implementations.

Any changes of Scope are not retroactive. 

FOCUS Scope Commentary
----------------------

The FOCUS Scope was taken partially from the goals and objectives of the FinOps Foundation Open Billing Standards working group Proposal which pre-dated the FOCUS Project by several months, and was subsumed into it in February 2023. 

The Scope was expanded to be more inclusive of work products beyond the first three sprints envisioned in that charter, and to include any foreseeable deliverables contributors would be asked to work on as part of the project. 

The scope as defined will be what Members of the FOCUS project are agreeing to contribute to, so should be broad enough to encompass a reasonable but well described scope. 

Future scope changes or additions will require Members to sign new Contributor License Agreements (CLAs) which is administratively complex, and so the broader scope addresses that potential challenge. 

FOCUS Working Groups established by the FOCUS Steering Committee (SC) will typically be more focused subsets of this larger Project scope. 
