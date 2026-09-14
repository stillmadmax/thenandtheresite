---
title: Datenschutzerklärung - Then & There
lang: de
alt_url: https://stillmadmax.github.io/thenandtheresite/en/privacy
alt_label: English
---

# Datenschutzerklärung für Then & There

Stand: 14. September 2026

## Verantwortlich

<address>
Maximilian Schell<br>
%%KONTAKT_ADRESSE%%
</address>

E-Mail: %%KONTAKT_EMAIL%%

Ein Datenschutzbeauftragter ist nicht bestellt; dazu besteht keine gesetzliche Verpflichtung. Wende
dich mit allen Datenschutzanliegen bitte an die oben genannte Kontaktadresse.

## Kurzfassung

Then & There zeigt dir Fotos aus deiner Mediathek, die an diesem Tag in früheren Jahren entstanden
sind, und erkennt daraus Reisen, Orte und volle Tage. **Deine Fotos verlassen dein Gerät dabei
nicht.** Es gibt keine Benutzerkonten, keine Registrierung, keine Werbung, keine Analyse- oder
Tracking-Dienste. Die einzigen Daten, die das Gerät verlassen, sind **Koordinaten von Ortsmittelpunkten**
für Ortsnamen und **Kartenanfragen** an Apple Karten, beides nur, wenn du die Karten- oder
Ortsfunktionen nutzt.

## Welche Daten die App verarbeitet

### Fotos und Metadaten

Die App liest deine Fotomediathek **ausschließlich auf dem Gerät**. Aus jedem Foto und Video
verwendet sie nur Aufnahmedatum, Aufnahmeort (sofern im Foto gespeichert), Medientyp, Dauer und die
Favoriten-Markierung. Daraus baut sie einen Index, der lokal im App-Speicher liegt. Die Bilder selbst
werden nur zur Anzeige geladen. Es findet **kein Upload** statt, die App **schreibt nichts** in deine
Mediathek: keine Alben, keine Favoriten, keine Änderungen.

### Ortsnamen (Reverse-Geocoding)

Für Reisen und Orte fasst die App Fotos mit Ortsangabe in Gebiete von etwa zehn Kilometern zusammen.
Um einem Gebiet einen Namen zu geben, sendet sie **einmal pro Gebiet den Mittelpunkt** (Koordinaten)
an den Geocoding-Dienst von Apple (`MKReverseGeocodingRequest`, systemseitig). Das Ergebnis wird auf
dem Gerät gespeichert und nicht erneut abgefragt.

| Dienst | Anbieter | Zweck | Übermittelt werden |
| --- | --- | --- | --- |
| Reverse-Geocoding | Apple (MapKit, systemseitig) | Ortsname und Land für ein Fotogebiet | Koordinaten des Gebietsmittelpunkts |
| Apple Karten | Apple (MapKit, systemseitig) | Kartenkacheln für Reise- und Ortskarten | Kartenausschnitt, den du ansiehst |

Apple handelt dabei als **eigenständig Verantwortlicher**; es gelten die Datenschutzbestimmungen von
Apple: <https://www.apple.com/legal/privacy/>. Wir senden **keine Fotos, keine Kontaktdaten und keine
von uns vergebenen Nutzer- oder Gerätekennungen** mit. Technisch bedingt ist bei jeder Abfrage die
**IP-Adresse** deines Geräts für Apple sichtbar. Die App selbst speichert keine Standortverläufe und
fragt **nie den aktuellen Standort** deines Geräts ab; sie nutzt ausschließlich die Ortsangaben, die
bereits in den Fotos gespeichert sind.

### Übermittlung in Drittländer

Geocoding und Kartenkacheln laufen über Systemdienste von Apple. Apple verarbeitet Daten auch
außerhalb der EU, unter anderem in den USA, und stützt solche Übermittlungen nach eigenen Angaben
auf die Standardvertragsklauseln der EU-Kommission (Art. 46 Abs. 2 lit. c DSGVO). Bei einer
Übermittlung in ein Land ohne Angemessenheitsbeschluss besteht das Risiko, dass Behörden dort auf die
Daten zugreifen und dagegen kein den EU-Standards vergleichbarer Rechtsschutz besteht. Übermittelt
werden ausschließlich Koordinaten von Gebietsmittelpunkten und Kartenausschnitte.

