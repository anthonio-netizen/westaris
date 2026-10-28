# Westaris Roleplay — Wet- en Regelgeving

Complete, statische GitHub Pages-website én losse Markdown-wetdocumenten. Alle wetten zijn fictief, Nederlandstalig en geïnspireerd op het Amerikaanse rechtsstelsel.

**Status:** Concept 1.0, 28 oktober 2026. Juridische bedragen en regels dienen vóór gebruik in de RP officieel te worden vastgesteld door het Westaris-bestuur.

## Bekijk de documenten op GitHub

- [21 losse wetboeken en regel-documenten](documenten/README.md)
- [Alles samengevoegd in één Markdown-document](documenten/VOLLEDIG_WETBOEK.md)
- [Westaris Roleplay-website](index.html)

## Publiceren op GitHub Pages

1. Maak een nieuwe **public** GitHub-repository aan, bijvoorbeeld `westaris-wetgeving`.
2. Upload **alle bestanden en mappen uit deze ZIP** naar de hoofdmap van die repository. Let op: de hoofdmap moet direct `index.html` bevatten.
3. Open bij GitHub **Settings → Pages**. Kies bij **Build and deployment** voor **Deploy from a branch**.
4. Selecteer branch **main**, map **/(root)** en klik **Save**.
5. Je site verschijnt op `https://GEBRUIKERSNAAM.github.io/westaris-wetgeving/` (vervang GEBRUIKERSNAAM en, indien anders, de repositorynaam). Publicatie kan even duren.

GitHub Pages werkt met deze bestanden zonder extra programma's of npm-installatie.

## Mappenindeling

```
index.html                    # Startpagina website
404.html                      # Pagina niet gevonden
.nojekyll                     # Directe statische publicatie
assets/
  styles.css                  # Uiterlijk
  app.js                      # Navigatie en zoekgedrag
  search-data.js              # Index voor zoeken
  favicon.svg                 # Website-icoon
grondwet/index.html           # Webpagina grondwet
wetboek/index.html            # Webpagina strafwetboek
...                           # Overige wetten en tarieven
documenten/
  README.md                   # Inhoudsopgave van 21 wetboeken
  VOLLEDIG_WETBOEK.md         # Alle wetboeken in 1 Markdown-bestand
  01-grondwet-en-burgerrechten.md
  02-strafwetboek-penal-code.md
  ...                         # Overige 19 losse Markdown-documenten
```

## Wetten bewerken

- Gebruik GitHub's web-editor om een `.md`-bestand te bewerken. Dat verandert **niet automatisch** de bijbehorende `.html`-pagina.
- Voor zichtbare website-wijzigingen bewerk je de bijbehorende `<onderwerp>/index.html` en wanneer nodig `assets/search-data.js`.
- De website bevat een zoekfunctie, mobiele navigatie en een printweergave.
- Het portaal is geschreven voor **Westaris Roleplay** en bevat geen live koppeling met een FiveM-server.
- De wetboeken zijn **fictieve spelregels**, geen juridisch advies.

## Inhoud

- **21** afzonderlijke wet- en regeldocumenten.
- Amerikaans geïnspireerde *Penal Code*, *Vehicle Code*, *District Court*, *Bill of Rights*, strafklassen en *Miranda*-procedures.
- Alle content in het Nederlands, met dollars en mph waar dat bij de fictieve Amerikaanse setting past.
- IC-wetten en OOC-serverregels zijn apart beschreven.

## Versies

Zie [CHANGELOG.md](CHANGELOG.md) voor wijzigingen.
