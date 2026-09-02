# ALB CATERING – Website

Statische Website der ALB CATERING UG (haftungsbeschränkt), Ballendorf.
Veröffentlicht über GitHub Pages.

## Dateien

- `index.html` – die komplette Website. Bilder stecken als Daten-URI in der Datei,
  deshalb kommt die Seite ohne Bilderordner aus.
- `fahrplan-familienfeier.pdf` – das Freebie „Der 4-Wochen-Fahrplan“, das Besucher
  nach Eintragen ihrer E-Mail-Adresse herunterladen können.
- `danke.html` – Danke-Seite mit dem Download für Besucher ohne JavaScript.
- `weihnachten.html` – Kampagnenseite für Weihnachten 2026 mit den vier
  Weihnachtsmenüs. Von der Startseite über den grünen Streifen oben verlinkt.
  Gerichte, Preise, Bestellschluss und Vorlaufzeiten sind noch Platzhalter.
- `danke-anfrage.html` – Danke-Seite für das Weihnachts-Anfrageformular.
- `bilder-web/` – verkleinerte Fotos für die Weihnachtsseite.

## Formulare

Der Freebie-Abschnitt läuft über [Web3Forms](https://web3forms.com).
Der Zugangsschlüssel steht in `index.html` im Feld `access_key` und legt
fest, an welche Adresse die Anmeldungen gehen.

Der Besucher bekommt den Fahrplan sofort auf der Seite zum Herunterladen,
nicht per Mail — automatische Antwortmails sind bei Web3Forms kostenpflichtig.
Besucher ohne JavaScript landen auf `danke.html`, wo derselbe Download steht.

## Adresse

https://albcateringug-crypto.github.io/alb-catering/
