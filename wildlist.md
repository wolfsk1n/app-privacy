# Privacy Policy / Datenschutzerklärung for WildList

_Last updated / Stand: 2026-05-20_

This privacy policy applies to the mobile application / Diese Datenschutzerklärung gilt für die mobile Anwendung:

**WildList**

---

# ENGLISH

## 1. Controller

Controller responsible for data processing in connection with this app:

AquaTerraLife  
Responsible person: Nils Behr  
Contact: aquaterralife.apps@gmail.com

---

## 2. Overview

WildList is an offline-first species checklist app. The app helps users select regions and animal groups, open prepared species checklists, mark species as seen, manage sightings, create custom species and custom checklists, import or export local data, and track checklist progress.

WildList may process data in the following ways:

- data stored locally on the device for app functionality
- optional local sightings, notes, and location information entered by the user
- local import/export and backup data
- optional custom species and custom checklists created by the user
- optional species or checklist suggestions submitted to WildList for review
- technical data required for app operation
- analytics data through Firebase Analytics, subject to the user's consent and privacy choices where required
- crash and diagnostic data through Firebase Crashlytics, subject to the user's consent and privacy choices where required
- technical configuration data through Firebase Remote Config
- app integrity and abuse-prevention data through Firebase App Check
- advertising-related data through Google AdMob / Google Mobile Ads
- consent-related data through Google User Messaging Platform (UMP)
- map, image, and external content requests where such content is loaded
- optional communication data if the user contacts the developer

WildList currently does not provide mandatory user accounts and does not require cloud sync. If optional cloud sync is introduced in the future, it will be opt-in. Sightings and location data will not be synced to the cloud automatically without an explicit user choice. This privacy policy and the relevant app/store information will be updated before such functionality is released.

---

## 3. Data processed by the app

### 3.1 Data stored locally on your device

WildList stores app-related content locally on the user's device, for example:

- checklist progress, such as species marked as seen
- unlocked checklist status
- privacy and consent settings
- app preferences and settings
- sightings created or imported by the user
- optional notes added by the user
- optional location data for sightings, if entered or selected by the user
- custom species created by the user
- custom checklists created by the user
- imported observation data
- local backup/export data
- cached images, if image caching is enabled

**Purpose:** providing the core functionality of the app.  
**Legal basis (EU/EEA):** Art. 6(1)(b) GDPR, if processing is necessary to provide the app functions requested by the user; otherwise Art. 6(1)(f) GDPR based on the legitimate interest in providing a stable and usable app.

Locally stored checklist data, sightings, custom species, custom checklists, and settings generally remain on the user's device and are not transmitted to the developer's own servers unless the user actively chooses a function that transmits data, such as submitting a suggestion.

Local data can be reset, deleted, exported, or re-imported depending on the app functions available.

### 3.2 Sightings and optional location data

WildList allows users to store sightings. A sighting may include, depending on user input and available app functionality:

- species reference or custom species reference
- checklist reference
- date
- note
- optional place name
- optional latitude and longitude
- optional location accuracy
- creation and update timestamps

Location data is sensitive. WildList is designed so that sighting location data is stored locally unless the user intentionally exports it or uses a future optional cloud/sync function.

Local exports may include sightings and optional location data. Users should only share backup or export files with people or services they trust.

**Purpose:** documenting observations and checklist progress.  
**Legal basis (EU/EEA):** Art. 6(1)(b) GDPR where the user requests this functionality.

### 3.3 Custom species and custom checklists

WildList allows users to create custom species and custom checklists. These may include, depending on user input:

- scientific name
- common or display name
- taxon group
- notes
- checklist name
- checklist description
- selected official species
- selected custom species
- creation and update timestamps

Custom species and custom checklists are private/local by default and are not automatically published or added to official WildList data.

**Purpose:** allowing users to maintain personal species lists and private checklist content.  
**Legal basis (EU/EEA):** Art. 6(1)(b) GDPR.

### 3.4 Suggestions submitted to WildList

WildList may allow users to submit custom species or custom checklists as suggestions for review by WildList administration/moderation.

Submitted suggestions may include, depending on the function used:

- suggested scientific name
- suggested common or display name
- taxon group
- region
- source URL
- notes entered by the user
- checklist name and description
- selected species
- custom species data included in a suggested checklist
- submission timestamp
- optional technical user identifier, if user accounts or authentication are introduced later

Suggestions are stored in Firebase/Cloud Firestore with an initial status such as `pending`. Suggestions are not automatically published and are not automatically added to official WildList data. They may be reviewed manually by WildList administration/moderation.

Users should avoid entering personal data, sensitive information, or third-party personal data in suggestion notes or source fields.

**Purpose:** allowing users to propose new species or checklists for future review.  
**Legal basis (EU/EEA):** Art. 6(1)(a) GDPR where the submission is based on user consent, and/or Art. 6(1)(b) GDPR where the user requests this function.

### 3.5 Import, export, and backups

WildList may allow users to import external observation files, for example CSV or iNaturalist-style exports, and to export local app data as a backup.

A local export may include:

- checklist progress
- unlocked checklist status
- settings
- sightings
- optional location data in sightings
- custom species
- custom checklists
- schema/version metadata such as schemaVersion, appVersion, dataVersion, and exportedAt

Import files may contain observation data, species names, dates, notes, and optional location information depending on the source file.

Export files are created for the user. WildList does not automatically upload local export files to the developer's own servers. Users are responsible for storing and sharing exported files safely.

