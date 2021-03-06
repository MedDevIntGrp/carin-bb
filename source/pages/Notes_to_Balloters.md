---
title: Notes to Balloters
layout: default
active: Notes to Balloters
---

[Previous Page](Examples.html)

1. During ballot, feedback is requested on additional search parameters to support the use cases covered in this IG. 
2. A new title has been assigned this IG. It is now called the Consumer-Directed Payer Data Exchange Implementation Guide. The IG continues to also be known as (aka) the Carin Blue Button Implementation Guide. The Acknowledgements Section recognizes the relationship between the formal HL7 name and the aka name. Feedback on this new name is welcome during the ballot. 
3. Terminology naming issues will be addressed during the ballot process and will be resolved prior to publication in the following way: the Value Sets will be updated to remove reference to CARIN Blue Button, replaced by either industry standard names or, for those specific to claim adjudication, with the new IG name.  Industry standard Code System revisions include consolidating the three Type of Bill Codes, removing reference to SNOMED CT, etc.  Some value sets renaming has be started. The rest will be completed during ballot reconciliation.
4. Code System referencing issues will be addressed during the ballot process and will be resolved prior to publication. Based on recent guidance from the HL7 Vocabulary Workgroup a change will be made to reference external licensed Code Systems using URIs instead of OIDs.
5. Trifolia-on-FHIR is not rendering complete information about the SearchParameter Resource.  To view the definition of a search parameter, review the XML or JSON representation.
6. The QA.html tab shows a small number of errors that have been reviewed and were determined to be an acceptable set of issues going into the ballot cycle.  These errors will be addressed prior to publication.  Error types included: 
* broken links to pdf files, which actually do work
* errors related to inability of IG Publisher to provide support for the code systems CARIN is using
* errors in the EOB example resource related to inability of IG Publisher to  validate ICD-10-CM and ICD-10-PCS codes. Grahame Grieve confirmed that ICD-10-CM and ICD-10-PCS is not supported by tx.fhir.org yet: https://chat.fhir.org/#narrow/stream/179166-implementers/topic/Validatior.20Error.20ICD-10.20codes

