# VINKJE 2.0

VINKJE 2.0 is een bestaanszekerheidsdashboard dat problemen vroeg zichtbaar maakt en helpt voorkomen dat een administratief probleem een bestaansprobleem wordt.

## Centrale uitgangspunten

> **Niet een betere herstelprocedure bouwen. Zorgen dat herstel zo vroeg plaatsvindt dat die procedure niet meer nodig is.**

VINKJE vraagt niet primair om meer uitvoeringscapaciteit. Het probeert bestaande capaciteit terug te winnen door vermijdbare procedures, overdrachten en vervolgschade te voorkomen. Betere dienstverlening en lagere uitvoeringslasten kunnen zo dezelfde kant op wijzen.

Voor de ontwikkeling geldt:

> **We lossen nu alleen op wat de volgende bruikbare versie van VINKJE tegenhoudt. De rest wordt een ticket.**

We werken daarom in kleine stappen: bouwen, bekijken, begrijpen, het probleem en de eigenaar zichtbaar maken, prioriteren, oplossen en controleren.

## Meten in een pilot

Een pilot beoordeelt niet alleen financiële opbrengsten. We vergelijken ook:

- doorlooptijd;
- aantal contactmomenten;
- aantal overdrachten;
- aantal brieven;
- bezwaar- en beroepsprocedures;
- benodigde medewerkerstijd;
- tijd tot feitelijk herstel;
- voorkomen vervolgschade.

Zo wordt zichtbaar of vroeg administratief herstel zowel de burger als de uitvoering daadwerkelijk helpt.

## Techniek

Het project gebruikt Astro, Tailwind en de Netlify-adapter. Het huidige dashboard werkt uitsluitend met lokale voorbeeldgegevens.

## Astro-commando's

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## Uitrollen op Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/netlify-templates/astro-platform-starter)

## Lokaal ontwikkelen

| Prerequisites                                                                |
| :--------------------------------------------------------------------------- |
| [Node.js](https://nodejs.org/) v18.20.8+.                                    |
| (optional) [nvm](https://github.com/nvm-sh/nvm) for Node version management. |

1. Clone this repository, then run `npm install` in its root directory.

2. Recommended: link your local repository to a Netlify project. This will ensure you're using the same runtime version for both local development and your deployed project.

```
netlify link
```

3. Run the Astro.js development server:

```
npm run dev
```