**Purpose:** data portability, backup, restore, and import of user observations.  
**Legal basis (EU/EEA):** Art. 6(1)(b) GDPR.

### 3.6 Firebase Analytics

WildList uses Firebase Analytics to understand general app usage and improve the app. Analytics may be enabled by default where legally permissible. In regions or cases where consent is required, Analytics is used according to the user's consent and privacy choices.

Firebase Analytics may process coarse app interaction data, for example:

- app opened
- region selected
- animal group selected
- checklist opened
- species checked or unchecked
- search or filter used
- species detail opened
- custom checklist created or opened
- custom species added or removed
- sighting added
- import or export started/completed
- rewarded unlock started/completed/failed
- species or checklist suggestion submitted
- settings or external link opened

WildList is designed so that analytics events do not include sensitive or unnecessarily identifying content. The app should not send the following as analytics parameters:

- species names
- scientific names
- checklist IDs
- custom species IDs
- precise location data
- free text
- notes
- personal data
- exact user observation histories

Analytics parameters, where used, should be coarse, for example `source`, `success`, or count buckets.

**Purpose:** understanding general app usage, improving app quality, detecting usability issues, and prioritizing future development.  
**Legal basis (EU/EEA):** Art. 6(1)(f) GDPR based on the legitimate interest in improving and maintaining the app, where legally permissible; Art. 6(1)(a) GDPR (consent), where consent is required.

The user can manage Analytics through the app's privacy and consent settings where available.

### 3.7 Firebase Crashlytics

WildList uses Firebase Crashlytics to detect, analyze, and fix crashes and stability problems. Crash reporting may be enabled by default where legally permissible, because stable and secure app operation is important for all users. In regions or cases where consent is required, Crashlytics is used according to the user's consent and privacy choices.

Crashlytics may process crash reports and diagnostic information, such as:

- crash logs
- device and app information
- operating system information
- technical diagnostic data
- information about the app state at the time of a crash

Crash reports may contain technical context about the app state. WildList is designed not to intentionally attach sensitive user content such as notes, precise location data, species names, or custom checklist content to crash reports.

**Purpose:** detecting and fixing crashes, improving app stability, and ensuring reliable app operation.  
**Legal basis (EU/EEA):** Art. 6(1)(f) GDPR based on the legitimate interest in providing a stable, secure, and reliable app, where legally permissible; Art. 6(1)(a) GDPR (consent), where consent is required.

The user can manage crash reporting through the app's privacy and consent settings where available.

### 3.8 Firebase Remote Config

WildList uses Firebase Remote Config to retrieve technical configuration values and feature flags, for example whether certain optional app functions are enabled.

Remote Config is not required for the app to work. If Remote Config is unavailable, the app uses local default values.

**Purpose:** technical configuration of the app and safe feature rollout.  
**Legal basis (EU/EEA):** Art. 6(1)(f) GDPR based on the legitimate interest in operating and maintaining the app.

### 3.9 Firebase App Check

WildList uses Firebase App Check or prepares App Check integration to help protect backend services from abuse and unauthorized automated access.

Depending on the platform and build type, App Check may use providers such as Play Integrity or debug providers. App Check may process technical integrity and attestation data.

**Purpose:** protecting backend services and reducing abuse.  
**Legal basis (EU/EEA):** Art. 6(1)(f) GDPR based on the legitimate interest in securing app infrastructure.

### 3.10 Advertising / Google AdMob and Google Mobile Ads

WildList uses or prepares Google AdMob / Google Mobile Ads to display ads. This may include banner ads, native ads, and rewarded ads used to unlock additional functionality such as checklist unlocks.

Ads may be personalized or non-personalized depending on the user's consent status, region, and app settings.

In connection with ads, Google and its partners may process certain data, which can include for example:

- advertising ID
- IP address
- device and app information
- diagnostics and performance information
- interactions with ads
- approximate location inferred from technical data

The actual scope of processing may depend on Google's systems, the user's device settings, region, and consent choices.

**Purpose:** monetization of the app, delivery of ads, fraud prevention, measurement, and service improvement.  
**Legal basis (EU/EEA):**
- for personalized advertising: Art. 6(1)(a) GDPR (consent)
- for non-personalized advertising and technically necessary related processing: Art. 6(1)(f) GDPR, insofar as applicable and legally permissible

The user can change advertising and privacy choices through the app's privacy and consent settings where available.

### 3.11 Google User Messaging Platform (UMP)

WildList uses or prepares Google User Messaging Platform (UMP) to collect and manage advertising consent where required.

UMP may process information necessary to determine whether consent is required and to store or communicate the user's consent choices.

**Purpose:** consent management for advertising and privacy choices.  
**Legal basis (EU/EEA):** Art. 6(1)(c) GDPR where consent management is legally required, and/or Art. 6(1)(f) GDPR for the legitimate interest in documenting privacy choices.

Consent choices can be reset or managed in the app settings where available.

### 3.12 Maps and map tiles

WildList may include map-related features, for example to display sightings with location information.

When map tiles or map data are loaded from third-party providers, technical request data may be transmitted to those providers, for example:

- IP address
- device and browser/app technical information
- requested map tile or map area
- time of request

WildList does not intentionally send user notes or species names to map tile providers as part of normal map tile loading.

**Purpose:** displaying map content and sighting locations requested by the user.  
**Legal basis (EU/EEA):** Art. 6(1)(b) GDPR where the user requests map functionality, and/or Art. 6(1)(f) GDPR for providing map functionality.

