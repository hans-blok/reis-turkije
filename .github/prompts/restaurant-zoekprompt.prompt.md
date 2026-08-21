---
mode: agent
description: Zoek vegetarische en vooral vegan restaurants per plaats en leg de resultaten vast in artefacten/restaurants.md met duidelijke score, locatie en werkende link.
---

# Prompt voor Copilot: restaurants zoeken en vastleggen

Zoek uitsluitend restaurants die in de betreffende plaats een duidelijk vegetarisch menu hebben, bij voorkeur volledig vegan of sterk vegan-georiënteerd. Neem geen restaurants op die slechts een paar losse vegetarische gerechten hebben naast een voornamelijk vleesgericht menu.

## Strikte regels

1. Zoek per plaats op basis van de geplande reisroute of de gevraagde locatie.
2. Geef altijd expliciet aan in welke plaats het restaurant ligt.
3. Neem alleen restaurants op als:
   - het restaurant duidelijk vegetarisch is
   - of het restaurant volledig vegan is
   - of het restaurant een specifiek, duidelijk vegan/vegetarisch menu heeft
4. Sluit restaurants uit die alleen incidenteel vegetarische opties aanbieden zonder duidelijke vegetarische focus.
5. Beoordeel elk restaurant op een schaal van 1–10 voor:
   - vegetarische opties
   - vegan opties
   - reviews
   - prijsindicatie
6. Houd de beoordeling consistent, realistisch en niet te optimistisch.
7. Voeg altijd een werkende URL toe:
   - website van het restaurant, als die bestaat
   - anders een officiële, betrouwbare alternatieve link zoals Instagram, Google Maps, menu-pagina, reservatiepagina of een bekend platform met werkende pagina
   - als er geen bruikbare link beschikbaar is, laat het restaurant weg in plaats van een onbetrouwbare link te plaatsen
8. Gebruik uitsluitend werkende links; geen dode, gebroken of twijfelachtige URL's.
9. Schrijf de resultaten altijd naar `artefacten/restaurants.md`.

## Vereiste structuur voor elk restaurant

Voor elk restaurant geef je:
- plaats
- restaurantnaam
- type (vegetarisch / vegan / vegetarisch + vegan opties)
- adres of wijk
- korte beschrijving
- score vegetarische opties
- score vegan opties
- score reviews
- score prijsindicatie
- werkende URL

## Uitvoervereiste

Werk `artefacten/restaurants.md` bij in een duidelijke tabel per plaats, in het Nederlands, met dezelfde stijl als de rest van de repo.

## Belangrijk

- De plaats moet altijd duidelijk zichtbaar zijn.
- Alleen restaurants met een duurzaamheid/vegetarische focus, bij voorkeur vegan.
- Geen valse of onbetrouwbare links.
- Geen algemene opsomming zonder concrete, gecontroleerde restaurantresultaten.
- Als een plaats niet zeker is of geen betrouwbare keuze heeft, vermeld dat kort en neem geen twijfelachtige restaurants op.

## Verwachte eindoutput

Geef een korte samenvatting van de gevonden restaurants per plaats, inclusief:
- totaal aantal restaurants
- beste vegan/vegetarische keuzes
- eventuele aandachtspunten
- vermelding dat alleen betrouwbare, werkende links zijn gebruikt

Zorg dat alles in `artefacten/restaurants.md` staat en klaar is om in de site te plaatsen.
