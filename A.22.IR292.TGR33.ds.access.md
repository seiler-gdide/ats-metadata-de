
# If No conditions applying to access and use

**Purpose**
	
Conditions applying to access and use must be described at least once for the resource.

**Test method**	

The test checks if a [useLimitation](#useLimitation) element is provided.

If no conditions apply to the access and use of the resource, �no
conditions apply� shall be used. If conditions are unknown, �conditions
unknown� shall be used.

Descriptions of terms and conditions, including where applicable, the
corresponding fees shall be provided through this element or a link
(URL) where these terms and conditions are described.

**Reference(s)**	 

* [IR](./README.md#IR), Chap. 2.9.2 
* [TG](./README.md#TG), Req 33,34

**Test type:** Automated

**Notes**

**Contextual XPath references**

The namespace prefixes used as described in [README.md](./README.md#namespaces).

Abbreviation                                   |  XPath expression (relative to gmd:MD_Metadata)
-----------------------------------------------| -------------------------------------------------------------------------
<a name="useLimitation"></a> useLimitation  | ./gmd:identificationInfo/*/gmd:resourceConstraints/*/gmd:useLimitation