The exact map/tile provider may depend on the app configuration. Users should also review the privacy information of the respective map provider where applicable.

### 3.13 Images, external media, and image caching

WildList may display species images from external sources or image URLs stored in the app's data. Images may include license and attribution information.

When images are loaded from external servers, those servers may receive technical request data, for example:

- IP address
- device and app information
- requested image URL
- time of request

WildList may cache images locally on the device to improve loading speed and reduce data usage. Image caching can be disabled in the app settings where available. Disabling image caching prevents new images from being intentionally cached through the app's image caching mechanism, but it may not automatically delete all existing cached files.

**Purpose:** displaying species images and improving app usability.  
**Legal basis (EU/EEA):** Art. 6(1)(b) GDPR where images are part of requested app functionality, and/or Art. 6(1)(f) GDPR for efficient app operation.

### 3.14 Contacting the developer

If you contact the developer by email, the data you provide (for example email address, name, message content) will be processed to handle your request.

**Purpose:** communication and support  
**Legal basis:** Art. 6(1)(b) GDPR and/or Art. 6(1)(f) GDPR

---

## 4. Recipients of data

Your data may be disclosed to the following categories of recipients where necessary:

- Google / Firebase for analytics, crash reporting, remote configuration, app integrity, Firestore storage, advertising, and consent-related services
- Google AdMob / Google Mobile Ads and advertising partners where ads are displayed
- map/tile providers where map content is loaded
- image/media hosting providers where external images are loaded
- technical service providers involved in app operation, if applicable
- public authorities, if there is a legal obligation

Locally stored checklist progress, sightings, custom species, and custom checklists are not transmitted to the developer's own servers unless the user actively chooses a feature that transmits data, such as submitting a suggestion or a future optional cloud sync function.

---

## 5. International data transfers

When using Google services, Firebase services, advertising services, map providers, image hosts, or other third-party services, personal data may be processed outside the European Union or the European Economic Area, including in countries where the level of data protection may differ from EU standards, in particular the United States.

Where required, such transfers are based on appropriate safeguards under applicable data protection law.

---

## 6. Data retention

Locally stored checklist progress, sightings, optional location data, custom species, custom checklists, unlocks, cached images, and settings remain on your device until you delete them, reset them in the app where available, uninstall the app, or clear the app data through your operating system.

Local export files remain wherever the user stores them and must be deleted by the user if no longer needed.

Suggestions submitted to WildList may be retained as long as necessary for review, moderation, documentation, abuse prevention, and app improvement. Rejected or obsolete suggestions may be deleted periodically.

Data processed in connection with support requests is retained only as long as necessary to handle the request and comply with legal retention obligations.

Data processed by Google, Firebase, AdMob, map providers, image hosts, or other third-party services is subject to their own retention periods and privacy rules.

---

## 7. Your rights under GDPR

If the GDPR applies, you may have the following rights:

- right of access
- right to rectification
- right to erasure
- right to restriction of processing
- right to data portability
- right to object
- right to withdraw consent at any time, with effect for the future
- right to lodge a complaint with a supervisory authority

If you wish to exercise your rights, please contact:

**aquaterralife.apps@gmail.com**

Please note that some data is stored only locally on your device. The developer may not be able to access, correct, or delete data that never leaves your device. You can manage such data through the app functions, device settings, local deletion, or uninstalling the app.

---

## 8. Requirement to provide data

You are generally not legally required to provide personal data. However, certain technical data may be necessary for app functionality, ad delivery, consent handling, crash diagnostics, remote configuration, map display, image loading, suggestion submission, or communication with the developer.

If optional data is not provided, some optional functions may not be available or may work only in a limited way.

---

## 9. Children

WildList is not intentionally directed at children where consent or special protections would be required under applicable law. If you believe that personal data of a child has been processed unlawfully, please contact the developer.

---

## 10. Future optional cloud sync

WildList currently does not require cloud sync. If optional cloud sync or account-based synchronization is introduced in the future:

- it will be optional where technically possible
- the app will explain what data is synced
- sightings and location data will not be synced automatically without an explicit user choice
- this privacy policy will be updated before release of the feature
- the relevant app store privacy/data safety information will be updated

Possible future cloud sync data may include checklist progress, custom species, custom checklists, sightings, settings, and optional location data, depending on the user's choices and the final implementation.

---

## 11. Changes to this privacy policy

This privacy policy may be updated from time to time, for example if app functionality changes, third-party services change, or legal requirements change. The current version will be made available at the privacy policy URL and, where applicable, within the app.

---

## 12. Third-party privacy information

For more information about how Google processes data, please review Google's privacy information:

https://policies.google.com/privacy

Google's information about advertising technologies:

https://policies.google.com/technologies/ads

Firebase privacy and security information:

https://firebase.google.com/support/privacy

---

# DEUTSCH

## 1. Verantwortlicher

Verantwortlicher für die Datenverarbeitung im Zusammenhang mit dieser App:

AquaTerraLife  
Verantwortliche Person: Nils Behr  
Kontakt: aquaterralife.apps@gmail.com

---

## 2. Überblick

WildList ist eine offline-first Arten-Checklisten-App. Die App dient dazu, Regionen und Tiergruppen auszuwählen, vorbereitete Artenlisten zu öffnen, Arten als gesehen zu markieren, Sichtungen zu verwalten, eigene Arten und eigene Checklisten anzulegen, lokale Daten zu importieren oder zu exportieren und den Checklisten-Fortschritt zu verfolgen.

