# Konzeption

Bei der Konzeption eines OER-Repositoriums sind nicht nur technische, sondern auch organisatorische Aspekte zu beachten. Wir haben diese Überlegungen während des Planungs- und Umsetzungsprozesses gesammelt und zu einer Checkliste zusammengestellt.

## Checkliste: 


**Hardware und Setup**

- [ ] Anzahl der erwarteten/gewünschten User:innen
- [ ] Erwarteter/gewünschter Traffic
- [ ] Erwartete Last
- [ ] Anforderungen an Availability (HA Setup)
- [ ] Backup
- [ ] Monitoring


**Integration in existierende Systemumgebung**

- [ ] Welche relevanten Systeme werden in der Institution betrieben (LMS, Medienserver, etc.)?
- [ ] Gibt es Systeme, die außerhalb der Institution betrieben werden, die aber relevant sind?
- [ ] Betreibt die Institution bereits ein Repositorium?
- [ ] Betreibt die Institution bereits einen PID-Server?
- [ ] Gibt es bereits Personal, das ein Repositorium technisch betreut?
- [ ] Gibt es bereits Personal, das ein Repositorium organisatorisch betreut?
- [ ] Gibt es bereits Personal, das Veröffentlichungen in Repositorien redaktionell betreut?


**User:innen**

- [ ] Anzahl der erwarteten/gewünschten User:innen
- [ ] Anzahl der gleichzeitig aktiven User:innen
- [ ] Art der User:innen (Studierende, Lehrende, Forschende, Externe...)
- [ ] Welche Rollen und Rechte gibt es?
- [ ] Gibt es ein Konzept für die Nutzer:innenverwaltung?
- [ ] Gibt es ein Konzept für die Nutzer:innenauthentifizierung?
- [ ] Ist eine Anbindung an ein bestehendes Nutzer:innenverwaltungssystem geplant?
- [ ] Ist Single-Sign-On (SSO) geplant?
- [ ] Welche Daten sollen von den User:innen erfasst werden?
- [ ] Gibt es ein Konzept für den Datenschutz?
- [ ] Gibt es ein Konzept für die User Experience?
- [ ] Gibt es ein Konzept für die Barrierefreiheit?


**Daten**

- [ ] Welche Daten sollen erfasst werden?
- [ ] In welchen Formaten sollen die Daten vorliegen?
- [ ] Welches Granularität der Objekte wird erwartet, welche ist gewünscht?
- [ ] Wie lange sollen die Daten (mindestens, garantiert) gespeichert werden, wird eine Langzeitarchivierung angestrebt?
- [ ] Über welche Schnittstellen bzw. Upload-Oberflächen können Daten eingebracht werden?
- [ ] Sollen andere Systeme (LMS, Medienserver, DMS, Videoportal...) eingebunden werden, über die Daten oder Metadaten an das Repositorium eingebracht werden bzw. die Objekte aus dem Repositorium anzeigen können?
- [ ] Inhalte: ausschließlich OER oder auch andere Inhalte? Sollen OER als solche ausgewiesen sein?
- [ ] Welche Art von Persistent Identifier (DOI, URN, handle) soll vergeben werden?
- [ ] Versionierung: Wie werden Änderungen im Ursprungssystem gehandhabt? Sollen diese Auswirkungen auf das Repo haben? Auch umgekehrt: Sollen Daten, die im  Repo geändert werden, sich auf andere Systeme auswirken? Falls ja, wie  oft sollen die Änderungen synchronisiert werden?
- [ ] Wie werden Löschungen technisch umgesetzt (Tombstone Pages o. Ä.)?



**Metadaten**

- [ ] Welche Metadaten sollen oder müssen mindestens vergeben werden?
- [ ] Welches Metadatenschema ist für den erwarteten Content passend? [OER: LOM, LMRI]
- [ ] Welche Vokabulare sollen/müssen für bestimmte Metadatenkategorien verwendet werden?
- [ ] Sind diese Vokabulare bereits (in maschinenlesbarer Form, öffentlich zugänglich...) vorhanden?
- [ ] Welche Metadaten sollen oder müssen exponiert werden (abhängig davon, ob und wie das Repositorium an andere Systeme angeschlossen ist)?
- [ ] Werden die (Meta-)Daten verlinkt oder kopiert? Falls verlinkt: Ist der Link stabil? Können die Daten im Ursprungssystem  gelöscht werden? (Problematik bei vielen verwaisten Links)
- [ ] Sollen Metadaten KI-gestützt vergeben oder angereichert werden?


**Funktionalität im Repositorium**

- [ ] Welche grundlegenden Funktionen soll das Repositorium bieten? (Content-Erstellung und -Bearbeitung, Gruppierung von Material...)
- [ ] Was sind die Anforderungen an Content-Suche und -Navigation?
- [ ] Sind Content-Bewertung und -Feedback innerhalb des Repositoriums gewünscht? 
- [ ] Soll eine Moderation von Content und/oder Bewertungen möglich sein? 
- [ ] Soll Versionierung möglich sein?
- [ ] Gibt es ein Konzept für die Zugriffskontrolle auf den Content?
- [ ] Gibt es ein Konzept für die Content-Migration?



**Datenauswertung – Statistik – Nachverfolgung**

- [ ] Wie sollen Nutzungsstatistiken ausgewertet werden?
- [ ] Gibt es ein Konzept für die Nachverfolgung der Nutzung, Reichweite, Interaktion und Wirkung? 
- [ ] Sollen Nutzungserlebnis und Zufriedenheit evaluiert werden? ?
- [ ] Sollen Verbesserungsvorschläge, Feedback, Fehlermeldungen eingereicht werden können?


**Leitlinien und rechtliche Aspekte**

- [ ] Gibt es ein Konzept für Leitlinien und rechtliche Aspekte?
- [ ] Ist der Rechtsdienst der Institution eingebunden? 
- [ ] Können Nutzungsbedingungen, Uploadrichtlinien und Leitlinien für die Lizenzierung bereitgestellt werden? 


## Zum Nachlesen

C. Hackl, Chr. Ladurner, A. Parschalk, J. Schindler, M. Schmid, R. Ganguly, O. Gröblinger: **An der Schnittstelle von E-Learning-Zentren, Zentralen IT-Services und Bibliotheken** - 
Interdisziplinäre Zusammenarbeit zur Entwicklung einer nationalen Infrastruktur für Open Educational Resources (OER) aus dem österreichischen Hochschulraum. In *Handbuch Repositorienmanagement*, Hg. v. Blumesberger et al.

Open Educational Resources (OER) etablieren sich in der Lehre aktuell analog zu offenen Praktiken in Wissenschaft und Forschung. Open Education Austria Advanced, ein Projekt österreichischer Universitäten, unterstützt diese Entwicklung mit dem gemeinsamen Aufbau eines Gesamtpakets für OER: der Ausbau lokaler OER-Repositorien und einer Meta-Suchmaschine (OERhub), sowie begleitende Maßnahmen wie Zertifizierung, Qualifizierung und der Wissenstransfer zwischen beteiligten und interessierten Hochschulen. Die erfolgreiche Umsetzung dieses Vorhabens bedingt die Zusammenarbeit von E-Learning-Zentren, Zentralen IT-Services und Bibliotheken. Der folgende Beitrag thematisiert die Arbeit an dieser Schnittstelle inklusive der unterschiedlichen Herangehensweisen und Anforderungen der Beteiligten.
