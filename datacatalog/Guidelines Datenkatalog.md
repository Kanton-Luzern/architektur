# Guidelines Datenkatalog
## Ziele der Guidelines
Die Guidelines sollen Datenmanager, Datenarchitekten, Data Stewards und Data Owners bei der Erstellung und Pflege von Datenkatalogen unterstützen.

## Einsatzzwecke von Datenkatalogen
Datenkataloge können grundsätzlich für externe Zwecke (Publikation von Daten für Nutzung ausserhalb der Organisation) und für interne Zwecke verwendet werden. Die Ausgestaltung der Kataloge bezüglich unterstützte Funktionalität und Attribute für Datensammlungen sowie die aufgenommenen Datensammlungen werden dem Einsatzzweck angepasst. Für die unterschiedlichen Einsatzzwecke kann unterschiedliche, spezialisierte Software verwendet werden.

## Was ist ein guter Eintrag im Datenkatalog?
### Was sollte in den Datankatalog aufgenommen werden (Relevanz)?
Für die Publikation von Daten
- Die Daten werden nachgefragt, oder 
- Es besteht ein politisches Mandat für die Publikation
Für die interne Nutzung
- Die Datensammlung wird verwendet, d.h. Daten werden erzeugt oder verändert
- Die Datensammlung hat Nutzen für die Leistungserbringung innerhalb der Verwaltung
Datensammlungen können geführt werden
- in IT-Systemen, als Tabelle, über mehrere Tabellen verteilt, als Subset von Tabellen oder als Text- oder binäre Objekte
- in Dateiablagen, als Dokumente oder Dateien mit Deten in einem oder mehreren Verzeichnissen oder als einzelnes Dokument oder Datei
- als Webpages, Content in einem Content Management System oder als Wiki-Content
### Was sollte *nicht* in den Datenkatalog aufgenommen werden?
Für die Publikation von Daten:
- Duplikate anderer Datensammlungen
- Temporäre Daten, Zwischenstände in Verarbeitungspipelines
- Backups und ungenutzte Archive
- Datensammlungen von Entwicklungs- und Pilotprojekten die sich noch ändern können
- Daten, die einzelnen Personen zugeordnet sind: Downloads, individuelle Einstellungen und Customizing, Bookmarks, individuelle Arbeitsdateien und Entwürfe
- Obsolete Daten ohne historischen Wert, ungepflegte Datensammlungen
Für die interne Nutzung können alle Datensammlungen in Kataloge aufgenommen werden, je nach Priorität und angestrebten Zweck. Insbesondere wird in vielen Fällen Wert gelet auf
- Ermittlung von Duplikaten, insbesondere von lokal gepflegten und teilweise mit Änderungen versehenen Duplikation
- Ermittlung von ungenutzten und obsoleten Daten
In den meisten Fällen sollten gewisse Datensammlungen nicht aufgenommen werden:
- Explizit als Backups erstellte Datensammlungen
- Zwischenstände in der Verarbeitung
- Daten, die Kontext für die individuelle Nutzung von IT-Systemen bereitstellen, und individuell erstellte Arbeitsdateien
### Wieviele Einträge werden in den Datenkatalog aufgenommen (Granularität)?
Separate Einträge werden aufgenommen, wenn sich die Datensammlungen signifikant unterscheiden:
- unterschiedliche Data Owner und Data Stewards
- repräsentieren unterschiedliche Geschäftskonzepte
- Nutzergruppen überlappen sich wenig, die Daten werden überwiegend nicht zusammen verwendet
- unterschiedliche Datenklassifikation, Zugrifsskontrollen oder andere rechtliche Basis
- unterschiedliche Qualitätsmassstäbe
- unterschiedliche Aktualisierungs- oder Veröffentlichungsfrequenzen
## Was ist sind gute Titel und Beschreibung eines Eintrages im Datenkatalog?
Gute Titel und Beschreibungen unterstützen das Auffinden von Datensammlungen durch Fachnutzer und auch für fachfremde Nutzer. Fachnutzer kennen und nutzen das Fachvokabular, um Datensammlungen zu suchen. Fachvokabular beinhaltet Begriffe, die ausserhalb des Faches andere BEdeutung haben oder generell ungebräuchlich sind. Fachfremde Nutzer verwenden Umschreibungen aus der Alltagssprache.
Neben dem Titel wird die Suche im Katalog unterstüzt durch
- Schlagwörter, die aus einem vorgegebenen Katalog auszuwählen sind
- Frei wählbare Stichwärter
- Angabe eines Raumbezugs (Land, Kanton, Gemeinde, andere Lokationen)
- Angabe eines Zeitbezuges
- Natürliche Sprache oder Sprachen, die in der Datensammlung verwendet werden
Eine mögliche Richtlinie
- Titel beginnt mit einem Substantiv, welches das grundlegende Thema der Datensammlung beschreibt
- Es folgen bestimmende Attriubute, z.B: Menge, Subsets
- Raumbezug und Zeitbezug, damit diese Angaben beim Download der Datensammlung und Auflösung der Verlinkung zu den Metadaten im Katalog erhalten bleiben
