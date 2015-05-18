# Zuordnung INSPIRE-Thema / ISO–Themenkategorie 

**Ziel**	

Prüfung auf Existenz einer ISO-Themenkategorie im Element "topicCategory". 

**Testmethode**	

1. Prüfe, ob es sich um einen Daten-Metadatensatz handelt (hierarchieLevel=dataset).
2. Prüfe, ob das Element topicCategory als Unterelement von MD_Metadata/identificationInfo vorhanden ist.
3. Prüfe, ob ein Eintrag aus der Zuordnungstabelle (Zuordnung der INSPIRE-Annex-Themen zu ISO-Themenkategorien) aus Anhang 2 des Konventionen-Dokumentes vorhanden ist.
4. Prüfe, ob die Schreibweise der Spalte ISO-Themenkategorie–EN verwendet wurde.

**Fehlermeldungen/Warnungen**
* [] Wenn es sich nicht um einen Daten-Metadatesatz habdelt, wird der Test nicht durchgeführt [1]. 
* [F] Wenn Element topicCategory nicht vorhanden ist [2]: "Fehler: Es muss ein topicCategory-Element vorhanden sein."
* [F] Wenn kein Eintrag aus der Zuordnungstabelle (ISO-Themenkategorie–EN) vorhanden ist [3/4]: "Fehler: Es muss ein Eintrag aus der Zuordnungstabelle (Zuordnung der INSPIRE-Annex-Themen zu ISO-Themenkategorien) aus Anhang 2 des Konventionen-Dokumentes mit Schreibweise der Spalte ISO-Themenkategorie–EN (z.B. inlandWaters) im topicCategory-Element vorhanden sein."

**XPath**
MD_Metadata/identificationInfo/*/topicCategory

**Referenzen**	 
[AK MD] Abschnitt 2.3

**Test type:** Automated
