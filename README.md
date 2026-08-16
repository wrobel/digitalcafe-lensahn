# Digitalcafé Lensahn

Statische, responsive und barrierearm gestaltete Webseite für das
Digitalcafé Lensahn.

## Lokal ansehen

Die Seite benötigt keinen Build-Schritt. Im Repository starten:

```bash
python3 -m http.server 8000
```

Anschließend <http://localhost:8000> öffnen.

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
