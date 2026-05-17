# Datenschutzerklärung Dispocall

*Stand: Mai 2026*

Diese Datenschutzerklärung informiert Sie über die Verarbeitung personenbezogener Daten bei der Nutzung der Software-as-a-Service-Plattform **Dispocall** einschließlich des optionalen Telefon-KI-Moduls **Voice AI**.

Die Dispocall App wird als Dienstleistung an Taxi-Unternehmen bereitgestellt. Je nachdem, in welcher Rolle Sie mit der Plattform in Berührung kommen, ist eine andere Stelle datenschutzrechtlich verantwortlich:

- Als **Firmeninhaber, Disponent oder Fahrer** eines Taxi-Unternehmens, das die Dispocall App einsetzt: **Ihr Arbeitgeber bzw. das Taxi-Unternehmen** ist der Verantwortliche für die Verarbeitung Ihrer Daten im Sinne von Art. 4 Nr. 7 DSGVO. Der Betreiber der Plattform handelt als sein Auftragsverarbeiter (siehe Abschnitt 8).
- Als **Endkunde / Fahrgast**, der eines der angeschlossenen Taxi-Unternehmen telefonisch kontaktiert oder eine Fahrt bestellt: **Das Taxi-Unternehmen**, bei dem Sie anrufen, ist Verantwortlicher.
- Für den **Betrieb der Plattform selbst** (z.B. Benutzerregistrierung von Taxi-Unternehmen, Plattform-weite Logs): Der Betreiber der Dispocall App ist Verantwortlicher.

---

## 1. Verantwortliche Stelle für den Plattformbetrieb

**Robin Eckel**

**Am Berg 2, 35066 Frankenberg**

**E-Mail: Support@dispocall.de**

Ein Datenschutzbeauftragter ist nicht bestellt, weil die gesetzlichen Schwellenwerte gemäß § 38 BDSG / Art. 37 DSGVO nicht erreicht werden. Anfragen richten Sie bitte an die oben genannte E-Mail-Adresse.

---

## 2. Welche personenbezogenen Daten wir verarbeiten

### 2.1 Mitarbeiter des Taxi-Unternehmens (Fahrer, Disponenten)

| Datenkategorie | Zweck |
|---|---|
| Vor- und Nachname, E-Mail, Passwort (Hash) | Authentifizierung, Rollenvergabe |
| GPS-Koordinaten während aktiver Schicht | Disposition und Auftragszuweisung |
| Login-/Logout-Zeitpunkte, Pausenzeiten | Arbeitszeiterfassung (§ 16 Abs. 2 ArbZG) |
| Fahrzeugkennzeichen, Kilometerstand | Schichtdokumentation, Fahrzeugverwaltung |
| Schichtumsatz (Summe der Fahrpreise) | Einnahmenachweis (§ 147 AO) |

### 2.2 Fahrgäste / Anrufer

| Datenkategorie | Zweck |
|---|---|
| Rufnummer (Carrier-Caller-ID oder vom Anrufer genannt) | Rückruf bei Problemen, Wiedererkennung bei Folgeanrufen (nur mit Einwilligung) |
| Name (sofern vom Anrufer/Fahrgast genannt) | Zuordnung des Auftrags, persönliche Ansprache |
| Abhol- und Zieladresse | Durchführung des Fahrtauftrags |
| Fahrpreis, Fahrttyp | Abrechnung, Buchhaltung |
| Stimme während des Voice-AI-Anrufs | Ausschließlich flüchtige Verarbeitung im Arbeitsspeicher — **keine Aufzeichnung**, keine Speicherung |
| Text-Antworten der Voice AI an Sie | Werden zur Sprachsynthese ggf. an einen EU-basierten Cloud-TTS-Dienst übermittelt (Google Cloud Text-to-Speech, Chirp 3 HD, EU-Multi-Region). Eingangstext und Ausgangsaudio werden dort ausschließlich in-memory während der ~200 ms Render-Zeit verarbeitet, anschließend verworfen. Keine Persistierung, keine Verwendung zum Training. Alternativ erfolgt die Sprachsynthese lokal auf der Server-Infrastruktur des Anbieters. |