WildList kann Daten in folgender Weise verarbeiten:

- lokal auf dem Gerät gespeicherte Daten zur Bereitstellung der App-Funktionen
- optionale lokale Sichtungen, Notizen und Standortinformationen, die vom Nutzer eingegeben werden
- lokale Import-/Export- und Backup-Daten
- optionale eigene Arten und eigene Checklisten, die vom Nutzer erstellt werden
- optionale Arten- oder Checklisten-Vorschläge, die zur Prüfung an WildList gesendet werden
- technische Daten, die für den Betrieb der App erforderlich sind
- Analysedaten über Firebase Analytics, abhängig von Einwilligungs- und Datenschutzeinstellungen, soweit erforderlich
- Absturz- und Diagnosedaten über Firebase Crashlytics, abhängig von Einwilligungs- und Datenschutzeinstellungen, soweit erforderlich
- technische Konfigurationsdaten über Firebase Remote Config
- App-Integritäts- und Missbrauchsschutzdaten über Firebase App Check
- werbebezogene Daten über Google AdMob / Google Mobile Ads
- consentbezogene Daten über Google User Messaging Platform (UMP)
- Karten-, Bild- und externe Inhaltsanfragen, soweit solche Inhalte geladen werden
- optionale Kommunikationsdaten, wenn Nutzer den Entwickler kontaktieren

WildList verwendet aktuell keine verpflichtenden Nutzeraccounts und keinen verpflichtenden Cloud-Sync. Falls zukünftig ein optionaler Cloud-Sync eingeführt wird, erfolgt dieser als Opt-in. Sichtungen und Standortdaten werden nicht automatisch ohne ausdrückliche Nutzerentscheidung in die Cloud synchronisiert. Diese Datenschutzerklärung und die relevanten App-/Store-Informationen werden vor Veröffentlichung einer solchen Funktion aktualisiert.

---

## 3. Von der App verarbeitete Daten

### 3.1 Lokal auf dem Gerät gespeicherte Daten

WildList speichert appbezogene Inhalte lokal auf dem Gerät des Nutzers, zum Beispiel:

- Checklisten-Fortschritt, etwa als gesehen markierte Arten
- Freischaltungsstatus zusätzlicher Checklisten
- Datenschutz- und Consent-Einstellungen
- App-Einstellungen und Präferenzen
- vom Nutzer erstellte oder importierte Sichtungen
- optionale Notizen des Nutzers
- optionale Standortdaten zu Sichtungen, wenn diese vom Nutzer eingegeben oder ausgewählt werden
- eigene Arten, die vom Nutzer erstellt werden
- eigene Checklisten, die vom Nutzer erstellt werden
- importierte Beobachtungsdaten
- lokale Backup-/Export-Daten
- zwischengespeicherte Bilder, wenn Bild-Caching aktiviert ist

**Zweck:** Bereitstellung der Kernfunktionen der App.  
**Rechtsgrundlage (EU/EWR):** Art. 6 Abs. 1 lit. b DSGVO, soweit die Verarbeitung zur Bereitstellung der vom Nutzer gewünschten App-Funktionen erforderlich ist; im Übrigen Art. 6 Abs. 1 lit. f DSGVO auf Grundlage des berechtigten Interesses an einer stabilen und nutzerfreundlichen App.

Lokal gespeicherte Checklistendaten, Sichtungen, eigene Arten, eigene Checklisten und Einstellungen verbleiben grundsätzlich auf dem Gerät des Nutzers und werden nicht an eigene Server des Entwicklers übermittelt, es sei denn, der Nutzer wählt aktiv eine Funktion, die Daten übermittelt, zum Beispiel das Senden eines Vorschlags.

Lokale Daten können je nach verfügbarer App-Funktion zurückgesetzt, gelöscht, exportiert oder reimportiert werden.

### 3.2 Sichtungen und optionale Standortdaten

WildList ermöglicht das Speichern von Sichtungen. Eine Sichtung kann je nach Nutzereingabe und verfügbarer App-Funktion folgende Daten enthalten:

- Artenreferenz oder Referenz auf eine eigene Art
- Checklistenreferenz
- Datum
- Notiz
- optionaler Ortsname
- optionale Breiten- und Längengrade
- optionale Standortgenauigkeit
- Erstellungs- und Aktualisierungszeitpunkte

Standortdaten sind sensibel. WildList ist so ausgelegt, dass Standortdaten zu Sichtungen lokal gespeichert werden, sofern der Nutzer sie nicht bewusst exportiert oder zukünftig eine optionale Cloud-/Sync-Funktion verwendet.

Lokale Exporte können Sichtungen und optionale Standortdaten enthalten. Nutzer sollten Backup- oder Exportdateien nur mit Personen oder Diensten teilen, denen sie vertrauen.

**Zweck:** Dokumentation von Beobachtungen und Checklisten-Fortschritt.  
**Rechtsgrundlage (EU/EWR):** Art. 6 Abs. 1 lit. b DSGVO, soweit der Nutzer diese Funktion anfordert.

### 3.3 Eigene Arten und eigene Checklisten

WildList ermöglicht Nutzern das Erstellen eigener Arten und eigener Checklisten. Diese können je nach Nutzereingabe enthalten:

