# Privacy Policy / Datenschutzerklärung for AquaTerraCare

*Last updated / Stand: 2026-08-03*

This privacy policy applies to the mobile application / Diese Datenschutzerklärung gilt für die mobile Anwendung:

**AquaTerraCare**

---

# ENGLISH

## 1. Controller

Controller responsible for data processing in connection with this app:

**AquaTerraLife**
Responsible person: Nils Behr
Postal address: **[insert postal address before publication]**
Contact: **[aquaterralife.apps@gmail.com](mailto:aquaterralife.apps@gmail.com)**

---

## 2. Overview

AquaTerraCare is an application for managing aquariums, terrariums, plant vivariums and other habitats. The app enables users to document habitats, organisms, species, care tasks, care logs, environmental parameters, measurements and related information.

AquaTerraCare follows an offline-first approach. The core app functions are designed to work without a permanent internet connection. Most content entered by users is initially stored locally on their device.

Depending on the functions used and the user’s settings, AquaTerraCare may process data in the following ways:

* local storage of app content on the user’s device
* local notifications for care reminders
* user-controlled backup, export and import
* optional cloud synchronization through Firebase Cloud Firestore
* technical crash and diagnostic reporting through Firebase Crashlytics
* app usage analysis through Firebase Analytics
* advertising-related processing through Google AdMob
* communication data if the user contacts the developer

Cloud synchronization, analytics and advertising functions may require an internet connection.

---

## 3. Data processed by the app

### 3.1 Data stored locally on the device

AquaTerraCare may store the following content locally on the user’s device:

* habitats, aquariums, terrariums, plant vivariums and comparable units
* habitat names, types, descriptions and notes
* organisms and animal or plant populations
* species assignments
* common and scientific species names
* custom species entries
* quantities and organism-related metadata
* recurring and non-recurring care tasks
* task due dates, recurrence settings and completion status
* task completions and skipped tasks
* care logs and history entries
* environmental parameter definitions
* measurements such as temperature, humidity, pH or other values
* measurement dates and notes
* notification and reminder settings
* onboarding status
* language, appearance and other app settings
* backup and import-related metadata
* technical identifiers required to link related local records

The exact content depends on which functions the user chooses to use. Users should avoid entering unnecessary personal data or sensitive information in free-text fields.

**Purpose:** Providing the requested app functions, locally organizing habitat and care information, displaying histories and measurements, scheduling reminders and maintaining app settings.

**Legal basis for users in the EU/EEA:** Art. 6(1)(b) GDPR where processing is necessary to provide the functions requested by the user; otherwise Art. 6(1)(f) GDPR based on the legitimate interest in providing a stable, functional and user-friendly application.

Data stored exclusively in the local app database is not automatically transmitted to the developer.

---

### 3.2 Local notifications and reminders

AquaTerraCare may schedule local notifications to remind users of upcoming or due care tasks.

For this purpose, the app may process locally:

* task title
* due date and time
* reminder status
* technical notification identifier
* information required to calculate recurring reminders

Notification scheduling is generally performed locally on the device. The app may request the operating system’s permission to display notifications.

The user can disable individual task reminders, globally disable notifications in the app where available, or revoke notification permissions in the device settings.

**Purpose:** Reminding users of care tasks requested by them.

**Legal basis:** Art. 6(1)(b) GDPR.

---

### 3.3 Backup, export and import

AquaTerraCare allows users to export their app data into a backup file and to restore data by importing a compatible backup.

Backups may include, depending on the stored content:

* habitats
* organisms
* species and custom species
* care tasks and task completions
* care logs
* parameter definitions and measurements
* app settings
* reminder settings
* technical identifiers and relationships between records

Backup files are generally created in a structured JSON format.

The user decides:

* whether to create a backup
* where the backup is stored
* whether it is shared with another app or service
* whether and when it is imported again

When a user selects an external storage location, file manager, email provider, cloud storage provider or sharing service, that third-party provider may process the backup file according to its own privacy policy. AquaTerraCare has no control over such external processing.

Backups may contain detailed information about the user’s habitats, animals, plants and care routines. Users should store and transmit backup files securely.

**Purpose:** Data portability, manual backup, device migration and restoration of app data.

**Legal basis:** Art. 6(1)(b) GDPR.

---

### 3.4 Optional cloud synchronization

AquaTerraCare provides or is being prepared to provide optional cloud synchronization through **Firebase Cloud Firestore**, a service provided by Google.

Cloud synchronization is not required for the basic offline use of AquaTerraCare. It is activated only when the user selects or enables the relevant synchronization function.

Depending on the implemented synchronization scope, the following information may be transmitted to and stored in Cloud Firestore:

* habitats and associated metadata
* organisms and populations
* species and custom species
* care tasks
* task completion and skip history
* care logs
* environmental parameters
* measurements
* app and synchronization settings
* timestamps
* record identifiers
* information required to associate synchronized records with the user or installation
* technical synchronization metadata

If user accounts or Firebase Authentication are used, the following data may additionally be processed, depending on the selected login method:

* user identifier
* email address
* authentication provider
* authentication tokens or technical authentication metadata
* account creation and login timestamps

AquaTerraCare should not use synchronized habitat or organism data for advertising purposes.

**Purpose:**

* synchronizing app data between devices
* restoring synchronized data
* enabling user-controlled cloud storage
* maintaining data consistency across authorized devices

**Legal basis:** Art. 6(1)(b) GDPR, because synchronization is performed at the user’s request. Where optional processing is based on a separate consent decision, Art. 6(1)(a) GDPR may additionally apply.

Users can disable cloud synchronization in the app where this function is available. Disabling synchronization does not necessarily delete data already stored in the cloud. A separate deletion function or request may be required.

Before activating cloud synchronization, users should be informed within the app about the data concerned and the available controls.

---

### 3.5 Firebase Crashlytics

AquaTerraCare uses **Firebase Crashlytics**, a crash-reporting service provided by Google, to identify crashes, technical errors and stability problems.

Crashlytics may process information such as:

* installation or instance identifier
* device model
* operating system and operating system version
* app version and build number
* time of a crash or error
* crash stack traces
* technical logs
* memory and execution status
* information about the app state at the time of the error
* diagnostic and performance information

AquaTerraCare does not intentionally attach the content of habitats, organisms, care logs, measurements or backups to Crashlytics reports. However, technical error messages may in individual cases contain limited contextual information if such information becomes part of an automatically generated error message. The app should therefore avoid including user-generated content in diagnostic logs.

**Purpose:** Detecting, analyzing and fixing crashes and technical errors, maintaining security and improving app stability.

**Legal basis:** Art. 6(1)(f) GDPR, based on the legitimate interest in providing a secure, stable and technically reliable application. Where consent is legally required for storing or accessing information on the user’s device or for the relevant processing, Crashlytics is activated on the basis of Art. 6(1)(a) GDPR and the applicable telecommunications or ePrivacy rules.

Collection through Crashlytics may be disabled or restricted through app privacy settings where such a control is provided.

---

### 3.6 Firebase Analytics

AquaTerraCare uses or may use **Firebase Analytics**, an analytics service provided by Google.

Depending on the technical configuration, consent status and enabled functions, Firebase Analytics may process information such as:

* app instance or installation identifier
* device and operating system information
* app version
* language and general region information
* app start and session information
* screen views
* interactions with app functions
* technical events
* approximate usage duration
* diagnostic and performance information
* advertising identifiers, where available and legally permitted

AquaTerraCare should not deliberately transmit user-entered habitat names, animal names, notes, care-log content, measurements or backup contents as Analytics event parameters.

Analytics is used only after obtaining consent where consent is legally required. Users can withdraw consent with effect for the future through the app’s privacy settings where available. The withdrawal does not affect the lawfulness of processing performed before the withdrawal.

**Purpose:**

* understanding general app usage
* identifying frequently or rarely used functions
* improving usability
* identifying technical problems
* supporting product development

**Legal basis:** Art. 6(1)(a) GDPR where consent is required or requested. Processing strictly necessary for security or technical operation may, in limited cases, be based on Art. 6(1)(f) GDPR, provided that the legal requirements are met.

---

### 3.7 Advertising through Google AdMob

AquaTerraCare uses or may use **Google AdMob**, an advertising service provided by Google, to display advertisements and finance the app.

Depending on the user’s location, consent choices, device settings and Google’s technical systems, personalized, non-personalized or limited ads may be displayed.

In connection with advertising, Google and participating advertising partners may process information including:

* advertising identifier
* app instance or device identifiers
* IP address
* approximate location derived from the IP address
* device manufacturer and model
* operating system
* app version
* language
* advertising consent status
* interactions with advertisements
* ad impressions and clicks
* diagnostic and performance information
* information used for fraud prevention, frequency capping and aggregated reporting

Personalized advertising may use information about interests, previous interactions or other data available to Google and participating advertising providers.

Non-personalized advertising is not based on a user profile for targeted advertising. However, identifiers or other technical information may still be processed for purposes such as frequency capping, fraud prevention, ad delivery and aggregated reporting.

Where legally required, AquaTerraCare requests consent before loading advertising services or accessing advertising identifiers. If consent is not given, advertisements may be restricted, non-personalized or unavailable, depending on the legally and technically available configuration.

**Purpose:**

* financing and monetizing the app
* delivering advertisements
* measuring ad performance
* limiting repeated advertisements
* preventing invalid traffic and fraud
* complying with advertising and consent requirements

**Legal basis:**

* personalized advertising: Art. 6(1)(a) GDPR
* access to or storage of information on the device: consent under the applicable telecommunications or ePrivacy rules where required
* non-personalized or limited advertising: Art. 6(1)(a) GDPR where consent is legally required for the identifiers or technologies used; otherwise Art. 6(1)(f) GDPR only to the extent legally permissible

Users may be able to review or change their privacy and advertising choices in the app settings or through the consent interface provided in the app.

---

### 3.8 Contacting the developer

If a user contacts the developer by email, the data provided in the communication will be processed. This may include:

* email address
* name
* date and time of the message
* subject
* message content
* attachments
* technical information voluntarily submitted for support

Users should not include unnecessary sensitive data in support requests.

**Purpose:** Responding to questions, processing support requests, handling bug reports and communicating with users.

**Legal basis:** Art. 6(1)(b) GDPR where the communication relates to app use or a contractual relationship; otherwise Art. 6(1)(f) GDPR based on the legitimate interest in handling inquiries and providing support.

---

## 4. Recipients of data

Depending on the functions used, personal data may be disclosed to the following recipients or categories of recipients:

* **Google Ireland Limited and affiliated Google companies**, in connection with Firebase, Cloud Firestore, Firebase Authentication, Firebase Analytics, Firebase Crashlytics and Google AdMob
* advertising partners participating in Google AdMob, depending on the consent choices and ad configuration
* operating-system and app-store providers, particularly Google Play
* email and hosting providers used for communication and publication of the privacy policy
* storage, sharing or cloud providers selected by the user for exported backup files
* technical service providers engaged in app operation, maintenance or support
* public authorities or courts where disclosure is required by law

Local habitat, organism, care and measurement data is not disclosed to the developer merely because it is stored in the local database.

---

## 5. International data transfers

Google and other service providers may process data outside the European Union or European Economic Area, including in the United States and other countries whose level of data protection may differ from that of the EU/EEA.

Where required, transfers are based on appropriate safeguards under Chapter V GDPR, such as:

* an adequacy decision by the European Commission
* participation in a recognized data-transfer framework
* standard contractual clauses
* additional technical and organizational safeguards

Further information is available in Google’s privacy and data-transfer documentation.

---

## 6. Data retention

### 6.1 Local app data

Locally stored app data remains on the device until:

* the user deletes individual records
* the user resets or deletes the app data
* the app is uninstalled
* an import replaces the existing local database
* the operating system deletes the app data

### 6.2 Backup files

Exported backup files remain stored until the user deletes them from the selected storage location or service. AquaTerraCare does not automatically control copies created or shared by the user.