### App Store

Die App wird über den App Store von Apple verbreitet. Beim Herunterladen und Aktualisieren
verarbeitet Apple Daten (z. B. Apple-Account, Zeitpunkt des Downloads, Gerätedaten) in eigener
Verantwortung. Darauf haben wir keinen Einfluss; es gilt die Datenschutzerklärung von Apple.

### Einstellungen und Erinnerungen

Filter, Zuhause, Mindestentfernung und die Erinnerungszeit werden **lokal auf dem Gerät** gespeichert
(`UserDefaults`). Die tägliche Erinnerung ist eine **lokale Mitteilung**, die die App auf dem Gerät
plant; es ist kein Push-Dienst beteiligt. Alle diese Daten werden gelöscht, wenn du die App löschst.

## Rechtsgrundlagen

- **Lesen der Mediathek, Index und Einstellungen auf dem Gerät:** Die Verarbeitung findet
  ausschließlich lokal statt und dient der von dir angeforderten Funktion der App - Art. 6 Abs. 1
  lit. b DSGVO. Den Zugriff auf die Mediathek erteilst du über den Systemdialog von iOS; er ist
  zugleich Einwilligung nach § 25 Abs. 1 TDDDG für den Zugriff auf Informationen in deinem Endgerät.
  Du kannst ihn jederzeit in den iOS-Einstellungen widerrufen.
- **Übermittlung von Gebietsmittelpunkten und Kartenausschnitten an Apple:** Art. 6 Abs. 1 lit. b
  DSGVO, weil Ortsnamen und Karten ohne diese Abfragen nicht dargestellt werden können. Die
  Abfragen erfolgen nur, wenn du die Reise-, Orts- oder Kartenansichten öffnest.
- **Mitteilungen:** Einwilligung über den Systemdialog von iOS - Art. 6 Abs. 1 lit. a DSGVO;
  widerrufbar in den iOS-Einstellungen oder über den Schalter in der App.
- **Zugriffsprotokolle beim Betrieb dieser Website:** siehe Abschnitt "Hosting dieser Seite".

## Speicherdauer

Wir betreiben selbst keine Server und speichern deine Daten nicht. Der Index, der Ortsnamen-Cache
und die Einstellungen bleiben auf deinem Gerät, bis du die App löschst oder in den Optionen die
Mediathek neu einlesen lässt. Wie lange Apple Zugriffsprotokolle vorhält, bestimmt Apple. Schreibst
du uns per E-Mail, löschen wir die Nachricht, sobald dein Anliegen abschließend geklärt ist und keine
gesetzlichen Aufbewahrungspflichten entgegenstehen.

## Teilen von Fotos

Wenn du ein Foto oder Video über die Teilen-Funktion weitergibst, geschieht das über das
System-Teilen von iOS mit den Originaldaten des Fotos. Wohin du teilst, entscheidest du; für die
Weitergabe ist der jeweils gewählte Dienst verantwortlich.

## Berechtigungen

- **Fotos (Alle Fotos)**: um die Mediathek zu lesen. Mit "Ausgewählte Fotos" kann die App keine
  Rückblicke bilden und zeigt einen Hinweis.
- **Mitteilungen**: nur, wenn du die tägliche Erinnerung einschaltest.

Die App fordert **keinen Standortzugriff** und **keinen Kamerazugriff** an. Jede Berechtigung kann in
den iOS-Einstellungen widerrufen werden. Du bist weder gesetzlich noch vertraglich verpflichtet, sie
zu erteilen; ohne Fotozugriff kann die App lediglich nichts anzeigen.

## Datenweitergabe und Tracking

Es findet **kein Tracking** statt. Daten werden nicht für Werbung genutzt, nicht mit Daten Dritter
zusammengeführt und nicht an Datenbroker weitergegeben. Es gibt keine Analyse-SDKs und keine
Bibliotheken Dritter.