- wissenschaftlicher Name
- deutscher/angezeigter Name
- Taxongruppe
- Notizen
- Checklistenname
- Checklistenbeschreibung
- ausgewählte offizielle Arten
- ausgewählte eigene Arten
- Erstellungs- und Aktualisierungszeitpunkte

Eigene Arten und eigene Checklisten sind standardmäßig privat/lokal und werden nicht automatisch veröffentlicht oder in offizielle WildList-Daten übernommen.

**Zweck:** Ermöglichung persönlicher Artenlisten und privater Checklisteninhalte.  
**Rechtsgrundlage (EU/EWR):** Art. 6 Abs. 1 lit. b DSGVO.

### 3.4 An WildList gesendete Vorschläge

WildList kann Nutzern ermöglichen, eigene Arten oder eigene Checklisten als Vorschläge zur Prüfung durch WildList-Administration/Moderation einzureichen.

Gesendete Vorschläge können je nach genutzter Funktion enthalten:

- vorgeschlagener wissenschaftlicher Name
- vorgeschlagener deutscher/angezeigter Name
- Taxongruppe
- Region
- Quellen-URL
- vom Nutzer eingegebene Notizen
- Checklistenname und Beschreibung
- ausgewählte Arten
- eigene Artendaten innerhalb einer vorgeschlagenen Checkliste
- Einreichungszeitpunkt
- optionaler technischer Nutzeridentifikator, falls Nutzeraccounts oder Authentifizierung später eingeführt werden

Vorschläge werden in Firebase/Cloud Firestore mit einem initialen Status wie `pending` gespeichert. Vorschläge werden nicht automatisch veröffentlicht und nicht automatisch in offizielle WildList-Daten übernommen. Sie können manuell durch WildList-Administration/Moderation geprüft werden.

Nutzer sollten in Vorschlagsnotizen oder Quellenfeldern keine personenbezogenen Daten, sensiblen Informationen oder personenbezogenen Daten Dritter eingeben.

**Zweck:** Ermöglichung von Vorschlägen für neue Arten oder Checklisten zur späteren Prüfung.  
**Rechtsgrundlage (EU/EWR):** Art. 6 Abs. 1 lit. a DSGVO, soweit die Übermittlung auf Einwilligung beruht, und/oder Art. 6 Abs. 1 lit. b DSGVO, soweit der Nutzer diese Funktion anfordert.

### 3.5 Import, Export und Backups

WildList kann ermöglichen, externe Beobachtungsdateien zu importieren, zum Beispiel CSV- oder iNaturalist-ähnliche Exporte, und lokale App-Daten als Backup zu exportieren.

Ein lokaler Export kann enthalten:

- Checklisten-Fortschritt
- Freischaltungsstatus
- Einstellungen
- Sichtungen
- optionale Standortdaten in Sichtungen
- eigene Arten
- eigene Checklisten
- Schema-/Versionsmetadaten wie schemaVersion, appVersion, dataVersion und exportedAt

Importdateien können je nach Quelldatei Beobachtungsdaten, Artennamen, Datumsangaben, Notizen und optionale Standortinformationen enthalten.

Exportdateien werden für den Nutzer erstellt. WildList lädt lokale Exportdateien nicht automatisch auf eigene Server des Entwicklers hoch. Nutzer sind selbst dafür verantwortlich, exportierte Dateien sicher zu speichern und zu teilen.

**Zweck:** Datenportabilität, Backup, Wiederherstellung und Import von Nutzerbeobachtungen.  
**Rechtsgrundlage (EU/EWR):** Art. 6 Abs. 1 lit. b DSGVO.

### 3.6 Firebase Analytics

WildList verwendet Firebase Analytics, um die allgemeine App-Nutzung besser zu verstehen und die App zu verbessern. Analytics kann standardmäßig aktiviert sein, soweit dies rechtlich zulässig ist. In Regionen oder Fällen, in denen eine Einwilligung erforderlich ist, erfolgt die Nutzung von Analytics entsprechend den Einwilligungs- und Datenschutzeinstellungen des Nutzers.

Falls aktiviert bzw. soweit zulässig, kann Firebase Analytics grobe App-Interaktionen verarbeiten, zum Beispiel:

- App geöffnet
- Region ausgewählt
- Tiergruppe ausgewählt
- Checkliste geöffnet
- Art abgehakt oder deaktiviert
- Suche oder Filter verwendet
- Art-Detailseite geöffnet
- eigene Checkliste erstellt oder geöffnet
- eigene Art hinzugefügt oder entfernt
- Sichtung hinzugefügt
- Import oder Export gestartet/abgeschlossen
- Rewarded Unlock gestartet/abgeschlossen/fehlgeschlagen
- Arten- oder Checklisten-Vorschlag gesendet
- Einstellungen oder externer Link geöffnet

WildList ist so ausgelegt, dass Analytics-Events keine sensiblen oder unnötig identifizierenden Inhalte enthalten. Die App soll insbesondere folgende Daten nicht als Analytics-Parameter senden:

- Artennamen
- wissenschaftliche Namen
- Checklist-IDs
- IDs eigener Arten
- genaue Standortdaten
- Freitexte
- Notizen
- personenbezogene Angaben
- exakte Beobachtungshistorien einzelner Nutzer

Analytics-Parameter sollen, soweit verwendet, grob sein, zum Beispiel `source`, `success` oder Zählbereiche.

