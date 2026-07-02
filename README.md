# Skills: Open Source Repository

Open Source Repository Skill is een Agent Skill die ontwikkelaars bij de Nederlandse overheid helpt om hun repository klaar te maken voor open source publicatie. De skill genereert bestanden zoals publiccode.yml, README.md, CONTRIBUTING.md, SECURITY.md en LICENSE op basis van projectinformatie. Daarnaast controleert de skill of de benodigde bestanden al aanwezig zijn en werkt bestaande bestanden bij waar nodig.

## Features
Deze codebase bestaat uit de volgende features:

- Genereert publiccode.yml op basis van projectinformatie
- Genereert README.md, CONTRIBUTING.md, SECURITY.md en LICENSE
- Controleert of open source bestanden al aanwezig zijn
- Werkt bestaande publiccode.yml bij
- Valideert publiccode.yml met publiccode-parser-go

## Aan de slag

### Vereisten

**PROJECTSPECIFIEK**: Voeg de vereisten voor jouw project toe, bijvoorbeeld:

- Node.js >= 18.x / Python >= 3.9 / PHP >= 8.1
- Git >= 2.30
- [Andere specifieke dependencies]

### Installatie

```bash
# Clone de repository
git clone https://github.com/developer-overheid-nl/skills-open-source-repo
cd project-directory

# Installeer dependencies
npm install
# of
pip install -r requirements.txt
# of
composer install
```

### Lokaal draaien

```bash
# Development server starten
npm run dev
# of
python manage.py runserver
# of
php artisan serve
```

## Ontwikkelstatus

Dit project heeft de status: **stable**

## Bijdragen

Leuk dat je overweegt om bij te dragen in dit project. Lees onze [CONTRIBUTING.md](CONTRIBUTING.md) voor meer informatie over hoe je kunt bijdragen.

### Gedragscode

Dit project hanteert een [gedragscode](CODE_OF_CONDUCT.md). Door bij te dragen aan dit project ga je akkoord met de voorwaarden hiervan.

## Security

Heb je een potentieel securityissue gevonden? Fijn dat je de moeite hebt genomen om hier in te duiken. Hoe je op een veilige manier melding kan maken vind je in [SECURITY.md](SECURITY.md).

## Licentie

Copyright © developer.overheid.nl.
Licensed under the [EUPL-1.2](LICENCE.md)

## Contact

Naam: developer.overheid.nl\
Email: developer.overheid@geonovum.nl\
Organisatie: Geonovum\


## Meer informatie

- [publiccode.yml](publiccode.yml) - Metadata volgens de publiccode.yml standaard