## Hosting dieser Seite

Dieser Abschnitt betrifft **nicht die App, sondern diese Internetseite**. Die Seite wird über
**GitHub Pages** bereitgestellt, einen Dienst der GitHub, Inc. (88 Colin P. Kelly Jr. Street, San
Francisco, CA 94107, USA), einem Unternehmen des Microsoft-Konzerns. Beim Aufruf der Seite
übermittelt dein Browser technisch notwendige Daten an GitHub, insbesondere deine **IP-Adresse**,
Datum und Uhrzeit der Anfrage, die aufgerufene Adresse sowie Angaben zu Browser und Betriebssystem.
GitHub gibt in der eigenen Dokumentation an, die IP-Adresse von Besucherinnen und Besuchern aus
Sicherheitsgründen zu protokollieren und zu speichern.

Auf Umfang und Dauer dieser Protokollierung haben wir keinen Einfluss; GitHub handelt insoweit in
eigener Verantwortung. Näheres in GitHubs Datenschutzerklärung:
<https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement>

**Rechtsgrundlage** ist Art. 6 Abs. 1 lit. f DSGVO. Unser berechtigtes Interesse liegt darin, diese
Pflichtinformation zuverlässig, sicher und ohne eigenen Serverbetrieb bereitzustellen. Du kannst der
Verarbeitung nach Art. 21 DSGVO widersprechen.

**Übermittlung in die USA:** GitHub verarbeitet Daten auch in den Vereinigten Staaten. Das Unternehmen
stützt solche Übermittlungen nach eigenen Angaben auf die Standardvertragsklauseln der
EU-Kommission (Art. 46 Abs. 2 lit. c DSGVO) und auf das EU-U.S. Data Privacy Framework.

Diese Seite setzt **keine Cookies**, bindet keine externen Schriftarten, Skripte oder Grafiken ein und
verwendet **keine Analyse- oder Tracking-Werkzeuge**. Der Aufruf erfolgt verschlüsselt über HTTPS.

## Kinder

Die App richtet sich nicht gezielt an Kinder und erhebt keine personenbezogenen Daten über sie.

## Deine Rechte

Dir stehen die folgenden Rechte zu: Auskunft über die zu deiner Person verarbeiteten Daten
(Art. 15 DSGVO), Berichtigung (Art. 16), Löschung (Art. 17), Einschränkung der Verarbeitung
(Art. 18), Datenübertragbarkeit (Art. 20) sowie Widerspruch gegen eine Verarbeitung (Art. 21). Hast
du in eine Verarbeitung eingewilligt, kannst du die Einwilligung jederzeit mit Wirkung für die
Zukunft widerrufen (Art. 7 Abs. 3 DSGVO).

**Praktischer Hinweis:** Die App legt bei uns keine Nutzerkonten und keine serverseitige Datenbank
an. Alle in der App entstehenden Daten liegen ausschließlich auf deinem Gerät; du kannst sie dort
selbst einsehen und löschen, spätestens mit dem Löschen der App. Da wir dich anhand dieser Daten nicht
identifizieren können, sind wir nach Art. 11 Abs. 2 DSGVO nicht verpflichtet, allein zur Erfüllung
dieser Rechte zusätzliche Daten zu speichern. Schreibst du uns an die oben genannte E-Mail-Adresse,
verarbeiten wir die Angaben aus deiner Nachricht - insoweit gelten die Rechte uneingeschränkt.

### Beschwerderecht

Du hast das Recht, dich bei einer Datenschutz-Aufsichtsbehörde über die Verarbeitung deiner
personenbezogenen Daten zu beschweren (Art. 77 DSGVO).

<address>
Bayerisches Landesamt für Datenschutzaufsicht (BayLDA)<br>
Postfach 1349<br>
91504 Ansbach<br>
<a href="https://www.lda.bayern.de">www.lda.bayern.de</a>
</address>

## Änderungen

Bei Funktionsänderungen wird diese Erklärung angepasst. Maßgeblich ist die jeweils unter dieser URL
veröffentlichte Fassung.
