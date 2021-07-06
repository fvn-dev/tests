# Sommervennen

Dette er en hjemmeoppgave for fvn.no - vi tror du kommer langt nok på tre timer, og vi regner med at du bruker et privat Github-repo til å vise skrittene du tar med hyppige og gode commits. Men har du gode erfaringer med gitlab eller bitbucket du vil fortelle oss om er vi åpen for se der også

## Vi trenger en ekstra nettavis - og vi trenger den nå!

Redaktøren har fått en kjempeidé i hengekøya, og vi må kaste oss rundt og få opp en "Proof of Concept" (POC) på - en rask mobilvennlig oversikt over de siste ferienyhetene.

1 vi kjører allerde nuxt, så lag en ny app med `npx create-nuxt-app`

_Så mange valg - hvilke tar du og hvorfor kan vi snakke om på intervju - lim inn oppsummeringen ✨  Generating Nuxt.js project i comitt eller readme_


2 juster forsiden i index.vue med litt stiler, logo og et slagord

3 lag en infoside som svarer opp på http://localhost:3000/demo 


## Livet er enklere med komponenter og litt dokumentasjon
_Storybook er greit til begge deler. I tillegg finnes det en ferdig kobling for nuxt så vi sparer tid når det koker._

4 installer storybook med `npm install --save-dev @nuxtjs/storybook postcss@latest`

5 lag en story for NuxtLogo komponenten, eller din egen logo komponent fra trinn 2

## Da er vi klare for få litt dynamikk inn på siden!

6 hent og vis `title` og `id` fra https://jsonplaceholder.typicode.com/posts på forsiden

7 lag en **dynamisk page** som henter en post fra jsonplaceholder viser `title` og `body`

### Ekstra ideer hvis fortsatt tid igjen:
_link fra front til detaljer for hver post, hent og vis random bilder fra placekitten eller picsum, lag en footer komponent basert på fvn.no og bruk i layout_
