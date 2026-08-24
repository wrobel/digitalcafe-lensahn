# Digitalcafé Lensahn

Statische, responsive und barrierearm gestaltete Webseite für das
Digitalcafé Lensahn.

## Lokal ansehen

Die Seite benötigt keinen Build-Schritt. Im Repository starten:

```bash
python3 -m http.server 8000
```

Anschließend <http://localhost:8000> öffnen.

Alternativ vom übergeordneten Politik-Projekt aus:

```bash
python3 -m http.server 8000 --directory repos/digitalcafe-lensahn
```

Zum Prüfen im Browser:

1. Termin, Ort und Themen lesen und alle internen Sprunglinks anklicken.
2. Das Fenster auf eine schmale Smartphonebreite verkleinern; es darf kein
   horizontaler Scrollbalken erscheinen.
3. Mit der Tabulatortaste durch Links und Schaltflächen gehen; der Fokus muss
   immer sichtbar sein.
4. Auf 200 Prozent zoomen; Text und E-Mail-Adresse müssen lesbar bleiben.
5. Prüfen, dass die Kontaktadresse `gunnar@digitalcafe.lensahn.org` sichtbar
   und über die Schaltfläche erreichbar ist.

## Mit GitHub Pages veröffentlichen

1. Änderungen nach `main` pushen.
2. Unter **Settings → Pages** als Quelle **Deploy from a branch** wählen.
3. Branch `main` und Verzeichnis `/ (root)` auswählen und speichern.
4. Die von GitHub angezeigte `github.io`-Adresse prüfen.
5. Erst danach unter **Custom domain** `digitalcafe.lensahn.org` eintragen.
6. Anschließend beim DNS-Anbieter einen CNAME `digitalcafe` auf
   `wrobel.github.io` setzen.
7. Nach erfolgreicher DNS-Prüfung **Enforce HTTPS** aktivieren.

## Technische Leitplanken

- reines HTML und CSS
- kein JavaScript
- keine Cookies, Analyse oder externen Einbettungen
- keine externen Schriftarten
- Kerninformationen nach WCAG 2.2 AA gestaltet

## Bildmaterial

Die beiden für das Projekt KI-generierten Fotomotive liegen optimiert als WebP
unter `images/`. Sie werden direkt mit der Seite ausgeliefert; es werden keine
externen Bilddienste eingebunden.