**Zweck:** Verständnis der allgemeinen App-Nutzung, Verbesserung der App, Erkennung von Nutzungsproblemen und Priorisierung der weiteren Entwicklung.  
**Rechtsgrundlage (EU/EWR):** Art. 6 Abs. 1 lit. f DSGVO auf Grundlage des berechtigten Interesses an Verbesserung und Wartung der App, soweit rechtlich zulässig; Art. 6 Abs. 1 lit. a DSGVO (Einwilligung), soweit eine Einwilligung erforderlich ist.

Analytics kann über die Datenschutz- und Einwilligungseinstellungen der App verwaltet werden, soweit verfügbar.

### 3.7 Firebase Crashlytics

WildList verwendet Firebase Crashlytics, um Abstürze und Stabilitätsprobleme zu erkennen, zu analysieren und zu beheben. Crash-Reporting kann standardmäßig aktiviert sein, soweit dies rechtlich zulässig ist, da ein stabiler und sicherer App-Betrieb für alle Nutzer wichtig ist. In Regionen oder Fällen, in denen eine Einwilligung erforderlich ist, erfolgt die Nutzung von Crashlytics entsprechend den Einwilligungs- und Datenschutzeinstellungen des Nutzers.

Crashlytics kann Absturzberichte und Diagnosedaten verarbeiten, zum Beispiel:

- Crash-Logs
- Geräte- und App-Informationen
- Betriebssysteminformationen
- technische Diagnosedaten
- Informationen zum App-Zustand zum Zeitpunkt eines Absturzes

Crash-Berichte können technischen Kontext zum App-Zustand enthalten. WildList ist so ausgelegt, dass sensible Nutzerinhalte wie Notizen, genaue Standortdaten, Artennamen oder Inhalte eigener Checklisten nicht absichtlich an Crash-Berichte angehängt werden.

**Zweck:** Erkennung und Behebung von Abstürzen, Verbesserung der App-Stabilität und Sicherstellung eines zuverlässigen App-Betriebs.  
**Rechtsgrundlage (EU/EWR):** Art. 6 Abs. 1 lit. f DSGVO auf Grundlage des berechtigten Interesses an einer stabilen, sicheren und zuverlässigen App, soweit rechtlich zulässig; Art. 6 Abs. 1 lit. a DSGVO (Einwilligung), soweit eine Einwilligung erforderlich ist.

Crash-Reporting kann über die Datenschutz- und Einwilligungseinstellungen der App verwaltet werden, soweit verfügbar.

### 3.8 Firebase Remote Config

WildList verwendet Firebase Remote Config, um technische Konfigurationswerte und Feature Flags abzurufen, zum Beispiel ob bestimmte optionale App-Funktionen aktiviert sind.

Remote Config ist nicht erforderlich, damit die App funktioniert. Wenn Remote Config nicht verfügbar ist, verwendet die App lokale Standardwerte.

**Zweck:** technische Konfiguration der App und sichere Bereitstellung von Funktionen.  
**Rechtsgrundlage (EU/EWR):** Art. 6 Abs. 1 lit. f DSGVO auf Grundlage des berechtigten Interesses am Betrieb und an der Wartung der App.

### 3.9 Firebase App Check

WildList verwendet Firebase App Check bzw. bereitet eine App-Check-Integration vor, um Backend-Dienste vor Missbrauch und unautorisiertem automatisiertem Zugriff zu schützen.

Je nach Plattform und Build-Typ kann App Check Anbieter wie Play Integrity oder Debug Provider verwenden. App Check kann technische Integritäts- und Attestierungsdaten verarbeiten.

**Zweck:** Schutz von Backend-Diensten und Verringerung von Missbrauch.  
**Rechtsgrundlage (EU/EWR):** Art. 6 Abs. 1 lit. f DSGVO auf Grundlage des berechtigten Interesses an der Absicherung der App-Infrastruktur.

### 3.10 Werbung / Google AdMob und Google Mobile Ads

WildList verwendet bzw. bereitet Google AdMob / Google Mobile Ads zur Anzeige von Werbung vor. Dies kann Banner Ads, Native Ads und Rewarded Ads zur Freischaltung zusätzlicher Funktionen, etwa Checklisten-Freischaltungen, umfassen.

Je nach Einwilligungsstatus, Region und App-Einstellungen können personalisierte oder nicht-personalisierte Anzeigen angezeigt werden.

Im Zusammenhang mit Werbung können Google und seine Partner bestimmte Daten verarbeiten, z. B.:

- Werbe-ID
- IP-Adresse
- Geräte- und App-Informationen
- Diagnose- und Leistungsdaten
- Interaktionen mit Anzeigen
- aus technischen Daten abgeleiteter ungefährer Standort

Der konkrete Umfang der Verarbeitung kann von den Systemen von Google, den Geräteeinstellungen des Nutzers, der Region und den getroffenen Einwilligungsentscheidungen abhängen.

**Zweck:** Monetarisierung der App, Auslieferung von Werbung, Betrugsverhinderung, Reichweitenmessung und Verbesserung der Dienste.  
**Rechtsgrundlage (EU/EWR):**
- für personalisierte Werbung: Art. 6 Abs. 1 lit. a DSGVO (Einwilligung)
- für nicht-personalisierte Werbung und damit verbundene technisch erforderliche Verarbeitungen: Art. 6 Abs. 1 lit. f DSGVO, soweit rechtlich zulässig

Soweit in der App vorgesehen, können Datenschutz- bzw. Werbeeinstellungen über die Datenschutz- und Einwilligungseinstellungen der App geändert werden.

### 3.11 Google User Messaging Platform (UMP)

