
# Schema Validierung der Ressource 

**Ziel**	

Prüfung auf Existenz des identificationInfo Elements. 

**Testmethode**	

1. Prüfe, ob das Element identificationInfo als Unterelement von MD_Metadata vorhanden ist.
2. Prüfe, ob das Element identificationInfo als Unterelement von MD_Metadata mehrfach vorhanden ist.
  

**Fehlermeldungen/Warnungen**
* [F] Wenn Element identificationInfo nicht vorhanden ist [1]: "Fehler: Die XML-Datei enthält kein identificationInfo Element als Unterelement von MD_Metadata."
* [W] Wenn mehr als ein identificationInfo Element vorhanden ist[2]: "Warnung: Im Rahmen von INSPIRE wird jedoch nur das erste identificationInfo-Element ausgewertet."


**XPath**
MD_Metadata/identificationInfo[1]


**Referenzen**	 
[AK MD] Abschnitt 2.1


**Test type:** Automated

**Notes**

