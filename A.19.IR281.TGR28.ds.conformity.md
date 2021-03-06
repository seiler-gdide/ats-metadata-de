
# Conformity

**Purpose**	

The metadata shall include information on the degree of conformity with the implementing
rules on interoperability of spatial data sets and services

**Test method**	

For every conformity statement, one conformance result indicated by a boolean value must be given.

The test first checks if there is at least one conformance [result](#result) of type gco:Boolean. 
It then performs the following actions for every element at ./*/gmd:result:
*	If the element has an element ./*/gmd:pass, it must contain a value of type gco:Boolean.


**Reference(s)**	 

* [IR](./README.md#IR), Chap. 2.8.1
* [TG](./README.md#TG) Req 28
 
**Test type:** Automated

**Notes**

**Contextual XPath references**

The namespace prefixes used as described in [README.md](./README.md#namespaces).

Abbreviation                                   |  XPath expression (relative to gmd:MD_Metadata)
-----------------------------------------------| -------------------------------------------------------------------------
<a name="result"></a> Result   | gmd:dataQualityInfo/*/gmd:report/*/gmd:result