WildList verwendet bzw. bereitet Google User Messaging Platform (UMP) vor, um erforderliche Werbeeinwilligungen abzufragen und zu verwalten.

UMP kann Informationen verarbeiten, die erforderlich sind, um zu bestimmen, ob eine Einwilligung erforderlich ist, und um die Consent-Entscheidungen des Nutzers zu speichern oder zu übermitteln.

**Zweck:** Consent-Management für Werbung und Datenschutzeinstellungen.  
**Rechtsgrundlage (EU/EWR):** Art. 6 Abs. 1 lit. c DSGVO, soweit Consent-Management rechtlich erforderlich ist, und/oder Art. 6 Abs. 1 lit. f DSGVO auf Grundlage des berechtigten Interesses an der Dokumentation von Datenschutzeinstellungen.

Consent-Entscheidungen können, soweit in der App vorgesehen, in den Einstellungen zurückgesetzt oder verwaltet werden.

### 3.12 Karten und Kartenkacheln

WildList kann Kartenfunktionen enthalten, zum Beispiel zur Anzeige von Sichtungen mit Standortinformationen.

Wenn Kartenkacheln oder Kartendaten von Drittanbietern geladen werden, können technische Anfragedaten an diese Anbieter übermittelt werden, zum Beispiel:

- IP-Adresse
- technische Geräte- und App-Informationen
- angefragte Kartenkachel oder angefragter Kartenausschnitt
- Zeitpunkt der Anfrage

WildList sendet im Rahmen des normalen Kartenkachel-Ladens nicht absichtlich Nutzernotizen oder Artennamen an Kartenkachel-Anbieter.

**Zweck:** Anzeige von Karteninhalten und Sichtungsorten, die vom Nutzer angefordert werden.  
**Rechtsgrundlage (EU/EWR):** Art. 6 Abs. 1 lit. b DSGVO, soweit der Nutzer die Kartenfunktion anfordert, und/oder Art. 6 Abs. 1 lit. f DSGVO zur Bereitstellung der Kartenfunktion.

Der konkrete Karten-/Kachel-Anbieter kann von der App-Konfiguration abhängen. Nutzer sollten, soweit relevant, auch die Datenschutzinformationen des jeweiligen Kartenanbieters beachten.

### 3.13 Bilder, externe Medien und Bild-Caching

WildList kann Artenbilder aus externen Quellen oder aus in den App-Daten gespeicherten Bild-URLs anzeigen. Bilder können Lizenz- und Attributionsinformationen enthalten.

Wenn Bilder von externen Servern geladen werden, können diese Server technische Anfragedaten erhalten, zum Beispiel:

- IP-Adresse
- Geräte- und App-Informationen
- angefragte Bild-URL
- Zeitpunkt der Anfrage

WildList kann Bilder lokal auf dem Gerät zwischenspeichern, um Ladezeiten zu verbessern und Datenverbrauch zu reduzieren. Bild-Caching kann in den App-Einstellungen deaktiviert werden, soweit verfügbar. Das Deaktivieren des Bild-Cachings verhindert, dass neue Bilder bewusst über den Bild-Cache-Mechanismus der App gespeichert werden; es löscht jedoch nicht zwingend automatisch alle bereits vorhandenen Cache-Dateien.

**Zweck:** Anzeige von Artenbildern und Verbesserung der Nutzbarkeit der App.  
**Rechtsgrundlage (EU/EWR):** Art. 6 Abs. 1 lit. b DSGVO, soweit Bilder Teil der angeforderten App-Funktion sind, und/oder Art. 6 Abs. 1 lit. f DSGVO für einen effizienten App-Betrieb.

### 3.14 Kontaktaufnahme mit dem Entwickler

Wenn du den Entwickler per E-Mail kontaktierst, werden die von dir übermittelten Daten (z. B. E-Mail-Adresse, Name, Inhalt der Nachricht) zur Bearbeitung deiner Anfrage verarbeitet.

**Zweck:** Kommunikation und Support  
**Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO und/oder Art. 6 Abs. 1 lit. f DSGVO

---

## 4. Empfänger von Daten

Deine Daten können, soweit erforderlich, an folgende Kategorien von Empfängern weitergegeben werden:

- Google / Firebase für Analysen, Absturzberichte, Remote-Konfiguration, App-Integrität, Firestore-Speicherung, Werbung und consentbezogene Dienste
- Google AdMob / Google Mobile Ads und Werbepartner, soweit Werbung angezeigt wird
- Karten-/Kachel-Anbieter, soweit Karteninhalte geladen werden
- Bild-/Medienhosting-Anbieter, soweit externe Bilder geladen werden
- technische Dienstleister, die am Betrieb der App beteiligt sind, falls zutreffend
- öffentliche Stellen, soweit eine gesetzliche Verpflichtung besteht

Lokal gespeicherter Checklisten-Fortschritt, Sichtungen, eigene Arten und eigene Checklisten werden nicht an eigene Server des Entwicklers übermittelt, es sei denn, der Nutzer wählt aktiv eine Funktion, die Daten übermittelt, zum Beispiel das Senden eines Vorschlags oder eine zukünftige optionale Cloud-Sync-Funktion.

---

## 5. Drittlandübermittlungen

