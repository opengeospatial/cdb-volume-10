Notice to public contributors:

The contributor understands that any contributions, if accepted by the OGC Membership, shall be incorporated into the relevant OGC standards and best practices documents and that all copyright and intellectual property shall be vested in the OGC.

# OGC CDB Volume 10 Implementation Guidance

## Content

This folder contains the text for the standard

* standard_document.adoc - the main standard document with references to all sections
* remaining adocs - each section of the standard document is in a separate document: follow directions in each document to populate
* images - directory for image files used as figures
* requirements - directory for requirements and requirement classes to be referenced in clause_7_normative_text.adoc
* code - sample code to accompany the standard, if desired
* abstract_tests - the Abstract Test Suite comprising one test for every requirement, optional
* UML - UML diagrams, if applicable

## Building

To produce the HTML of the standard run `asciidoctor -a stem=latexmath --safe -a data-uri  -o standard_document.html standard_document.adoc`.

To produce the PDF of the standard run `asciidoctor-pdf -a stem=latexmath --safe -o standard_document.pdf standard_document.adoc`
