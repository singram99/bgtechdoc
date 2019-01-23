## Business Gateway developer pack: Search by Property Description
[//]: # Comment?
### Technical documents for software developers to integrate Search by Property Description service data into their systems.

#### Contents
- [Process flow](#process-flow)
- [Schemas](#schemas)
- [Vendor testing](#vendor-testing)

The Search by Property Description service returns the title number of a property based on the address supplied.

### Process flow

#### Input
Request an enquiry by property description by sending the parameters:

- login details
- external reference number
- customer reference
- address

#### Validation
Validation diagram (Search by property description) details the validation that the request undergoes.

<h3><img style="float: left;" src="../../images/file.png"> <a href="../../pdfs/services/RequestSearchbyPropertyDescriptionValidationDiagramV1_1.pdf">Validation diagram</a></h3>

PDF, 223KB, 11 pages

This file may not be suitable for users of assistive technology. Request an accessible format.
<br />
<br />

#### Output
A list of properties and title numbers.

### Schemas

<img style="float: left;" src="../../images/file.png"> <a href="../../schemas/RequestSearchByPropertyDescriptionV2_0.xsd">Schema: RequestSearchByPropertyDescriptionV2_0.xsd</a>

XSD, 10KB

This file may not be suitable for users of assistive technology. Request an accessible format.
<p />

This schema provides sample XML for the service.

#### [Schema: RequestSearchByPropertyDescriptionV2_0Example.xml](../../xml/RequestSearchByPropertyDescriptionV2_0Example.xml)
XML, 974Bytes

This file may not be suitable for users of assistive technology. Request an accessible format.

Schema explain describes the request schema for the service.

#### [Schema explain](../../pdfs/services/RequestSearchByPropertyDescriptionV2_0SchemaExplain.pdf)
PDF, 109KB, 10 pages

This file may not be suitable for users of assistive technology. Request an accessible format.

#### [Schema: ResponseSearchByPropertyDescriptionV2_0.xsd](../../schemas/ResponseSearchByPropertyDescriptionV2_0.xsd)
XSD, 20.4KB

This file may not be suitable for users of assistive technology. Request an accessible format.

### Vendor testing

Vendor test data documents the data for testing the service.

#### [Vendor test data](../../pdfs/services/SearchByPropertyDescriptionVendorTest.pdf)
PDF, 207KB, 16 pages

This file may not be suitable for users of assistive technology. Request an accessible format.