### 6.3 Cloud-synchronized data

Cloud-synchronized data is retained until:

* the user deletes the relevant data
* the user uses an available cloud-data deletion function
* the user requests deletion where applicable
* the relevant Firebase project or account is deleted
* retention is otherwise required by law

Merely disabling synchronization may not delete data already stored in the cloud.

### 6.4 Analytics, Crashlytics and AdMob

Data processed through Firebase Analytics, Firebase Crashlytics and Google AdMob is retained according to the configured retention settings, the applicable Google service terms and Google’s privacy policies.

### 6.5 Support communications

Support requests are retained only as long as necessary to process the request, document the communication, defend or establish legal claims and comply with statutory retention obligations.

---

## 7. Consent and withdrawal

Where processing is based on consent, users may withdraw their consent at any time with effect for the future.

Depending on the implemented app version, consent settings may be available for:

* Firebase Analytics
* Firebase Crashlytics
* personalized or non-personalized advertising
* advertising partners
* cloud synchronization

Withdrawal does not affect processing already performed lawfully before the withdrawal.

Disabling a function may limit the availability of associated features. For example:

* disabling notifications prevents care reminders
* disabling cloud synchronization prevents synchronization between devices
* refusing advertising consent may result in limited advertising or no advertisements
* refusing Analytics does not prevent use of the core offline functions

---

## 8. Your rights under GDPR

If the GDPR applies, users may have the following rights:

* right of access under Art. 15 GDPR
* right to rectification under Art. 16 GDPR
* right to erasure under Art. 17 GDPR
* right to restriction of processing under Art. 18 GDPR
* right to data portability under Art. 20 GDPR
* right to object under Art. 21 GDPR
* right to withdraw consent under Art. 7(3) GDPR
* right to lodge a complaint with a data protection supervisory authority under Art. 77 GDPR

Where data is stored exclusively on the user’s device and is not accessible to the developer, the developer may not be technically able to access, correct or delete that local data. The user can manage such data directly in the app, through backup functions, by deleting app data or by uninstalling the app.

Requests relating to cloud data, support communication or other data accessible to the developer may be sent to:

**[aquaterralife.apps@gmail.com](mailto:aquaterralife.apps@gmail.com)**

Users also have the right to lodge a complaint with the competent data protection supervisory authority. They may contact the supervisory authority of their habitual residence, place of work or the place of the alleged infringement.

---

## 9. Right to object

Where processing is based on Art. 6(1)(f) GDPR, users have the right to object to the processing on grounds relating to their particular situation.

If data is processed for direct marketing purposes, users have the right to object at any time without stating reasons.

---

## 10. Requirement to provide data

Users are generally not legally required to provide personal data.

However:

* local app content is required if the relevant organizational functions are to be used
* notification permissions are required to display reminders
* an internet connection and the required synchronization information are necessary for cloud synchronization
* technical information may be necessary for Crashlytics, Analytics or advertising functions
* an email address and message content are necessary if the user contacts support

Core offline app functions should remain available without enabling optional cloud synchronization, Analytics or personalized advertising, except where technical or legal restrictions prevent this.

---

## 11. Automated decision-making and profiling

AquaTerraCare itself does not use automated decision-making that produces legal effects or similarly significantly affects users.

Google AdMob and participating advertising providers may use profiling for personalized advertising where the user has given the required consent. Details are determined by the respective providers and the user’s consent choices.

---

## 12. Children

AquaTerraCare is not intentionally directed specifically at children in circumstances where parental consent or other special protection is required under applicable law.

The app is intended as an organizational tool for responsible keepers of aquariums, terrariums, plants and animals. If a parent or guardian believes that a child’s personal data has been processed unlawfully, they should contact the developer.

---

## 13. Data security

AquaTerraCare uses technical and organizational measures intended to protect data against unauthorized access, loss, alteration or disclosure.

These measures may include:

* local app isolation provided by the operating system
* encrypted network transmission
* Firebase security rules
* authentication and authorization controls for cloud data
* transaction-based backup restoration
* separation of local app content from analytics and crash-reporting events
* data minimization
* user-controlled synchronization and export functions

No method of electronic storage or transmission can guarantee absolute security.

Users are responsible for protecting:

* their device
* device access credentials
* cloud or authentication account credentials
* exported backup files
* files shared with third-party services

---

## 14. Open-source software

AquaTerraCare uses open-source software components.

License notices for included components can be viewed within the app under **Open Source Licenses** or a comparable menu item.

The inclusion of open-source software does not mean that the respective authors receive the user’s app content.

---

## 15. Changes to this privacy policy

This privacy policy may be updated when:

* app functions change
* new services are introduced
* existing services are removed or reconfigured
* legal requirements change
* supervisory guidance changes

The current version will be made available at the public privacy-policy URL and, where applicable, through the app.

Material changes may additionally be communicated within the app.

---

## 16. Third-party privacy information

Further information about Google and Firebase data processing is available at:

Google Privacy Policy:
https://policies.google.com/privacy

Firebase Privacy and Security:
https://firebase.google.com/support/privacy

Firebase Terms:
https://firebase.google.com/terms

Cloud Firestore documentation:
https://firebase.google.com/docs/firestore

Google AdMob personalized and non-personalized ads:
https://support.google.com/admob/answer/7676680

Google data-transfer frameworks:
https://policies.google.com/privacy/frameworks

---

# DEUTSCH

## 1. Verantwortlicher

Verantwortlicher für die Datenverarbeitung im Zusammenhang mit dieser App:

**AquaTerraLife**
Verantwortliche Person: Nils Behr
Anschrift: **[vor Veröffentlichung ladungsfähige Anschrift ergänzen]**
Kontakt: **[aquaterralife.apps@gmail.com](mailto:aquaterralife.apps@gmail.com)**

---

## 2. Überblick

AquaTerraCare ist eine Anwendung zur Verwaltung von Aquarien, Terrarien, Pflanzenvitrinen und sonstigen Habitaten. Die App ermöglicht die Dokumentation von Habitaten, Organismen, Arten, Pflegeaufgaben, Pflegeprotokollen, Umweltparametern, Messwerten und zugehörigen Informationen.

