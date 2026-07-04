TG BAU – WEBSITE-DATEIEN
=========================

INHALT
------
index.html         Startseite (Hero, Leistungen, Projekte, Ablauf, FAQ, Kurz-Kontakt)
kontakt.html        Eigene Anfrage-/Kontaktseite mit Formular
impressum.html       Impressum (Pflichtangaben, mit Platzhaltern)
datenschutz.html     Datenschutzerklärung (Vorlage, mit Platzhaltern)
assets/style.css     Gesamtes Design (Farben, Layout, Animationen)
assets/script.js     Interaktive Funktionen (Slider, FAQ, Zähler, Formular)

HOSTING
-------
1. Diesen kompletten Ordner (inkl. "assets") per FTP/SFTP oder über das
   Datei-Upload-Tool Ihres Hosters in das Hauptverzeichnis Ihres Webspace
   hochladen (meist "public_html", "htdocs" oder "www").
2. Der Ordner "assets" muss im selben Verzeichnis wie die .html-Dateien
   liegen, sonst werden Design und Animationen nicht geladen.
3. index.html ist automatisch die Startseite unter Ihrer Domain.

VOR DEM ONLINE-GEHEN UNBEDINGT ANPASSEN
----------------------------------------
- Telefonnummer (aktuell Platzhalter: 030 · 123 456 78) — kommt in allen
  Dateien mehrfach vor (Header, Kontakt, tel:-Links).
- E-Mail-Adresse (aktuell: info@tg-bau.de)
- Adresse (aktuell: Baustraße 14, 12045 Berlin)
- impressum.html: alle Angaben in [eckigen Klammern] ausfüllen
  (Geschäftsführer, Handelsregister, USt-IdNr., Handwerkskammer)
- datenschutz.html: an tatsächlich genutzte Dienste anpassen (Hosting,
  ggf. Formular-Versanddienst, Analyse-Tools) — im Zweifel juristisch
  prüfen lassen
- Projektbeispiele in index.html (#projekte) durch echte Referenzen
  ersetzen

DAS KONTAKTFORMULAR
--------------------
Das Formular zeigt aktuell nur eine Bestätigung im Browser an — es
verschickt noch KEINE echte E-Mail. Um Anfragen tatsächlich zu erhalten,
brauchen Sie einen Formular-Versanddienst (z. B. Formspree, GetForm,
oder ein serverseitiges PHP-Mail-Script Ihres Hosters). Sagen Sie
gerne Bescheid, wenn Sie dabei Unterstützung möchten.

SCHRIFTARTEN
------------
Die Website lädt "Space Grotesk", "Inter" und "JetBrains Mono" von
Google Fonts über eine Internetverbindung. Das funktioniert automatisch,
sobald die Seite online ist — es muss nichts weiter installiert werden.