### 2.3 Firmeninhaber des Taxi-Unternehmens

| Datenkategorie | Zweck |
|---|---|
| Firmen-E-Mail, Firmenname, Passwort-Hash | Authentifizierung des Plattform-Zugangs |
| Firmensitz-PLZ | Voice-AI-Erkennung gleichlautender Straßennamen in Nachbarorten |
| Öffnungszeiten / Voice-AI-Betriebszeiten | Konfiguration der Erreichbarkeit |

---

## 3. Rechtsgrundlagen

| Verarbeitungszweck | Rechtsgrundlage |
|---|---|
| Mitarbeiterdaten zur Durchführung des Arbeitsverhältnisses | Art. 6 Abs. 1 lit. b DSGVO |
| GPS-Ortung während Schicht | Art. 6 Abs. 1 lit. f DSGVO (berechtigtes Interesse an effizienter Disposition) — Betroffene werden vor der ersten Nutzung schriftlich informiert |
| Schichtdaten (Arbeitszeit) | Art. 6 Abs. 1 lit. c DSGVO + ArbZG § 16 Abs. 2 |
| Fahrauftrag und Fahrpreis | Art. 6 Abs. 1 lit. b DSGVO (Vertragsdurchführung) + Art. 6 Abs. 1 lit. c DSGVO (PBefG § 49, BOKraft § 26, AO § 147) |
| Voice-AI-Gesprächsannahme | Art. 6 Abs. 1 lit. b DSGVO (Bestellaufnahme) |
| **Kundenkartei (wiederkehrende Anrufer)** | Art. 6 Abs. 1 lit. a DSGVO — **Einwilligung**, die am Ende des ersten Anrufs ausdrücklich eingeholt wird |
| Bug-Reports | Art. 6 Abs. 1 lit. f DSGVO (Produktverbesserung) |

---

## 4. Speicherdauer

Wir verarbeiten Ihre Daten nur so lange, wie es für die genannten Zwecke erforderlich ist oder gesetzliche Aufbewahrungspflichten bestehen. Für den gesetzlich zwingenden Teil gilt ein **Zwei-Stufen-Modell**:

- **Stufe 1 — Teil-Anonymisierung:** Nach Ablauf der personenbezogenen Aufbewahrungsfrist werden Namen, Telefonnummern, detaillierte Adressen und Kommentare durch Platzhalter ersetzt. Betrags- und Zeitangaben bleiben als steuerliche Nachweise erhalten.
- **Stufe 2 — Vollständige Löschung:** Nach Ablauf der steuerrechtlichen Aufbewahrungsfrist wird der Datensatz vollständig entfernt.

| Datenkategorie | Stufe 1 | Stufe 2 |
|---|---|---|
| Fahraufträge und Fahrten (inkl. Fahrpreis) | 1 Jahr | 8 Jahre |
| Schicht- und Arbeitszeitdaten (inkl. Schichtumsatz) | 2 Jahre | 10 Jahre |
| Kundenkartei | keine Teil-Anonymisierung — Einwilligungswiderruf oder 12 Monate ab letztem Kontakt → vollständige Löschung | |
| GPS-Standortdaten | nur während aktiver Schicht im Arbeitsspeicher — keine Speicherung nach Schichtende | |
| Audio-Aufnahmen / Sprach-zu-Text-Transkripte | **keine Speicherung** — sofortige Verwerfung nach Ende des Anrufs | |

---

## 5. Empfänger und Datenweitergabe

Ihre Daten werden grundsätzlich nur innerhalb des Taxi-Unternehmens verarbeitet, das Sie beauftragen bzw. bei dem Sie beschäftigt sind. Eine Weitergabe an Dritte erfolgt nur in folgendem Umfang:

| Empfänger | Zweck | Rechtsgrundlage |
|---|---|---|
| **Google Ireland Ltd.** (Firebase, Cloud KMS, Cloud Text-to-Speech) | (a) Hosting der Datenbank und Schlüsselverwaltung — Primärregion europe-west3 (Frankfurt); (b) Sprachsynthese der Voice-AI-Antworten via Cloud Text-to-Speech „Chirp 3 HD" — EU-Multi-Region (Frankfurt/Eemshaven/London). Eingangstext und Ausgangsaudio werden bei Google nur in-memory während der Render-Zeit verarbeitet, nicht persistiert und nicht zu Trainings- oder Service-Verbesserungszwecken genutzt. Alternativ erfolgt die Sprachsynthese lokal auf Anbieter-Servern. | Auftragsverarbeitung gemäß Art. 28 DSGVO; Cloud Data Processing Addendum mit Google akzeptiert |
| **Mistral AI SAS** (Mistral LLM) | Echtzeit-Textverarbeitung während eines Anrufs (alternativ zur lokalen LLM-Inferenz) | Auftragsverarbeitung; Sitz in der EU (Paris), **keine** Drittlandübermittlung; kein Training mit übermittelten Daten. Datenschutz: https://mistral.ai/terms#privacy-policy · AGB: https://mistral.ai/terms |
| **Easybell GmbH** | SIP-Telefonie-Provider (Inbound-Rufnummer der Voice AI) | TK-Dienstleister, DSGVO-konform, Deutschland |
| **Sendinblue SAS** („Brevo", Paris/Frankreich) | Versand transaktionaler E-Mails (Bug-Report-Bestätigungen, Account-Lösch-Anträge, Daten-Export-Benachrichtigungen). Keine Marketing-E-Mails, kein Newsletter-Versand, keine Verwendung der übermittelten Empfängerdaten zu eigenen Zwecken oder zum Training. | Auftragsverarbeitung gemäß Art. 28 DSGVO; Sitz in der EU, **keine** Drittlandübermittlung; Datenschutz: https://www.brevo.com/legal/privacypolicy/ |

---

## 6. Drittlandübermittlung

- **Google Cloud (Datenhaltung):** Primäre Datenhaltung in europe-west3 (Deutschland). Ausschließlich als Sekundärbackup ist eine Übermittlung in das EU-Rechenzentrum-Netz möglich. Keine Ausleitung in Nicht-EU-Länder.
- **LLM-Betrieb (lokal oder Mistral-EU):** Die Voice AI nutzt zur Sprachverarbeitung wahlweise ein lokales LLM auf der Infrastruktur des Betreibers in Deutschland oder die EU-API von Mistral AI SAS in Paris (Frankreich). **In beiden Fällen findet keine Drittlandübermittlung statt** — die Verarbeitung bleibt vollständig in der EU. Mistral verwendet übermittelte Daten gemäß seinen Nutzungsbedingungen für zahlende Kunden **nicht** zum Training.
- **TTS-Betrieb (lokal oder Google-EU):** Die Voice AI nutzt zur Sprach-Ausgabe (Synthese der gesprochenen Antworten) wahlweise einen lokalen TTS-Renderer auf der Infrastruktur des Betreibers in Deutschland oder die EU-Multi-Region-Variante von Google Cloud Text-to-Speech (Modell „Chirp 3 HD"). Der EU-Multi-Region-Endpunkt von Google routet ausschließlich auf Rechenzentren in der Europäischen Union (Frankfurt, Eemshaven oder London). **In beiden Fällen findet keine Drittlandübermittlung statt** — die Verarbeitung bleibt vollständig in der EU. Google verarbeitet die übermittelten Antwort-Texte und das gerenderte Audio gemäß Cloud Data Processing Addendum ausschließlich in-memory während der Render-Zeit (~200 ms) und persistiert sie weder zu Logging- noch zu Trainings- oder Service-Verbesserungszwecken.
- **Transaktionaler E-Mail-Versand (Brevo / Sendinblue SAS):** Wenn der Betreiber Ihnen automatisierte E-Mails sendet (z. B. Bestätigung eines Lösch-Antrags oder Bereitstellung eines Datenexport-Links), läuft der Versand über die Plattform der Sendinblue SAS (Markenname „Brevo") mit Sitz in Paris, Frankreich. Übermittelt werden lediglich die zur Mailzustellung nötigen Daten (Ihre Mail-Adresse, Betreff, Mailinhalt). Brevo betreibt seine Infrastruktur ausschließlich in der EU; **eine Drittlandübermittlung findet nicht statt**. Brevo verwendet diese Daten nicht zu eigenen Marketing- oder Profilingzwecken.
- **Allgemeiner Hinweis:** Eine Verarbeitung über LLM-, TTS- oder E-Mail-Anbieter mit Sitz außerhalb der EU (z. B. USA) ist im aktuellen Vertragsstand nicht vorgesehen; eine etwaige spätere Erweiterung würde mit angemessener Vorlaufzeit angekündigt und unterläge den Vorgaben der Art. 44 ff. DSGVO.

---

## 7. Ihre Rechte als betroffene Person

Sie haben uns bzw. dem jeweils verantwortlichen Taxi-Unternehmen gegenüber folgende Rechte hinsichtlich der Sie betreffenden personenbezogenen Daten:

- **Auskunft** (Art. 15 DSGVO)
- **Berichtigung** (Art. 16 DSGVO)
- **Löschung** (Art. 17 DSGVO)
- **Einschränkung der Verarbeitung** (Art. 18 DSGVO)
- **Datenübertragbarkeit** (Art. 20 DSGVO)
- **Widerspruch** gegen Verarbeitung auf Grundlage berechtigter Interessen (Art. 21 DSGVO)
- **Widerruf einer Einwilligung** (Art. 7 Abs. 3 DSGVO) — wirkt für die Zukunft; rechtmäßige vorherige Verarbeitung bleibt bestehen

### Sonderweg für die Kundenkartei

Wenn Sie der Voice AI im Gespräch sagen „Löschen Sie meine Daten", wird die Kundenkartei **sofort** vollständig entfernt. Sie müssen keinen schriftlichen Antrag stellen.

### Zuständigkeit

Für Anfragen zur Kundenkartei sowie zu Fahrten bei einer konkreten Taxi-Firma wenden Sie sich bitte an diese Firma. Für Anfragen zum Plattformbetrieb als solchen wenden Sie sich an den Betreiber (siehe Abschnitt 1). Wir leiten Anfragen, die bei der falschen Stelle eingehen, unverzüglich weiter und bestätigen Ihnen den Eingang.

### Beschwerderecht

Sie haben das Recht, sich bei einer Datenschutz-Aufsichtsbehörde zu beschweren (Art. 77 DSGVO). Zuständig ist in Hessen die hessische Datenschutzaufsicht:
**Der Hessische Beauftragte für Datenschutz und Informationsfreiheit**
Postfach 3163, 65021 Wiesbaden
https://datenschutz.hessen.de

---

## 8. Auftragsverarbeitung durch den Plattformbetreiber

Wenn Sie als Taxi-Unternehmen die Plattform nutzen, ist der Betreiber Ihr Auftragsverarbeiter gemäß Art. 28 DSGVO. Eine schriftliche Auftragsverarbeitungsvereinbarung (AVV) wird mit jedem Taxi-Unternehmen geschlossen, bevor die Plattform produktiv genutzt wird. Diese AVV regelt Pflichten, technische Maßnahmen, Unterauftragsverarbeiter und Meldewege für Datenschutzverletzungen.

---

## 9. Technische und organisatorische Maßnahmen

Die wichtigsten Schutzmaßnahmen im Überblick:

- **Transportverschlüsselung** (HTTPS/TLS 1.2+) für alle Übertragungen
- **Mandantentrennung** auf Datenbank-Strukturebene — jede Firma hat eine eigene Sub-Collection
- **Anwendungs-Verschlüsselung der Kundenkartei**: Inhalte werden mit firmenspezifischen AES-256-GCM-Schlüsseln in Google Cloud KMS verschlüsselt. Der Betreiber kann die Klartextinhalte **nicht** ohne den firmenspezifischen Schlüssel wiederherstellen
- **Keine Audio-/Transkript-Persistierung** — Gesprächsinhalte existieren ausschließlich während der Sitzung im Arbeitsspeicher; gleiches gilt für ausgehende TTS-Synthese-Texte gegenüber Google Cloud TTS (in-memory-Verarbeitung, keine Persistierung)
- **Authentifizierung** über Firebase Auth mit Passwort-Hashing
- **Firestore Security Rules** verhindern jeden firmenübergreifenden Datenzugriff durch Clients

---

## 10. Einwilligung der Kundenkartei (wiederkehrende Anrufer)

Wenn Sie ein angeschlossenes Taxi-Unternehmen per Telefon kontaktieren, fragt die Voice AI am Ende des Gesprächs: **„Dürfen wir Ihren Namen und Ihre Rufnummer speichern, damit wir Sie bei Problemen oder Rückfragen erreichen können?"**

- Ein **Ja** führt dazu, dass Ihre Stammdaten (Name, Rufnummer, die letzten Abholadressen) verschlüsselt in der Kundenkartei abgelegt werden. Bei einem Folgeanruf wird Ihre Nummer erkannt und die Voice AI schlägt Ihnen bekannte Daten zur Bestätigung vor.
- Ein **Nein** oder das Schweigen auf die Frage führt dazu, dass **nichts** über Sie gespeichert wird, was über den aktuellen Auftrag hinausgeht (die Auftragsdaten selbst unterliegen der Aufbewahrung gemäß Abschnitt 4).

Die Einwilligung ist freiwillig, kann jederzeit widerrufen werden (mündlich im Gespräch oder schriftlich beim Taxi-Unternehmen) und hat keine Nachteile zur Folge, wenn sie verweigert wird.

---

## 11. Keine Profilbildung, kein Tracking, keine Werbung

Wir erstellen keine Profile im Sinne von Art. 22 DSGVO (mit Ausnahme der automatisierten Entscheidung der Voice AI über die Fahrerzuweisung — siehe Abschnitt 12). Wir setzen keine Tracking-Cookies, keine Werbe-IDs, keine Analysetools Dritter ein. Es erfolgt keine Weitergabe an Werbenetzwerke.

---

## 12. Automatisierte Entscheidungsfindung (Art. 22 DSGVO)

Die Voice AI trifft automatisiert folgende Entscheidungen:

1. **Erfassung des Fahrauftrags** aus dem Gespräch
2. **Auswahl des passenden Fahrers** anhand Verfügbarkeit und geschätzter Anfahrtszeit
3. **Optional: Abweisen des Anrufers mit Hinweis auf Betriebszeiten**

Diese Entscheidungen sind für die Durchführung des Fahrauftrags erforderlich (Art. 22 Abs. 2 lit. a DSGVO). Die Voice AI weist am Gesprächsbeginn ausdrücklich darauf hin, dass es sich um eine **„Digitale Disponentin"** handelt (Art. 22 Abs. 3 DSGVO — Transparenz). Sie haben jederzeit das Recht, ein menschliches Gespräch zu verlangen; das Taxi-Unternehmen hält hierzu einen Rückrufkontakt bereit.

---

## 13. Änderungen dieser Datenschutzerklärung

Wir können diese Datenschutzerklärung anpassen, um sie an geänderte Rechtslage oder an Änderungen der Funktionen der Plattform anzupassen. Die aktuelle Fassung ist stets auf der Website des Plattformbetreibers einsehbar. Das Datum der letzten Aktualisierung finden Sie am Anfang dieses Dokuments.

---

*Bei Fragen zur Datenverarbeitung wenden Sie sich bitte an die in Abschnitt 1 genannte Kontaktadresse oder — wenn es um Daten einer konkreten Taxi-Firma geht — direkt an die jeweilige Firma.*