AquaTerraCare folgt einem Offline-First-Ansatz. Die Kernfunktionen sind so ausgelegt, dass sie ohne dauerhafte Internetverbindung verwendet werden können. Die von Nutzern eingegebenen Inhalte werden zunächst überwiegend lokal auf ihrem Gerät gespeichert.

Abhängig von den verwendeten Funktionen und den Einstellungen des Nutzers kann AquaTerraCare Daten in folgender Weise verarbeiten:

* lokale Speicherung von App-Inhalten auf dem Gerät
* lokale Benachrichtigungen für Pflegeerinnerungen
* nutzergesteuerte Backups sowie Export und Import
* optionale Cloud-Synchronisation über Firebase Cloud Firestore
* technische Absturz- und Diagnosedaten über Firebase Crashlytics
* Analyse der App-Nutzung über Firebase Analytics
* werbebezogene Datenverarbeitung über Google AdMob
* Kommunikationsdaten bei Kontaktaufnahme mit dem Entwickler

Für Cloud-Synchronisation, Analyse- und Werbefunktionen kann eine Internetverbindung erforderlich sein.

---

## 3. Von der App verarbeitete Daten

### 3.1 Lokal auf dem Gerät gespeicherte Daten

AquaTerraCare kann insbesondere folgende Inhalte lokal auf dem Gerät speichern:

* Habitate, Aquarien, Terrarien, Pflanzenvitrinen und vergleichbare Einheiten
* Bezeichnungen, Typen, Beschreibungen und Notizen zu Habitaten
* Organismen sowie Tier- oder Pflanzenbestände
* Zuordnung zu Arten
* deutsche, englische und wissenschaftliche Artnamen
* benutzerdefinierte Arten
* Mengenangaben und weitere organismenbezogene Metadaten
* wiederkehrende und einmalige Pflegeaufgaben
* Fälligkeiten, Wiederholungsregeln und Erledigungsstatus
* erledigte und übersprungene Aufgaben
* Pflegeprotokolle und historische Einträge
* Definitionen von Umweltparametern
* Messwerte, etwa Temperatur, Luftfeuchtigkeit, pH-Wert oder sonstige Werte
* Messzeitpunkte und Notizen
* Benachrichtigungs- und Erinnerungseinstellungen
* Status des Onboardings
* Sprache, Darstellung und sonstige App-Einstellungen
* Metadaten zu Backups und Importen
* technische Kennungen zur Verknüpfung zusammengehöriger Datensätze

Der konkrete Umfang hängt davon ab, welche Funktionen der Nutzer verwendet. Nutzer sollten in Freitextfeldern keine unnötigen personenbezogenen oder sensiblen Angaben eintragen.

**Zweck:** Bereitstellung der gewünschten App-Funktionen, lokale Organisation von Habitat- und Pflegedaten, Darstellung von Historien und Messwerten, Planung von Erinnerungen sowie Speicherung der App-Einstellungen.

**Rechtsgrundlage für Nutzer in der EU bzw. im EWR:** Art. 6 Abs. 1 lit. b DSGVO, soweit die Verarbeitung zur Bereitstellung der vom Nutzer gewünschten Funktionen erforderlich ist; im Übrigen Art. 6 Abs. 1 lit. f DSGVO auf Grundlage des berechtigten Interesses an einer stabilen, funktionsfähigen und nutzerfreundlichen Anwendung.

Daten, die ausschließlich in der lokalen App-Datenbank gespeichert werden, werden nicht automatisch an den Entwickler übermittelt.

---

### 3.2 Lokale Benachrichtigungen und Erinnerungen

AquaTerraCare kann lokale Benachrichtigungen einplanen, um Nutzer an bevorstehende oder fällige Pflegeaufgaben zu erinnern.

Hierfür können lokal insbesondere verarbeitet werden:

* Titel der Aufgabe
* Fälligkeitsdatum und Uhrzeit
* Aktivierungsstatus der Erinnerung
* technische Benachrichtigungskennung
* Angaben zur Berechnung wiederkehrender Erinnerungen

Die Planung der Benachrichtigungen erfolgt grundsätzlich lokal auf dem Gerät. Die App kann hierzu die Berechtigung des Betriebssystems zum Anzeigen von Benachrichtigungen anfordern.

Der Nutzer kann einzelne Erinnerungen deaktivieren, Benachrichtigungen – soweit vorgesehen – global in der App ausschalten oder die Berechtigung in den Geräteeinstellungen widerrufen.

**Zweck:** Erinnerung an die vom Nutzer angelegten Pflegeaufgaben.

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO.

---

### 3.3 Backup, Export und Import

AquaTerraCare ermöglicht es Nutzern, App-Daten in eine Sicherungsdatei zu exportieren und durch Import einer kompatiblen Sicherungsdatei wiederherzustellen.

Backups können abhängig von den gespeicherten Inhalten insbesondere enthalten:

* Habitate
* Organismen
* Arten und benutzerdefinierte Arten
* Pflegeaufgaben und Aufgabenerledigungen
* Pflegeprotokolle
* Parameterdefinitionen und Messwerte
* App-Einstellungen
* Erinnerungseinstellungen
* technische Kennungen und Beziehungen zwischen Datensätzen

Sicherungsdateien werden grundsätzlich in einem strukturierten JSON-Format erstellt.

Der Nutzer entscheidet selbst:

* ob ein Backup erstellt wird
* wo das Backup gespeichert wird
* ob es mit einer anderen App oder einem anderen Dienst geteilt wird
* ob und wann es wieder importiert wird

Wählt der Nutzer einen externen Speicherort, Dateimanager, E-Mail-Dienst, Cloud-Speicher oder Freigabedienst aus, kann dieser Drittanbieter die Sicherungsdatei nach seiner eigenen Datenschutzerklärung verarbeiten. AquaTerraCare hat auf diese externe Verarbeitung keinen Einfluss.

