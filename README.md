# bodleian-RDF
The Bodleian Libraries, University of Oxford, publish their medieval(ish) manuscripts [catalogue in TEI](https://github.com/bodleian/medieval-mss). This repository provides a subset of the catalogue information which has been mapped into RDF.

To generate linked data from TEI, it is first transformed into a simpler, flatter XML structure using xquery and then mapped to RDF/XML using [3M software](https://github.com/isl/Mapping-Memory-Manager). This mapping relies heavily on CIDOC-CRM, and grew out of the Oxford Linked Open Data (OXLOD) and Mapping Manuscript Migrations (MMM) projects at Oxford and was led by Andrew Morrison and Athanasios Velios.

The mapping files and instructions for running the data conversion can be found in the [bodleian-mmm](https://github.com/mapping-manuscript-migrations/bodleian-mmm) repository.
