# verslag opdracht 1: Package manager

> Verslaggever: Zinedin El Habachi

## Beschrijving

In deze opdracht moesten we gebruikmaken van scripts in de powershell. We moesten we een package manager gebruiken om applicaties eenvoudiger te installeren.

Het doel van deze opdract was om bekend te raken met het gebruiken van een package manager en de eerste stappen te leren om een script te schrijven.

## Antwoorden

### Vraag 1: De PowerShell-prompt toont de map waar we ons nu bevinden. Wat is de naam van deze directory?

C:\Windows\system32>

### Vraag 2: In welke map heb je het script bewaard?

```
"C:\Users\zined\Desktop\SEL\script hello world.ps1"
```

### Vraag 3: Wat doen de opties -e en --id voor winget install

#### -e

-e zorgt ervoor dat alleen het pakket met de exacte naam wordt gebruikt.

#### --id

Je gebruikt --id wanneer je de exacte pakket-ID van de applicatie wilt installeren.

## Evaluatiecriteria

- [x] Je hebt een package manager voor jouw besturingssysteem geïnstalleerd.
- [x] Je hebt een script (PowerShell of Bash, afhankelijk van je besturingssysteem) geschreven en gebruikt om de opgesomde applicaties te installeren.
- [x] Je toont inzicht in de werking van een package manager en kan deze vlot kan gebruiken om basistaken uit te voeren.
- [x] Je hebt een verslag gemaakt op basis van het template.
- [ ] De cheat sheet is aangevuld met nuttige commando's die je wil onthouden.
- [x] Je kan een correct antwoord geven op de vragen die zijn aangeduid met een :question:.

## Problemen en oplossingen

Geen problemen ondervonden.

## Demo

Als eerst stap zou ik windows powershell ISE openen als administrator. De volgende stap is het installeren van de package manager met de volgende link: [Winget](https://aka.ms/getwingetpreview).

Vervolgens ga je op de [website](https://winget.run/) en kies je de applicatie die je wilt installeren.

hierna gebruik je het volgende commando met de id van de applicatie:

```
Write-Host "Installatie applicatie"
winget install -e --id id.van.applicatie
```

Ten slotte sla ik de script op in een map naar keuze.

## Reflectie

De opdracht was niet zo moeilijk, maar ik vond de uitleg soms te vaag. Desondanks zou ik het niets anders doen als ik het opnieuw moeten doen. Deze opdracht heeft mij leren kennismaken met een packet package manager en Markdown.

## Bronnen

https://winget.run