Backups können detaillierte Angaben zu Habitaten, Tieren, Pflanzen und Pflegeroutinen enthalten. Nutzer sollten Sicherungsdateien daher sicher speichern und übertragen.

**Zweck:** Datenübertragbarkeit, manuelle Datensicherung, Gerätewechsel und Wiederherstellung von App-Daten.

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO.

---

### 3.4 Optionale Cloud-Synchronisation

AquaTerraCare stellt eine optionale Cloud-Synchronisation über **Firebase Cloud Firestore**, einen Dienst von Google, bereit bzw. bereitet diese technisch vor.

Die Cloud-Synchronisation ist für die grundlegende Offline-Nutzung von AquaTerraCare nicht erforderlich. Sie wird nur verwendet, wenn der Nutzer die entsprechende Synchronisationsfunktion auswählt oder aktiviert.

Je nach umgesetzt­em Synchronisationsumfang können insbesondere folgende Informationen an Cloud Firestore übermittelt und dort gespeichert werden:

* Habitate und zugehörige Metadaten
* Organismen und Bestände
* Arten und benutzerdefinierte Arten
* Pflegeaufgaben
* Historie erledigter und übersprungener Aufgaben
* Pflegeprotokolle
* Umweltparameter
* Messwerte
* App- und Synchronisationseinstellungen
* Zeitstempel
* Datensatzkennungen
* Informationen zur Zuordnung synchronisierter Daten zum Nutzer oder zur Installation
* technische Synchronisationsmetadaten

Soweit Nutzerkonten oder Firebase Authentication eingesetzt werden, können abhängig von der gewählten Anmeldemethode zusätzlich folgende Daten verarbeitet werden:

* Nutzerkennung
* E-Mail-Adresse
* verwendeter Authentifizierungsanbieter
* Authentifizierungstoken oder technische Authentifizierungsmetadaten
* Zeitpunkte der Kontoerstellung und Anmeldung

Synchronisierte Habitat-, Organismen- oder Pflegedaten sollen nicht für Werbezwecke verwendet werden.

**Zwecke:**

* Synchronisation von App-Daten zwischen Geräten
* Wiederherstellung synchronisierter Daten
* Bereitstellung eines nutzergesteuerten Cloud-Speichers
* Wahrung der Datenkonsistenz zwischen autorisierten Geräten

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO, da die Synchronisation auf Wunsch des Nutzers erfolgt. Soweit eine optionale Verarbeitung auf einer gesonderten Einwilligungsentscheidung beruht, kann zusätzlich Art. 6 Abs. 1 lit. a DSGVO einschlägig sein.

Nutzer können die Cloud-Synchronisation in der App deaktivieren, soweit diese Funktion bereitsteht. Die Deaktivierung der Synchronisation führt nicht zwingend zur Löschung bereits in der Cloud gespeicherter Daten. Hierfür kann eine gesonderte Löschfunktion oder ein Löschersuchen erforderlich sein.

Vor Aktivierung der Cloud-Synchronisation sollen Nutzer innerhalb der App über die betroffenen Daten und die verfügbaren Steuerungsmöglichkeiten informiert werden.

---

### 3.5 Firebase Crashlytics

AquaTerraCare verwendet **Firebase Crashlytics**, einen Absturzanalysedienst von Google, um Abstürze, technische Fehler und Stabilitätsprobleme zu erkennen.

Crashlytics kann insbesondere folgende Informationen verarbeiten:

* Installations- oder Instanzkennung
* Gerätemodell
* Betriebssystem und Betriebssystemversion
* App-Version und Build-Nummer
* Zeitpunkt eines Absturzes oder Fehlers
* Absturz-Stacktraces
* technische Protokolle
* Speicher- und Ausführungszustand
* Informationen über den App-Zustand zum Fehlerzeitpunkt
* Diagnose- und Leistungsdaten

AquaTerraCare übermittelt Inhalte von Habitaten, Organismen, Pflegeprotokollen, Messwerten oder Backups nicht gezielt als Bestandteil von Crashlytics-Berichten. Technische Fehlermeldungen können im Einzelfall jedoch begrenzte Kontextinformationen enthalten, wenn diese Bestandteil einer automatisch erzeugten Fehlermeldung geworden sind. Die App soll daher nutzergenerierte Inhalte nicht in Diagnoseprotokolle aufnehmen.

**Zweck:** Erkennung, Analyse und Behebung von Abstürzen und technischen Fehlern, Aufrechterhaltung der Sicherheit sowie Verbesserung der Stabilität.

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. f DSGVO auf Grundlage des berechtigten Interesses an einer sicheren, stabilen und technisch zuverlässigen Anwendung. Soweit für die Speicherung oder den Zugriff auf Informationen auf dem Gerät oder für die betreffende Verarbeitung eine Einwilligung rechtlich erforderlich ist, erfolgt die Aktivierung von Crashlytics auf Grundlage von Art. 6 Abs. 1 lit. a DSGVO und der einschlägigen telekommunikations- bzw. ePrivacy-rechtlichen Bestimmungen.

Die Erfassung durch Crashlytics kann über Datenschutz-Einstellungen der App deaktiviert oder eingeschränkt werden, soweit eine solche Steuerungsmöglichkeit vorgesehen ist.

---

### 3.6 Firebase Analytics

AquaTerraCare verwendet oder kann **Firebase Analytics**, einen Analysedienst von Google, verwenden.

Abhängig von technischer Konfiguration, Einwilligungsstatus und aktivierten Funktionen kann Firebase Analytics insbesondere folgende Informationen verarbeiten:

* App-Instanz- oder Installationskennung
* Geräte- und Betriebssysteminformationen
* App-Version
* Sprache und allgemeine Regionsinformationen
* App-Starts und Sitzungsinformationen
* aufgerufene Ansichten
* Interaktionen mit App-Funktionen
* technische Ereignisse
* ungefähre Nutzungsdauer
* Diagnose- und Leistungsinformationen
* Werbekennungen, soweit verfügbar und rechtlich zulässig

