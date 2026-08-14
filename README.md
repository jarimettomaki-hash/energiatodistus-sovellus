# Energiatodistuksen lähtötiedot

Mobiiliystävällinen PWA-sovellus energiatodistuksen lähtötietojen keräämiseen. Sovellus perustuu toimitettuun Excel-lomakkeeseen ja tukee uudisrakennusta, olemassa olevaa rakennusta, korjausrakentamisen energiaselvitystä sekä energia-avustusta.

## Toiminnot

- vaiheittainen, mobiilissa toimiva lomake
- automaattinen paikallinen tallennus selaimeen
- JSON-varmuuskopiointi ja palautus
- rakennerivien pinta-alojen summat ja pinta-alapainotetut U-arvot
- puuttuvien pakollisten tietojen tarkistus
- tulostettava lähtötietoraportti / PDF
- PWA-välimuisti offline-käyttöä varten

## Käynnistys

Sovellus ei tarvitse käännösvaihetta:

```bash
python3 -m http.server 8080 -d .
```

Avaa `http://localhost:8080`.

## Rajaus

Sovellus tuottaa lähtötieto- ja luonnosraportin. Se ei tuota eikä allekirjoita virallista energiatodistusta. Virallinen energiatodistus laaditaan ja allekirjoitetaan energiatodistusrekisterissä pätevän, rekisteröidyn laatijan toimesta.
