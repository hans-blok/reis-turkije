# Reis Turkije 2026

Reisplanning van Leanne en Hans naar Turkije: heenvlucht op maandag 28 september, verblijf in onder andere Göreme (Cappadocië), en terugvlucht vanaf Antalya op dinsdag 13 oktober.

De planning staat dag voor dag beschreven in de map [`artefacten/`](artefacten/): vluchten, overnachtingen en bezienswaardigheden per dag.

## Site bekijken

De reisplanning wordt gepubliceerd als website met [MkDocs](https://www.mkdocs.org/) (Material thema). Zodra GitHub Pages is ingesteld (zie hieronder), is de site te vinden op:

```
https://hans-blok.github.io/reis-turkije/
```

De repository zelf staat op [github.com/hans-blok/reis-turkije](https://github.com/hans-blok/reis-turkije).

## Lokaal draaien

```bash
pip install -r requirements-docs.txt
mkdocs serve
```

Open daarna `http://localhost:8000` in de browser.

## GitHub instellen

1. **Repository aanmaken op GitHub**
   De repository bestaat al: [github.com/hans-blok/reis-turkije](https://github.com/hans-blok/reis-turkije).

2. **Remote koppelen aan deze lokale repo**
   ```bash
   git remote add origin https://github.com/hans-blok/reis-turkije.git
   git branch -M main
   git push -u origin main
   ```
   Daarna kun je nieuwe wijzigingen pushen met `push.bat "commit message"`.

3. **GitHub Pages inschakelen**
   De site wordt niet automatisch gebouwd; publiceer 'm met MkDocs zelf:
   ```bash
   mkdocs gh-deploy
   ```
   Dit bouwt de site en pusht het resultaat naar de branch `gh-pages`.

4. **Pages-bron controleren**
   Ga in de repository naar **Settings → Pages** en zet de bron op branch `gh-pages`, map `/ (root)`. Na een paar minuten is de site live op de URL hierboven.

5. **`mkdocs.yml` bijwerken**
   Vul `site_url` in [`mkdocs.yml`](mkdocs.yml) in met de echte GitHub Pages-URL, zodat interne links en zoekfunctie correct werken.
