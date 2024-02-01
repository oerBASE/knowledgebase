# Beispiele

Hier gibt es eine Auflistung unterschiedlicher Setups und Konzepte für OER Repositorien, die im Projekt OEAA aufgesetzt und in den regulären Betrieb überführt wurden:

*Contributions welcome - gerne stellen wir hier auch andere Repositorien mit Konzept, Software und Setup vor!*

## Universität Innsbruck

OER-Repositorium der Universität Innsbruck: [www.oer-repo.uibk.ac.at](www.oer-repo.uibk.ac.at)

**Konzept:**
Wird als open-access Publikationsrepositorium für Lehrmaterialien betrieben. Lehrende können Autor:innen-Zugang beantragen und fertig bearbeitete Materialien hochladen. Diese Materialien müssen mit einem minimalen Set an Metadaten versehen werden und können dann zur Veröffentlichung freigegeben werden. Die Veröffentlichung wird nach oberflächlicher Prüfung der Metadaten von einem Kuratorinnenteam übernommen. Alle Publikationen erhalten einen Persistent Identifier (handle oder auf Wunsch auch DOI).

**LMS:**
Derzeit ist keine Verbindung zum Lernmanagementsystem OpenOlat aufrecht, diese soll in naher Zukunft unidirektional erfolgen: OpenOlat hat einen “edu-sharing-Baustein” und eine Funktion in den Editoren, über die in den dahinter konfigurierten edu-sharing Instanzen gesucht und Materialien direkt in Kurse eingebunden werden können.

**Einschränkungen:**
Eine Bearbeitung der Materialen im Repo (einzeln oder kollaborativ) wäre möglich, ist aber nicht vorgesehen. Der H5P Editor wird nicht angeboten. Ebenso ist es nicht erwünscht, dass Lehrende ihre Materialien im Repo nur ablegen, aber nicht (oder nur für eine eingeschränkte Gruppe) veröffentlichen. Bewerten oder Kommentieren von Materialien ist nicht vorgesehen.

**Anbindungen:**
Das Repositorium wird über die OAI-PMH Schnittstelle geharvestet. Wir wissen, dass die Metadatensätze in den Aggregatoren [www.oerhub.at](www.oerhub.at) und [www.oersi.de](www.oersi.de) durchsucht werden können. Weitere Anbindungen innerhalb der UIBK Systemlandschaft sind vorgesehen: Opencast (Videoplattform), Artemis (Kursplattform).

**Setup:**
- **Software:** Edu-sharing
- Wird durch den ZID der Uni Innsbruck on premise betrieben. Dedizierter Sysadmin, wenig Eigenentwicklung, nur minimale Anpassungen (z. B. am Exporter), Support- und Entwicklungsvertrag mit der Entwicklerfirma Metaventis.
- **Aktuell (01/24):** HA Setup mit jeweils 2 Nodes für Repo, Render, Index
- **Externe Datenbank**
- **Authentifizierung:** LDAP
- **Software Version:** 6.0
- **Geplant (Q1/24):** Präferierter Betrieb im Kubernetes Cluster oder Fallback Docker Setup auf 2 Nodes (wird aktuell getestet, ist problematisch)
- **Externe Datenbank**
- **Authentifizierung:** Shibboleth
- **Software Version:** 8.1

## Universität Graz

OER-Repositorium der Universität Graz: [https://oer-portal.uni-graz.at/edu-sharing/](https://oer-portal.uni-graz.at/edu-sharing/)

**Konzept:**
Ist das Edusharing Repo der Universität Graz. Eingerichtet mit Hilfe von Metaventis und läuft derzeit mit der Version 6.0.11. Auth über Shibboleth für UniGraz User. Normale User haben sehr beschränkte Rechte. Erhöhte Rechte für den Datei/OER Upload müssen gesondert angefragt werden. Veröffentlichte OER werden nachträglich sporadisch auf Vollständigkeit und Korrektheit überprüft.

**Anbindung an externe Systeme:**
- [www.oerhub.at](www.oerhub.at) über OAI-PMH
- [www.oersi.de](www.oersi.de) über OAI-PMH
- Externes ILIAS
- [www.edutags.de](www.edutags.de) über selbstgeschriebenes spring boot projekt als rss feed
- [www.bildungsserver.de](www.bildungsserver.de) über selbstgeschriebenes spring boot projekt als xml im format elixier

**Setup**
Geplant (Q1/24):
Update auf neuere Version mit Umstellung auf Kubernetes. Anbindung unseres LMS Moodle (metaventis hat tinymce editor plugin geplant)

## Universität Klagenfurt

**Konzept**

**LMS**

**Einschränkungen**

**Anbindungen**

**Setup**

<!-- Hier können Sie weitere Informationen zu Repo Klagenfurt hinzufügen -->

## Technische Universität Graz**

**Konzept**

**LMS**

**Einschränkungen**

**Anbindungen**

**Setup**

<!-- Hier können Sie weitere Informationen zu Repo Graz2 hinzufügen -->

## Universität Wien**

**Konzept**

**LMS**

**Einschränkungen**

**Anbindungen**

**Setup**

<!-- Hier können Sie weitere Informationen zu Repo WIen hinzufügen -->
