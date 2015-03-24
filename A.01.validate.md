
# Schema Validierung der Ressource 

**Ziel**	

Durchfürhung der Schemavalidierung des XML-Dokuments. 

**Testmethode**	

Das Dokument muss die Schemavalidierung gegen eines der folgenden Schemata ohne Fehler bestehen:


Validierung gegen ISO AP 1.0:
* http://schemas.opengis.net/csw/2.0.2/profiles/apiso/1.0.0/apiso.xsd

Validierung gegen ISO 19139 Version 2005-DIS with GML 3.2.0:
* http://schemas.opengis.net/iso/19139/20060504/gmd/gmd.xsd

Validierung gegen ISO/TS 19139:2007 with GML 3.2.1:
* http://standards.iso.org/ittf/PubliclyAvailableStandards/ISO_19139_Schemas/gmd/gmd.xsd or
http://schemas.opengis.net/iso/19139/20070417/gmd/gmd.xsd

**Fehlermeldungen/Warnungen**
* [F] Wenn XML nicht wohlgeformt ist: "Fehler: Die XML-Datei ist nicht wohlgeformt."
* [F] Wenn XML nicht schema-valide: "Fehler: Die XML-Datei ist nicht schema-valide. Die XML-Dateien müssen dem Schema XYZ entsprechen. Es folgt die Fehlermeldung der des Schemavalidators: [...]"


**Referenzen**	 

* [IR](./README.md#IR) p16

**Test type:** Automated

**Notes**