Bei der Nutzung von Google-Diensten, Firebase-Diensten, Werbediensten, Kartenanbietern, Bild-Hosts oder anderen Drittanbietern können personenbezogene Daten auch außerhalb der Europäischen Union bzw. des Europäischen Wirtschaftsraums verarbeitet werden, insbesondere in Staaten, in denen möglicherweise kein mit der EU vergleichbares Datenschutzniveau besteht, insbesondere den USA.

Soweit erforderlich, erfolgen solche Übermittlungen auf Grundlage geeigneter Garantien nach dem anwendbaren Datenschutzrecht.

---

## 6. Speicherdauer

Lokal gespeicherter Checklisten-Fortschritt, Sichtungen, optionale Standortdaten, eigene Arten, eigene Checklisten, Freischaltungen, zwischengespeicherte Bilder und Einstellungen verbleiben auf deinem Gerät, bis du sie löschst, in der App zurücksetzt, die App deinstallierst oder die App-Daten über das Betriebssystem entfernst.

Lokale Exportdateien verbleiben dort, wo der Nutzer sie speichert, und müssen vom Nutzer gelöscht werden, wenn sie nicht mehr benötigt werden.

An WildList gesendete Vorschläge können so lange gespeichert werden, wie dies zur Prüfung, Moderation, Dokumentation, Missbrauchsverhinderung und Verbesserung der App erforderlich ist. Abgelehnte oder veraltete Vorschläge können regelmäßig gelöscht werden.

Daten aus Support-Anfragen werden nur so lange gespeichert, wie dies zur Bearbeitung der Anfrage und zur Erfüllung gesetzlicher Aufbewahrungspflichten erforderlich ist.

Daten, die im Zusammenhang mit Google, Firebase, AdMob, Kartenanbietern, Bild-Hosts oder anderen Drittanbietern verarbeitet werden, unterliegen den jeweiligen Aufbewahrungsfristen und Datenschutzbestimmungen dieser Anbieter.

---

## 7. Deine Rechte nach der DSGVO

Soweit die DSGVO anwendbar ist, hast du insbesondere folgende Rechte:

- Recht auf Auskunft
- Recht auf Berichtigung
- Recht auf Löschung
- Recht auf Einschränkung der Verarbeitung
- Recht auf Datenübertragbarkeit
- Recht auf Widerspruch
- Recht auf Widerruf einer Einwilligung mit Wirkung für die Zukunft
- Recht auf Beschwerde bei einer Aufsichtsbehörde

Zur Ausübung deiner Rechte kannst du dich an folgende Kontaktadresse wenden:

**aquaterralife.apps@gmail.com**

Bitte beachte, dass einige Daten ausschließlich lokal auf deinem Gerät gespeichert werden. Der Entwickler kann Daten, die dein Gerät nie verlassen, möglicherweise nicht einsehen, korrigieren oder löschen. Solche Daten kannst du über App-Funktionen, Geräteeinstellungen, lokale Löschung oder Deinstallation der App verwalten.

---

## 8. Pflicht zur Bereitstellung von Daten

Du bist grundsätzlich nicht verpflichtet, personenbezogene Daten bereitzustellen. Bestimmte technische Daten können jedoch für die Funktion der App, die Auslieferung von Werbung, Consent-Management, Absturzdiagnosen, Remote-Konfiguration, Kartenanzeige, Bildladen, Vorschlagsübermittlung oder die Kommunikation mit dem Entwickler erforderlich sein.

Wenn optionale Daten nicht bereitgestellt werden, können bestimmte optionale Funktionen nicht oder nur eingeschränkt verfügbar sein.

---

## 9. Kinder

WildList richtet sich nicht gezielt an Kinder, soweit nach anwendbarem Recht eine besondere Einwilligung oder ein besonderer Schutz erforderlich wäre. Falls du der Ansicht bist, dass personenbezogene Daten eines Kindes unrechtmäßig verarbeitet wurden, kontaktiere bitte den Entwickler.

---

## 10. Zukünftiger optionaler Cloud-Sync

WildList erfordert aktuell keinen Cloud-Sync. Falls zukünftig optionaler Cloud-Sync oder accountbasierte Synchronisierung eingeführt wird:

- erfolgt dies soweit technisch möglich optional
- erklärt die App, welche Daten synchronisiert werden
- werden Sichtungen und Standortdaten nicht automatisch ohne ausdrückliche Nutzerentscheidung synchronisiert
- wird diese Datenschutzerklärung vor Veröffentlichung der Funktion aktualisiert
- werden die relevanten App-Store-Datenschutz-/Data-Safety-Angaben aktualisiert

Mögliche zukünftige Cloud-Sync-Daten können je nach Nutzerentscheidung und finaler Umsetzung Checklisten-Fortschritt, eigene Arten, eigene Checklisten, Sichtungen, Einstellungen und optionale Standortdaten umfassen.

---

## 11. Änderungen dieser Datenschutzerklärung

Diese Datenschutzerklärung kann von Zeit zu Zeit angepasst werden, etwa bei Änderungen der App-Funktionen, Änderungen eingesetzter Drittanbieter-Dienste oder Änderungen der Rechtslage. Die jeweils aktuelle Version wird unter der Datenschutzerklärungs-URL und, soweit vorgesehen, innerhalb der App bereitgestellt.

---

## 12. Informationen zu Drittanbietern

Weitere Informationen zur Datenverarbeitung durch Google findest du unter:

https://policies.google.com/privacy

Informationen von Google zu Werbetechnologien:

https://policies.google.com/technologies/ads

Informationen von Firebase zu Datenschutz und Sicherheit:

https://firebase.google.com/support/privacy
