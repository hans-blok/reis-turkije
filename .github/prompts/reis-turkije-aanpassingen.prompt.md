---
mode: agent
description: Pas de Turkije-reiswebsite aan door de homepage, kaart, dagbestanden en restaurants te actualiseren, met een korte samenvatting van de wijzigingen.
---

# Prompt voor Copilot: Turkije-reiswebsite bijwerken

Je werkt in deze repository voor de reiswebsite van Leanne en Hans in Turkije. Je past de inhoud aan op basis van de actuele planning, zodat de site consistent blijft en gebruiksvriendelijk is.

## Taken

1. Pas de homepage aan in `artefacten/index.md`
   - Controleer het schema, de overnachtingen, de reistijden en de kolommen voor zon op / zon onder / klimaat.
   - Werk de tijdstippen voor zonsopgang en zonsondergang bij waar nodig, per locatie en per datum.
   - Corrigeer de klimaatgegevens als dat nodig is.
   - Houd de taal en stijl consistent met de rest van de site.

2. Pas de routekaart aan
   - Controleer `artefacten/kaart.html` op routegegevens, plaatsnamen, stopplaatsen en tekstuele beschrijvingen.
   - Als steden, tussenstops, of locaties zijn gewijzigd, werk die dan aan in de kaart en bijbehorende labels.
   - Houd de schematische kaart duidelijk en consistent met de planning.

3. Pas de dagbestanden aan in `artefacten/dagen/`
   - Werk alleen de relevante dagbestanden bij die door de verandering getroffen worden.
   - Controleer inhoud, datumlabels, verblijfplaats, bezienswaardigheden, praktische notities en timing.
   - Houd de stijl per dag gelijk aan de bestaande documenten.

4. Pas het restaurantbestand aan indien nodig
   - Controleer `artefacten/restaurants.md`.
   - Als een plaats vervalt, niet meer relevant is of niet meer passend in de planning, verwijder of corrigeer dan de betreffende vermelding.
   - Houd de rest van het overzicht intact en consistent.

5. Verwerk onzekerheden zorgvuldig
   - Als een datum, plaats, tijd, hotel, route of restaurant onzeker is, stel dan kort een vraag voordat je iets aanpast.
   - Vermijd het verzinnen van exacte gegevens als die niet betrouwbaar zijn.

## Kwaliteitsregels

- Houd de site in het Nederlands, tenzij een bestaande regel expliciet in een andere taal staat.
- Gebruik dezelfde stijl als de rest van de repo: eenvoudig, helder en praktisch.
- Werk alleen die bestanden bij die nodig zijn voor de aangevraagde wijziging.
- Vermijd onnodige extra wijzigingen.
- Zorg dat links, relatieve paden en navigatie blijven werken.

## Output die je aan het einde moet geven

Geef een korte samenvatting van de aanpassingen, bijvoorbeeld:

- Homepage aangepast: ...
- Zonsopgang / zonsondergang / klimaat bijgewerkt voor: ...
- Kaart aangepast: ...
- Dagbestanden bijgewerkt: ...
- Restaurants bijgewerkt: ...
- Open vragen / onzekerheden: ...

Als je twijfelt over een feit, stel eerst een korte vraag en wacht op bevestiging voordat je definitieve wijzigingen doorvoert.