AquaTerraCare soll vom Nutzer eingegebene Habitatnamen, Tiernamen, Notizen, Inhalte von Pflegeprotokollen, Messwerte oder Backup-Inhalte nicht gezielt als Analytics-Ereignisparameter übermitteln.

Analytics wird nur nach Einholung einer Einwilligung eingesetzt, soweit eine Einwilligung rechtlich erforderlich ist. Nutzer können eine Einwilligung mit Wirkung für die Zukunft über die Datenschutz-Einstellungen der App widerrufen, soweit diese Möglichkeit bereitsteht. Die Rechtmäßigkeit der bis zum Widerruf erfolgten Verarbeitung bleibt unberührt.

**Zwecke:**

* Verständnis der allgemeinen App-Nutzung
* Erkennung häufig oder selten verwendeter Funktionen
* Verbesserung der Benutzerfreundlichkeit
* Erkennung technischer Probleme
* Unterstützung der Produktentwicklung

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. a DSGVO, soweit eine Einwilligung erforderlich ist oder eingeholt wird. Streng für Sicherheit oder technischen Betrieb erforderliche Verarbeitungen können in eng begrenzten Fällen auf Art. 6 Abs. 1 lit. f DSGVO gestützt werden, sofern die gesetzlichen Voraussetzungen erfüllt sind.

---

### 3.7 Werbung über Google AdMob

AquaTerraCare verwendet oder kann **Google AdMob**, einen Werbedienst von Google, verwenden, um Anzeigen darzustellen und die App zu finanzieren.

Abhängig vom Aufenthaltsort, den Einwilligungsentscheidungen, den Geräteeinstellungen und den technischen Systemen von Google können personalisierte, nicht personalisierte oder eingeschränkte Anzeigen angezeigt werden.

Im Zusammenhang mit Werbung können Google und beteiligte Werbepartner insbesondere folgende Informationen verarbeiten:

* Werbekennung
* App-Instanz- oder Gerätekennungen
* IP-Adresse
* aus der IP-Adresse abgeleiteter ungefährer Standort
* Hersteller und Modell des Geräts
* Betriebssystem
* App-Version
* Sprache
* Werbeeinwilligungsstatus
* Interaktionen mit Anzeigen
* Anzeigenaufrufe und Klicks
* Diagnose- und Leistungsinformationen
* Informationen zur Betrugsprävention, Häufigkeitsbegrenzung und aggregierten Berichterstattung

Personalisierte Werbung kann Informationen über Interessen, frühere Interaktionen oder andere Daten verwenden, die Google und beteiligten Werbeanbietern zur Verfügung stehen.

Nicht personalisierte Werbung beruht nicht auf einem Nutzerprofil für zielgerichtete Werbung. Gleichwohl können Kennungen oder sonstige technische Angaben weiterhin etwa zur Häufigkeitsbegrenzung, Betrugsprävention, Auslieferung von Anzeigen und aggregierten Berichterstattung verarbeitet werden.

Soweit rechtlich erforderlich, holt AquaTerraCare eine Einwilligung ein, bevor Werbedienste geladen oder Werbekennungen verwendet werden. Wird keine Einwilligung erteilt, können Anzeigen abhängig von der rechtlich und technisch verfügbaren Konfiguration eingeschränkt, nicht personalisiert oder nicht verfügbar sein.

**Zwecke:**

* Finanzierung und Monetarisierung der App
* Auslieferung von Werbung
* Messung der Anzeigenleistung
* Begrenzung wiederholt angezeigter Werbung
* Verhinderung ungültiger Zugriffe und Betrug
* Einhaltung werbe- und einwilligungsbezogener Anforderungen

**Rechtsgrundlage:**

* personalisierte Werbung: Art. 6 Abs. 1 lit. a DSGVO
* Zugriff auf oder Speicherung von Informationen auf dem Gerät: Einwilligung nach den einschlägigen telekommunikations- bzw. ePrivacy-rechtlichen Bestimmungen, soweit erforderlich
* nicht personalisierte oder eingeschränkte Werbung: Art. 6 Abs. 1 lit. a DSGVO, soweit für eingesetzte Kennungen oder Technologien eine Einwilligung erforderlich ist; andernfalls Art. 6 Abs. 1 lit. f DSGVO nur, soweit dies rechtlich zulässig ist

Nutzer können ihre Datenschutz- und Werbeentscheidungen gegebenenfalls in den App-Einstellungen oder über die in der App bereitgestellte Einwilligungsoberfläche prüfen oder ändern.

---

### 3.8 Kontaktaufnahme mit dem Entwickler

Wenn Nutzer den Entwickler per E-Mail kontaktieren, werden die in der Kommunikation übermittelten Daten verarbeitet. Hierzu können gehören:

* E-Mail-Adresse
* Name
* Datum und Uhrzeit der Nachricht
* Betreff
* Nachrichteninhalt
* Anhänge
* freiwillig für Supportzwecke übermittelte technische Informationen

Nutzer sollten in Supportanfragen keine unnötigen sensiblen Daten übermitteln.

**Zweck:** Beantwortung von Fragen, Bearbeitung von Supportanfragen und Fehlermeldungen sowie Kommunikation mit Nutzern.

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO, soweit die Kommunikation die App-Nutzung oder ein Vertragsverhältnis betrifft; im Übrigen Art. 6 Abs. 1 lit. f DSGVO auf Grundlage des berechtigten Interesses an der Bearbeitung von Anfragen und Bereitstellung von Support.

---

## 4. Empfänger von Daten

Abhängig von den verwendeten Funktionen können personenbezogene Daten an folgende Empfänger oder Empfängerkategorien übermittelt werden:

