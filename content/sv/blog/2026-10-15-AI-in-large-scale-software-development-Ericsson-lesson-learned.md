---
title: "AI i storskalig mjukvaruutveckling"
date: 2026-10-15
draft: false
thumbnail: "/images/blog/2026-10-14-AI-in-large-scale-software-development-Ericsson-lesson-learned.jpg"
tags:
  - AI
  - data
  - Agentic AI
  - Software Development
  - Ericsson
---
## Lärdomar från Ericsson

![Presentation från Ericssons team om mjukvaruutveckling med AI-agenter](/images/blog/2026-10-14-AI-in-large-scale-software-development-Ericsson-lesson-learned.jpg)
Onsdagen den 14 oktober 2026 berättade [**Katerina Doneva**](https://www.linkedin.com/in/katerinag/) (**System Manager**) och [**Noman Latif**](https://www.linkedin.com/in/nomanlatif/) (**mjukvaruarkitekt**) från **Ericsson** om hur de har tagit in AI-agenter i utvecklingen av stora mjukvarubaserade produkter. Det skedde vid ett evenemang som [**Blue Science Park**](https://www.bluesciencepark.se/) arrangerade på **BlackBox** i Karlskrona.

## Hur stora produkterna är

Ericsson är inte längre bara ett företag för nätverk och antenner. De har också en stor mjukvaruportfölj. Till exempel används deras plånboksplattform i 24 länder och har över 600 miljoner aktiva konton. Deras moderniserade system för charging och billing är installerat på sex platser i USA och når över 160 miljoner mobilabonnenter.

## Varför är det svårt att använda AI?

Problemet är inte modellernas förmåga. I stora finansiella produkter är kostnaden för ett enda fel mycket hög, och processerna och skyddsräckena för kvalitet, säkerhet och skalbarhet har byggts upp med avsikt. Tusentals utvecklare arbetar med delar av produkten som hänger ihop, så det är inte enkelt att "börja om från noll". Att lära utvecklarna använda verktygen var faktiskt den lätta delen. Att få dem att fungera i hela organisationen visade sig vara det svåra.

## Vägen i fyra steg

Ericssons väg till att använda AI-agenter bestod av fyra steg: hitta rätt verktyg, få utvecklarna att börja använda det, förändra processerna och ta fram en styrmodell. Att välja verktyg i en stor organisation kan ta veckor eller månader, eftersom frågor och utmaningar som risken att källkod lämnar organisationen, hur man mäter värdet, vem som äger koden och immateriella rättigheter måste få svar. Alla utvecklare ställer inte heller upp direkt, av olika skäl, till exempel rädsla för förändring eller helt enkelt brist på tid. Därför vände sig teamet till de entusiastiska i organisationen ("Champions"), som visade sina framgångar för andra, och efter ett tag började alla använda verktygen.

## Från kodning till arbetsflöden

Trots att AI-agenter användes brett verkade produktiviteten fortfarande låg, eftersom kodning faktiskt bara är 10 till 15 procent av utvecklingsprocessen. För att få en verklig förändring kartlade de därför hela livscykeln för sina produkter, identifierade rollerna och byggde stöd med agenter för varje roll (till exempel krav, analys, utveckling, test och så vidare). Och precis som varje nytt verktyg behöver varje ny agent förändringsledning.

## Utmaningar med att bygga agenter

- **AI-vänliga artefakter:** Vanliga dokument (Word, PowerPoint, Excel, ...) är gjorda för människor. Agenter fungerar bättre med text och Markdown (MD), så teamet byggde mallar som både människor och agenter kan arbeta med. Dessa artefakter är gränssnitten mellan agenterna i arbetsflödet.
- **Kunskapslagret:** En språkmodell vet ingenting om ert företag och er produkt. Agenten måste få rätt kontext via RAG, MCP, kunskapsgrafer eller vektordatabaser. Det är enkelt att bygga en agent, men en agent som verkligen ger värde behöver rätt kontext.
- **Outtalad kunskap:** En del av organisationens kunskap finns bara i experternas huvuden eller i samtal. För att göra den outtalade kunskapen tydlig byggde teamet skills och interaktiva arbetsflöden som intervjuar experterna och gör om det de kan till tydliga artefakter.
- **System med flera agenter:** En styrande agent (orchestrator) bestämmer hur de andra agenterna utför sina uppgifter. Teamet har också skapat en modell som kallas agentteam (kodare, testare, ...), som de fortfarande utforskar och förbättrar.

## Agent Hub

När antalet agenter växte uppstod ett behov av att hantera deras livscykel. Eftersom verktygen från början inte kunde göra det byggde de en intern "Appbutik" för agenter, skills och styr filer, med en pipeline för säkerhetsgranskning, övervakning, betyg och en användargemenskap, en styrmodell, semantisk versionshantering och avveckling av agenter som inte används.

## Viktiga lärdomar

Att bli en organisation som arbetar med AI-agenter går varken snabbt eller enkelt. Det är en förändring av hela organisationen och inte bara en teknisk utrullning, och det innebär entusiasm, skepsis, prövande med fel och misstag samt initiativ som ger resultat både snabbt och långsamt. Modeller och verktyg blir hela tiden bättre, men organisationens data är en unik konkurrensfördel. Vinnaren är inte den organisation som har byggt hundratals agenter, utan den som har mest strukturerad kunskap och bäst koppling mellan sina arbetsflöden.
