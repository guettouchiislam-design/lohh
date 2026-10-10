CNC-Rechner – PWA für PWABuilder

Dateien (alle 12 in den GLEICHEN Ordner / das Hauptverzeichnis des Repositorys hochladen):
- index.html: Anwendung (Version 6: Fräsen, Drehen, Bohren, Gewinde, Passung, Info; Deutsch/Englisch)
- manifest.json: PWA-Manifest
- sw.js: Service Worker für Offline-Cache (Cache-Name cnc-rechner-v8)
- icon-32.png / icon-180.png / icon-192.png / icon-512.png: App-Icons
- icon-512-maskable.png: maskierbares Icon (Android)
- screenshot-narrow-1.png / screenshot-narrow-2.png: Screenshots Smartphone (1080x1920)
- screenshot-wide.png: Screenshot Desktop (1280x720)

Für GitHub Pages: vorhandene Dateien mit gleichem Namen ersetzen. Die Startseite muss über HTTPS erreichbar sein.
Danach die URL bei PWABuilder prüfen (Seite mit Strg+F5 neu laden, dann den Aktualisieren-Button neben "Last tested" drücken).

Hinweis zum Update: Der Service Worker nutzt einen Cache. Wird eine neue Version hochgeladen,
muss der Cache-Name in sw.js (CACHE = 'cnc-rechner-vX') erhöht werden, sonst zeigt das Gerät weiter die alte Version.
