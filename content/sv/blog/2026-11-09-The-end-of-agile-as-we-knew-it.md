---
title: "Slutet för agile som vi känner det"
date: 2026-11-09
draft: false
thumbnail: "/images/blog/2026-11-09-The-end-of-agile-as-we-knew-it.png"
tags:
  - AI
  - Agile
  - Agentic AI
  - Embedded Systems
  - Software Development
  - DevOps
---
### Lärdomar från [**Software Center i Göteborg**](https://www.software-center.se/)

![Utmaningar när agile ska anpassas till mjukvaruföretagens behov - från artikeln](/images/blog/2026-11-09-The-end-of-agile-as-we-knew-it.png)
För en agilist som har arbetat länge inom området kan den här rubriken verka lite hård som beskrivning av agiles nuläge och framtid. Men som vi har lärt oss i den agila kulturen och övat på i decennier är det yttersta målet för varje praktiker att lära sig, även om alla de grunder och principer vi har byggt vårt arbete på ställs under debatt.

### Problemet

Det har gått mer än två decennier sedan [**det agila manifestet**](https://agilemanifesto.org/) publicerades, men företagen upplever fortfarande inte de fördelar de hade förväntat sig. Nyligen visade två forskare vid Software Center i Göteborg i en [**artikel**](https://doi.org/10.1016/j.jss.2026.113100), baserad på fjorton års samverkansforskning med 14 stora företag inom bland annat fordon, telekom, tillverkning samt säkerhet och övervakning, samt en serie workshops under 2024, att det finns en bristande överensstämmelse mellan agiles ursprungliga principer och verkligheten i storskalig produktutveckling, särskilt för inbyggda system (embedded systems). Dessa system är oftast en kombination av mekanik, elektronik, mjukvara och artificiell intelligens.

### Att gräva efter grundorsaken

Det agila manifestet skrevs av en grupp mjukvaruingenjörer som mest byggde skräddarsydd mjukvara åt en specifik, lättillgänglig kund. De företag som studerats i den här forskningen befinner sig i en helt annan situation: många kunder, många team och många produkter, med gemensamma komponenter. Enligt författarna ligger problemet inte inom de agila teamen, utan i att skala arbetssättet bortom teamnivån. Produktledning, systemteknik och affärsmodeller, alltså de mekanismer som företag använder för att skala, saknas i agile. Ramverk som SAFe gjorde enligt en av de intervjuade heller ingen skillnad: ”Vi införde SAFe, men ingenting förändrades.”

### Centrala utmaningar

- **Definitioner och tolkningar**: ingen gemensam definition av agile; regulatoriska krav och certifieringskrav som ofta förutsätter vattenfallsliknande mjukvaruutveckling; bristande anpassning till sammanhanget; och att mål blandas ihop med arbetet för att förbättra agiliteten i produktutvecklingsprocessen.
- **Affärsmodeller och intäktsmodeller**: att ”varför” och ”vad” glöms bort på grund av för stort fokus på ”hur”; affärsmodeller som inte passar med kontinuerlig leverans; och att MVP:er är verkningslösa i produkter som måste vara kompletta i varje iteration för att klara kvalitets- och funktionstester.
- **Vattenfalls- och hårdvarucentrerat tankesätt i systemdesign**: perfektionism i systemdesign och systemteknik, svårigheter att frikoppla team och bristande tillit.
- **Organisationskultur**: allvarliga utmaningar med att skapa en samordnad rytm mellan mjukvaruutveckling och andra delar av organisationen, som support och försäljning, till följd av täta releaser under produktens livstid; brister i styrning och regelefterlevnad; avsaknad av korta återkopplingsloopar i en B2B-miljö; och att arbetssättet inte går att skala bortom teamnivån.

### Systemutveckling genom RADICAL-linsen

Författarna föreslår också ett konceptuellt ramverk, ännu inte testat, som kallas RADICAL. Till skillnad från mycket akademiskt arbete som erbjuder förbättringar av tidigare metoder (här agile) hävdar de i grunden att något bör ersätta agile snarare än komplettera det. I det föreslagna ramverket har sju principer tagits fram och beskrivits som krav på ett alternativt paradigm: Responsive (responsivt), Architecture (arkitektur), Data-driven (datadrivet), Integrated cross-functional alignment (integrerad, tvärfunktionell samstämmighet), Continuous (kontinuerligt), Aligned on business goals (förankrat i affärsmålen) och Leadership (ledarskap).

### Begränsningar

RADICAL-ramverket är för närvarande bara ett första förslag och har ännu inte validerats, och resultaten gäller främst inbyggda system i stora företag. Det ger oss som arbetar med mjukvara utrymme att kritiskt granska våra nuvarande arbetssätt i team och organisation, lägga grunden för en grundläggande omprövning som passar den verksamhet och bransch vi arbetar i, och avsluta det långa arbetet med att anpassa allt efter agila principer. Forskningen genomfördes dessutom i en kontext av stora företag och organisationer i norra Europa och Skandinavien, så man bör vara försiktig när resultaten ska generaliseras till andra platser eller till miljöer före skalning, som startups.