* **Google Ireland Limited und verbundene Google-Unternehmen** im Zusammenhang mit Firebase, Cloud Firestore, Firebase Authentication, Firebase Analytics, Firebase Crashlytics und Google AdMob
* an Google AdMob beteiligte Werbepartner, abhängig von den Einwilligungsentscheidungen und der Werbekonfiguration
* Anbieter des Betriebssystems und des App-Stores, insbesondere Google Play
* für Kommunikation und Veröffentlichung der Datenschutzerklärung eingesetzte E-Mail- und Hostinganbieter
* vom Nutzer ausgewählte Speicher-, Freigabe- oder Cloud-Anbieter für exportierte Backup-Dateien
* technische Dienstleister, die mit Betrieb, Wartung oder Support der App beauftragt werden
* öffentliche Stellen oder Gerichte, soweit eine Offenlegung gesetzlich vorgeschrieben ist

Lokal gespeicherte Habitat-, Organismen-, Pflege- und Messdaten werden nicht allein deshalb an den Entwickler übermittelt, weil sie in der lokalen Datenbank gespeichert sind.

---

## 5. Drittlandübermittlungen

Google und andere Dienstleister können Daten außerhalb der Europäischen Union oder des Europäischen Wirtschaftsraums verarbeiten, insbesondere in den USA oder anderen Staaten, deren Datenschutzniveau von dem der EU bzw. des EWR abweichen kann.

Soweit erforderlich, erfolgen Übermittlungen auf Grundlage geeigneter Garantien nach Kapitel V DSGVO, insbesondere:

* eines Angemessenheitsbeschlusses der Europäischen Kommission
* der Teilnahme an einem anerkannten Datenschutzrahmen
* von Standardvertragsklauseln
* ergänzender technischer und organisatorischer Schutzmaßnahmen

Weitere Informationen enthalten die Datenschutz- und Datenübermittlungsinformationen von Google.

---

## 6. Speicherdauer

### 6.1 Lokale App-Daten

Lokal gespeicherte App-Daten verbleiben auf dem Gerät, bis:

* der Nutzer einzelne Datensätze löscht
* der Nutzer die App-Daten zurücksetzt oder löscht
* die App deinstalliert wird
* ein Import die vorhandene lokale Datenbank ersetzt
* das Betriebssystem die App-Daten löscht

### 6.2 Backup-Dateien

Exportierte Backup-Dateien bleiben gespeichert, bis der Nutzer sie am gewählten Speicherort oder bei dem gewählten Dienst löscht. AquaTerraCare hat keine automatische Kontrolle über vom Nutzer erstellte oder weitergegebene Kopien.

### 6.3 Cloud-synchronisierte Daten

Cloud-synchronisierte Daten werden gespeichert, bis:

* der Nutzer die betreffenden Daten löscht
* der Nutzer eine verfügbare Funktion zur Löschung der Cloud-Daten verwendet
* der Nutzer – soweit anwendbar – die Löschung verlangt
* das betreffende Firebase-Projekt oder Nutzerkonto gelöscht wird
* eine weitere Speicherung gesetzlich erforderlich ist

Die bloße Deaktivierung der Synchronisation führt nicht zwingend zur Löschung bereits in der Cloud gespeicherter Daten.

### 6.4 Analytics, Crashlytics und AdMob

Über Firebase Analytics, Firebase Crashlytics und Google AdMob verarbeitete Daten werden entsprechend den konfigurierten Aufbewahrungseinstellungen, den einschlägigen Google-Nutzungsbedingungen und den Datenschutzbestimmungen von Google gespeichert.

### 6.5 Support-Kommunikation

Supportanfragen werden nur so lange gespeichert, wie dies zur Bearbeitung der Anfrage, Dokumentation der Kommunikation, Geltendmachung oder Abwehr rechtlicher Ansprüche und Erfüllung gesetzlicher Aufbewahrungspflichten erforderlich ist.

---

## 7. Einwilligung und Widerruf

Soweit eine Verarbeitung auf einer Einwilligung beruht, können Nutzer ihre Einwilligung jederzeit mit Wirkung für die Zukunft widerrufen.

Je nach umgesetzter App-Version können Einwilligungs- oder Aktivierungseinstellungen insbesondere verfügbar sein für:

* Firebase Analytics
* Firebase Crashlytics
* personalisierte oder nicht personalisierte Werbung
* beteiligte Werbepartner
* Cloud-Synchronisation

Der Widerruf berührt nicht die Rechtmäßigkeit der bis zum Widerruf erfolgten Verarbeitung.

Die Deaktivierung einer Funktion kann die Verfügbarkeit der damit verbundenen Funktionen einschränken. Beispielsweise:

* verhindert die Deaktivierung von Benachrichtigungen Pflegeerinnerungen
* verhindert die Deaktivierung der Cloud-Synchronisation die Synchronisation zwischen Geräten
* kann die Ablehnung von Werbeeinwilligungen zu eingeschränkter oder ausbleibender Werbung führen
* verhindert die Ablehnung von Analytics nicht die Nutzung der grundlegenden Offline-Funktionen

---

## 8. Rechte nach der DSGVO

Soweit die DSGVO anwendbar ist, können Nutzer insbesondere folgende Rechte haben:

* Recht auf Auskunft nach Art. 15 DSGVO
* Recht auf Berichtigung nach Art. 16 DSGVO
* Recht auf Löschung nach Art. 17 DSGVO
* Recht auf Einschränkung der Verarbeitung nach Art. 18 DSGVO
* Recht auf Datenübertragbarkeit nach Art. 20 DSGVO
* Recht auf Widerspruch nach Art. 21 DSGVO
* Recht auf Widerruf einer Einwilligung nach Art. 7 Abs. 3 DSGVO
* Recht auf Beschwerde bei einer Datenschutzaufsichtsbehörde nach Art. 77 DSGVO

Soweit Daten ausschließlich auf dem Gerät des Nutzers gespeichert werden und für den Entwickler nicht zugänglich sind, kann der Entwickler diese lokalen Daten technisch möglicherweise nicht einsehen, berichtigen oder löschen. Der Nutzer kann diese Daten unmittelbar in der App, über die Backup-Funktionen, durch Löschen der App-Daten oder durch Deinstallation der App verwalten.

Anfragen zu Cloud-Daten, Support-Kommunikation oder sonstigen für den Entwickler zugänglichen Daten können an folgende Adresse gerichtet werden:

