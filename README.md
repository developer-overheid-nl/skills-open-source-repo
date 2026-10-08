> [!IMPORTANT]
> **Deze skill is verplaatst naar
> [`developer-overheid-nl/repo-docs-generator`](https://github.com/developer-overheid-nl/repo-docs-generator),**
> de repository met de tooling die de skill aanroept. Deze repository wordt
> gearchiveerd en krijgt geen updates meer.
>
> De plugin houdt zijn naam, dus je hoeft niets opnieuw te installeren:
>
> ```bash
> claude plugin update developer-overheid-open-source-repo@overheid-plugins
> ```
>
> De skill schrijft de bestanden nu niet meer zelf, maar vult `input.json` en
> draait de `repo-docs-generator` CLI. De templates in die repository zijn
> daarmee de enige bron van waarheid voor het formaat.

# Skills: Open Source Repository

Open Source Repository Skill is een Agent Skill die ontwikkelaars bij de Nederlandse overheid helpt om hun repository klaar te maken voor open source publicatie. De skill genereert bestanden zoals publiccode.yml, README.md, CONTRIBUTING.md, SECURITY.md en LICENSE op basis van projectinformatie. Daarnaast controleert de skill of de benodigde bestanden al aanwezig zijn en werkt bestaande bestanden bij waar nodig.

## Features
Deze codebase bestaat uit de volgende features:

- Genereert publiccode.yml op basis van projectinformatie
- Genereert README.md, CONTRIBUTING.md, SECURITY.md en LICENSE
- Controleert of open source bestanden al aanwezig zijn
- Werkt bestaande publiccode.yml bij

## repo-docs-generator

Dit project maakt gebruik van [`repo-docs-generator`](https://github.com/developer-overheid-nl/repo-docs-generator) om de benodigde open source bestanden (zoals publiccode.yml en LICENSE) te genereren.

## Bijdragen

Deze Agent Skill verbeteren? Graag! Pas de `Skill.md` aan naar gelang en dien een pull request in.

## Gedragscode

Dit project hanteert een [gedragscode](CODE_OF_CONDUCT.md). Door bij te dragen aan dit project ga je akkoord met de voorwaarden hiervan.

## Security

Heb je een potentieel securityissue gevonden? Fijn dat je de moeite hebt genomen om hier in te duiken. Hoe je op een veilige manier melding kan maken vind je in [SECURITY.md](SECURITY.md).

## Licentie

Copyright © developer.overheid.nl.
Licensed under the [EUPL-1.2](LICENSE.md)

## Contact

Naam: developer.overheid.nl\
Email: developer.overheid@geonovum.nl\
Organisatie: Geonovum\


## Meer informatie

- [publiccode.yml](publiccode.yml) - Metadata volgens de publiccode.yml standaard
