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

OER-Portal der Universität Graz: [https://oer-portal.uni-graz.at/edu-sharing/](https://oer-portal.uni-graz.at/edu-sharing/)

**Konzept:**
Ist das edu-sharing-Repositorium der Universität Graz. Das Repo wurde mit Hilfe von metaVentis eingerichtet und läuft derzeit mit der Version 6.0.11. Die Authentifizierung erfolgt über Shibboleth für Angehörige der Universität Graz. Normale User:innen haben sehr beschränkte Rechte, erweiterte Rechte für das Anlegen von OER müssen gesondert angefragt werden. Veröffentlichte OER werden nachträglich auf Vollständigkeit und Korrektheit überprüft.

**Anbindung an externe Systeme:**

- [www.oerhub.at](https://www.oerhub.at) über OAI-PMH
- [www.oersi.de](https://www.oersi.de) über OAI-PMH
- [Plattform der Stiftung SPI](https://www.plattform-spi.de/) über ILIAS-Plugin von edu-sharing
- [www.edutags.de](https://www.edutags.de) über selbstgeschriebenes Spring-Boot-Projekt als RSS-Feed
- [www.bildungsserver.de](https://www.bildungsserver.de) über selbstgeschriebenes Spring-Boot-Projekt als XML im Format Elixier

**Setup:**

- **Authentifizierung:** Shibboleth
- **Software Version:** 6.0.11
- **Geplant (2024):** Update auf neuere Version (8.1) mit Umstellung der Infrastruktur auf Kubernetes. Anbindung an das LMS Moodle (nach Verfügbarkeit des Moodle/TinyMCE-Plugins).

## Universität Klagenfurt

**Konzept**

**LMS**

**Einschränkungen**

**Anbindungen**

**Setup**

<!-- Hier können Sie weitere Informationen zu Repo Klagenfurt hinzufügen -->

## Technische Universität Graz

**Konzept**

**LMS**

**Einschränkungen**

**Anbindungen**

**Setup**

<!-- Hier können Sie weitere Informationen zu Repo Graz2 hinzufügen -->

## Universität Wien

**Konzept** 
https://github.com/phaidra/phaidra
PHAIDRA ist ein Repositorium zur dauerhaften Sicherung von digitalen Beständen an der Universität Wien. Dies schließt Forschungsdaten, offene Bildungsressourcen und sonstige Materialien ein. Wissenschaftliche Dokumente und Materialien der Universität Wien wie Zeitschriftenartikel (auch Pre- und Postprints), Monographien und Sammelwerke (oder Einzelbeiträge aus diesen), Kongressmaterialien, Forschungsberichte, Working Papers u. Ä., werden über die Oberfläche https://uscholar.univie.ac.at/ hochgeladen und in PHAIDRA langzeitarchiviert.

PHAIDRA kann von allen Mitarbeiter*innen und Studierenden der Universität Wien aktiv genutzt werden. Es stehen mehr als 50 Metadatenfelder zur Verfügung (davon 8 Pflichtfelder), die in Ebenen organisiert werden können (Metadaten digitaler Objekte vs. Metadaten dargestellter Objekte). Es gibt sowohl einfache (z. B. Video) als auch komplexe Objekttypen (z. B. Container). Es können mehrere Beziehungen verwendet werden, z. B. um Sammlungen zu erstellen (um Objekte hierarchisch oder in Mengen zu organisieren), verschiedene Objektversionen oder -formate zu verbinden, usw. 

Offene Bildungsressourcen können ab März 2024 über ein eigenes Submit Form hochgeladen werden, das alle Pflichtfelder laut der Dokumentation des OERhub vorsieht: https://www.openeducation.at/fileadmin/user_upload/OEA_TwoPager_Voraussetzungen_und_Vorgaben_f%C3%BCr_die_Anbindung_an_den_OERhub.pdf . Objekte in PHAIDRA werden mit einem persistenten Identifier versehen (handle; auf Wunsch DOI). 

PHAIDRA verwendet primär das Metadatenschema JSON-LD, unterstützt aber auch UWMETADATA (LOM-basiert) und MODS.

Weitere Informationen entnehmen Sie bitte der offiziellen PHAIDRA-Dokumentation: https://www.phaidra.org/docs/overview/ 

**LMS**

**Einschränkungen**
Nutzer*innen können bereits hochgeladene Objekte nicht selbständig löschen. Metadaten sind immer nach außen sichtbar - auch wenn der Zugriff eingeschränkt wurde, weil es sich z. B. um sensible Daten handelt. PHAIDRA beinhaltet nicht nur offene Bildungsressourcen.  

**Anbindungen**
Auf PHAIDRA-Objekte kann auf verschiedene Arten zugegriffen werden:
* Benutzeroberfläche und SEO
* Harvesting: Eine OAI-PMH-Schnittstelle steht zur Verfügung, mit den Formaten oai_dc und oai_openaire. Das dcterms-Format wird in Zukunft hinzugefügt.
* Integrationen: PHAIDRA-API 
Siehe auch die Open-API-Dokumentation des API: https://github.com/phaidra/phaidra-api/blob/master/public/docs/openapi.json und die PHAIDRAorg Webseite: https://www.phaidra.org/docs/api/#creating-simple-objects .

**Setup**
- **Software**: Fedora repository https://fedora.lyrasis.org/ 
- Der Betrieb und die Weiterentwicklung der auf Open Source basierenden Software erfolgt an der Universität Wien.
- **Authentifizierung:** Shibboleth
- **Software Version:** Fedora Version 3.8 und 6+


<!-- Hier können Sie weitere Informationen zu Repo WIen hinzufügen -->