**[aquaterralife.apps@gmail.com](mailto:aquaterralife.apps@gmail.com)**

Nutzer haben außerdem das Recht, sich bei einer zuständigen Datenschutzaufsichtsbehörde zu beschweren. Sie können sich insbesondere an die Aufsichtsbehörde ihres gewöhnlichen Aufenthaltsortes, ihres Arbeitsplatzes oder des Ortes des mutmaßlichen Verstoßes wenden.

---

## 9. Widerspruchsrecht

Soweit eine Verarbeitung auf Art. 6 Abs. 1 lit. f DSGVO beruht, haben Nutzer das Recht, aus Gründen, die sich aus ihrer besonderen Situation ergeben, der Verarbeitung zu widersprechen.

Werden Daten für Zwecke der Direktwerbung verarbeitet, besteht jederzeit ein Widerspruchsrecht, ohne dass besondere Gründe angegeben werden müssen.

---

## 10. Pflicht zur Bereitstellung von Daten

Eine gesetzliche Pflicht zur Bereitstellung personenbezogener Daten besteht grundsätzlich nicht.

Allerdings gilt:

* lokale App-Inhalte sind erforderlich, wenn die betreffenden Organisationsfunktionen genutzt werden sollen
* eine Benachrichtigungsberechtigung ist erforderlich, um Pflegeerinnerungen anzuzeigen
* eine Internetverbindung und die erforderlichen Synchronisationsinformationen sind für die Cloud-Synchronisation erforderlich
* technische Angaben können für Crashlytics-, Analytics- oder Werbefunktionen erforderlich sein
* eine E-Mail-Adresse und der Nachrichteninhalt sind erforderlich, wenn der Nutzer den Support kontaktiert

Die grundlegenden Offline-Funktionen sollen auch ohne Aktivierung der optionalen Cloud-Synchronisation, von Analytics oder personalisierter Werbung verfügbar bleiben, soweit dem keine technischen oder rechtlichen Einschränkungen entgegenstehen.

---

## 11. Automatisierte Entscheidungsfindung und Profiling

AquaTerraCare selbst verwendet keine automatisierte Entscheidungsfindung, die gegenüber Nutzern rechtliche Wirkung entfaltet oder sie in ähnlicher Weise erheblich beeinträchtigt.

Google AdMob und beteiligte Werbeanbieter können bei erteilter Einwilligung Profiling zur Bereitstellung personalisierter Werbung einsetzen. Einzelheiten richten sich nach den jeweiligen Anbietern und den Einwilligungsentscheidungen des Nutzers.

---

## 12. Kinder

AquaTerraCare richtet sich nicht gezielt an Kinder in Situationen, in denen nach dem anwendbaren Recht eine elterliche Einwilligung oder ein besonderer Schutz erforderlich wäre.

Die App ist als Organisationstool für verantwortliche Halter von Aquarien, Terrarien, Pflanzen und Tieren vorgesehen. Sind Eltern oder Sorgeberechtigte der Ansicht, dass personenbezogene Daten eines Kindes unrechtmäßig verarbeitet wurden, können sie den Entwickler kontaktieren.

---

## 13. Datensicherheit

AquaTerraCare verwendet technische und organisatorische Maßnahmen, die dazu dienen, Daten vor unberechtigtem Zugriff, Verlust, Veränderung oder Offenlegung zu schützen.

Hierzu können insbesondere gehören:

* lokale App-Isolation durch das Betriebssystem
* verschlüsselte Netzwerkübertragung
* Firebase Security Rules
* Authentifizierungs- und Autorisierungskontrollen für Cloud-Daten
* transaktionsbasierte Wiederherstellung von Backups
* Trennung lokaler App-Inhalte von Analyse- und Absturzereignissen
* Datenminimierung
* nutzergesteuerte Synchronisations- und Exportfunktionen

Keine Form elektronischer Speicherung oder Übertragung kann eine absolute Sicherheit gewährleisten.

Nutzer sind selbst für den Schutz folgender Komponenten verantwortlich:

* ihres Geräts
* der Zugangsdaten zum Gerät
* der Zugangsdaten zu einem Cloud- oder Authentifizierungskonto
* exportierter Backup-Dateien
* an Drittanbieter weitergegebener Dateien

---

## 14. Open-Source-Software

AquaTerraCare verwendet verschiedene Open-Source-Komponenten.

Lizenzhinweise zu den eingebundenen Komponenten können innerhalb der App unter **Open Source Lizenzen** oder einem vergleichbaren Menüpunkt eingesehen werden.

Die Verwendung von Open-Source-Software bedeutet nicht, dass deren Urheber Zugriff auf die App-Inhalte des Nutzers erhalten.

---

## 15. Änderungen dieser Datenschutzerklärung

Diese Datenschutzerklärung kann angepasst werden, wenn:

* sich App-Funktionen ändern
* neue Dienste eingeführt werden
* bestehende Dienste entfernt oder anders konfiguriert werden
* sich gesetzliche Anforderungen ändern
* sich Vorgaben von Aufsichtsbehörden ändern

Die jeweils aktuelle Version wird unter der öffentlichen Datenschutz-URL und – soweit vorgesehen – innerhalb der App bereitgestellt.

Über wesentliche Änderungen kann zusätzlich innerhalb der App informiert werden.

---

## 16. Informationen zu Drittanbietern

Weitere Informationen zur Datenverarbeitung durch Google und Firebase sind verfügbar unter:

Google-Datenschutzerklärung:
https://policies.google.com/privacy?hl=de

Datenschutz und Sicherheit bei Firebase:
https://firebase.google.com/support/privacy

Firebase-Nutzungsbedingungen:
https://firebase.google.com/terms

Dokumentation zu Cloud Firestore:
https://firebase.google.com/docs/firestore

Informationen zu personalisierten und nicht personalisierten AdMob-Anzeigen:
https://support.google.com/admob/answer/7676680?hl=de

Informationen zu den Datenübermittlungsrahmen von Google:
https://policies.google.com/privacy/frameworks?hl=de
