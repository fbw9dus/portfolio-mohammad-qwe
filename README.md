# Profil-Seite

![layout](drafts/page.png "Portfolio Seite")

- Seite nur für mobile
- meta Tag für die korrekte Skalierung auf Handys benutzen:
  ```html
  <meta name="viewport" content="width=device-width, initial-scale=1">
  ```
- Link für Email, der E-Mail Anwendung öffnet (6/5)
- Link für Telefon, der Telefon-Anwendung öffnet (5/5)
- Link zum Lebenslauf(PDF), der einen Download auslöst (5/5)
- Links zu Social Media Profilen
  - Haben Icons der Dienste (10/10)
  - Sollen in einem neuen Tab öffnen (5/5)
  
- Foto, das im Kreis dargestellt wird, mit border-radius (5/5)
- Navigation zu den Abschnitten mit Hash-Links (10/10)
- Bilder im Portfolio sollen verlinkt sein (10/10)

## Anforderungen für den Code
- Keine Block-Tags in Inline-Tags (0/10)
```diff
- Bei den Kontakt-Links sind p-Tags in a-Tags. a ist ein Inline-Element, p ist ein Block-Element
```
- Padding in den Links der Hauptnavigation (10/10)
- Abstand zwischen Text und Fensterrand und zwischen Text und Element-Rand (8/10)
```Bei Handy-Auflösung läuft der Text der Links in Kontakt über den Fensterrand hinaus```
- Korrekte html-Grundstruktur (html, head, body) (10/10)
```diff
- Bitte nicht hr benutzen, stattdessen border
```
- Keine Viewport-Elemente im head (5/5)

### Punkte
(**89**/100)
