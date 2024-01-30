# Konzeption
# eines OER Repositoriums

Bei der Konzeption eines OER Repositoriums sind nicht nur technische sondern auch organisatorische Aspekte zu beachten. Wir haben diese Überlegungen während des Planungs- und Umsetzungsprozesses gesammelt und zu einer Checkliste zusammengestellt. 

## Checkliste: 




**Hardware und Setup**

[ ] Anzahl der erwarteten/gewünschten User
- [ ] Erwarteter/gewünschter Traffic
- [ ] Erwartete Last
- [ ] Anforderungen an Availability (HA Setup)
- [ ] Backup
- [ ] Monitoring


**Integration in existierende Systemumgebung**

- [ ] Welche relevanten Systeme werden in der Institution betrieben (LMS, Medienserver, etc.)?
- [ ] Gibt es Systeme, die außerhalb der Institution betrieben werden, die aber relevant sind?
- [ ] Betreibt die Institution bereits ein Repositorium?
- [ ] Betreibt die Institution bereits einen PID Server?
- [ ] Gibt es bereits Personal, das ein Repositorium technisch betreut?
- [ ] Gibt es bereits Personal, das ein Repositorium organisatorisch betreut?
- [ ] Gibt es bereits Personal, das Veröffentlichungen in Repositorien redaktionell betreut?


**User**

- [ ] Anzahl der erwarteten/gewünschten User
- [ ] Anzahl der gleichzeitig aktiven User
- [ ] Art der User (Studierende, Lehrende, Forschende, Externe, ...)
- [ ] Welche Rollen und Rechte gibt es?
- [ ] Gibt es ein Konzept für die Nutzerverwaltung?
- [ ] Gibt es ein Konzept für die Nutzerauthentifizierung?
- [ ] Ist eine Anbindung an ein bestehendes Nutzerverwaltungssystem geplant?
- [ ] Ist Single-Sign-On (SSO) geplant?
- [ ] Welche Daten sollen von den Usern erfasst werden?
- [ ] Gibt es ein Konzept für den Datenschutz?
- [ ] Gibt es ein Konzept für die User Experience?
- [ ] Gibt es ein Konzept für die Barrierefreiheit?


**Daten**

- [ ] Welche Daten sollen erfasst werden?
- [ ] In welchen Formaten sollen die Daten vorliegen?
- [ ] Welches Granularität der Objekte wird erwartet, welche ist gewünscht?
- [ ] Wie lange sollen die Daten (mindestens, garantiert) gespeichert werden, wird eine Langzeitarchivierung angestrebt?
- [ ] Über welche Schnittstellen bzw. Upload-Oberflächen können Daten eingebracht werden?
- [ ] Sollen andere Systeme (LMS, Medienserver, DMS, Videoportal….) eingebunden werden, über die Daten oder Metadaten an das Repositorium eingebracht werden bzw. die Objekte aus dem Repositorium anzeigen können?
- [ ] Inhalte: ausschließlich OER oder auch andere Inhalte? Sollen OER als solche ausgewiesen sein?
- [ ] Welche Art von Persistent Identifier (DOI, URN, handle) soll vergeben werden?
- [ ] Versionierung: Wie werden Änderungen Im Ursprungssystem gehandhabt? Sollen diese  Auswirkungen auf das Repo haben? Auch umgekehrt, sollen Daten, die im  Repo geändert werden sich auf andere Systeme auswirken? Falls ja, wie  oft sollen die Änderungen synchronisiert werden?
- [ ] Wie werden Löschungen technisch umgesetzt (Tombstone Pages o.ä- ) 



**Metadaten**

- [ ] Welche Metadaten sollen oder müssen mindestens vergeben werden?
- [ ] Welches Metadatenschema ist für den erwarteten Content passend? [OER: LOM, LMRI]
- [ ] Welche Vokabulare sollen/müssen für bestimmte Metadatenkategorien verwendet werden?
- [ ] Sind diese Vokabulare bereits (in maschinenlesbarer Form, öffentlich zugänglich,…) vorhanden?
- [ ] Welche Metadaten sollen oder müssen exponiert werden (abhängig ob und wie das Repositorium an andere Systeme angeschlossen ist)
- [ ] Werden die (Meta)Daten verlinkt oder kopiert? Falls verlinkt: ist der Link stabil? können die Daten im Ursprungssystem  gelöscht werden? (Problematik bei vielen verwaisten Links)
- [ ] Sollen Metadaten KI-Gestützt vergeben oder angereichert werden? 


**Funktionalität im Repositorium**

- [ ] Welche grundlegenden Funktionen soll das Repositorium bieten?
- [ ] Content-Erstellung und -Bearbeitung, Gruppierung von Material
- [ ] Was sind die Anforderungen an Content-Suche und -Navigation
- [ ] Ist Content-Bewertung und -Feedback innerhalb des Repositoriums gewünscht? 
- [ ] Soll eine Moderation von Content und/oder Bewertungen möglich sein? 
- [ ] Soll Versionierung möglich sein?
- [ ] Gibt es ein Konzept für die Zugriffskontrolle auf den Content?
- [ ] Gibt es ein Konzept für die Content-Migration?



**Datenauswertung – Statistik – Nachverfolgung**

- [ ] Wie sollen Nutzungsstatistiken ausgewertet werden?
- [ ] Gibt es ein Konzept für die Nachverfolgung der Nutzung, Reichweite, Interaktion und Wirkung? 
- [ ] Soll Nutzungserlebnis und Zufriedenheit evaluiert werden? ?
- [ ] Sollen Verbesserungsvorschläge, Feedback, Fehlermeldungen eingereicht werden können?


**Leitlinien und Rechtliche Aspekte**

- [ ] Gibt es ein Konzept für Leitlinien und rechtliche Aspekte?
- [ ] Ist der Rechtsdienst der Institution eingebunden? 
- [ ] Können Nutzungsbedingungen, Uploadrichtlinien und Leitlinien für die Lizensierung bereitgestellt werden? 




- Text "An der Schnittstelle" - OER Repositorien und ihre institutionelle Verankerung
