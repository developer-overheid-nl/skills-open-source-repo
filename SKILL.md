---
name: open-source-repo
description: >-
  Maak de bestanden aan die nodig zijn voor een goed open source project, of
    controleer of ze al aanwezig zijn. Gebruik deze skill wanneer de gebruiker
    een repository open source wil publiceren, ontbrekende bestanden wil
    toevoegen, of een project wil klaarmaken voor publieke bijdragen.
    Voorbeelden: "maak dit project open source", "open source checklist", "voeg README
    toe", "CODE_OF_CONDUCT.md aanmaken", "publiccode.yml", "Standard for Public
    Code", "nieuwe open source repo opzetten", "welke bestanden heb ik nodig",
  "voeg een Security.md toe","voeg een licentie toe".
allowed-tools:
  - Read
  - Write
  - Edit
  - Glob
  - Grep
  - Bash(gh api *)
  - Bash(gh issue list *)
  - Bash(gh pr list *)
  - Bash(gh search *)
  - Bash(git *)
  - Bash(curl *)
  - Bash(find *)
  - Bash(npx *)
  - Bash(docker *)
  - Bash(/tmp/pcval/publiccode-parser-go *)
  - Bash(npx @stoplight/spectral-cli *)
  - WebFetch(*)
  - AskUserQuestion
  - Read
  - Bash(curl -s *)
  - Bash(npx github:developer-overheid-nl/oas-generator *)
  - Bash(npx @developer-overheid-nl/don-checker *)
  - Bash(npx @stoplight/spectral-cli *)
  - Bash(npx @redocly/cli *)
  - Bash(npx @openapitools/openapi-generator-cli *)
  - Bash(git clone *)
  - WebFetch(*)
---

# Maak alle bestanden aan die je nodig hebt voor een Open Source project

Maak alle benodigde bestanden aan die je nodig hebt om je project te open sourcen.

## Instructies

- Gebruik de `repo-docs-generator` om de files te genereren: `npx github:developer-overheid-nl/repo-docs-generator`
- Zet de files in de root van het project.
- Doe dit doormiddel van het aanmaken van een input.json op basis van de beschikbare projectinformatie. De input.json geef je vorm aan de hand van deze schema.json: https://github.com/developer-overheid-nl/repo-docs-generator/blob/main/input_json_schema.json
- Vraag zo nodig aan de user om extra input als je niet voldoende informatie hebt voor het aanmaken van de files.

## Roep "generate-publiccode-yml" skill aan
Roep deze skill aan om de publiccode.yml te genereren. Dit dient alsnog te gebeuren op basis van de repo-docs-generator tool.

## 1. Licentie bepalen

Gebruik de license file die de `repo-docs-generator` CLI genereert.

## Referenties

- [publiccode.yml schemadocumentatie](https://yml.publiccode.tools/schema.core.html)
- [Categorielijst](https://yml.publiccode.tools/categories-list.html)
- [SPDX licentie-identifiers](https://spdx.org/licenses/)
