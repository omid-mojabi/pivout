---
title: "Slutet för agile som vi känner det"
date: 2026-11-09
draft: false
thumbnail: "/images/blog/2026-11-09-The-end-of-agile-as-we-knew-it.jpg"
tags:
  - AI
  - Agile
  - Agentic AI
  - Embedded Systems
  - Software Development
  - DevOps
---
### Lärdomar från Software Center i Göteborg

![Slutet för agile - tade från Forbes](/images/blog/2026-11-09-The-end-of-agile-as-we-knew-it.jpg "Slutet för agile - tade från Forbes")
För en agilist som har arbetat länge inom området kan den här rubriken verka lite hård som beskrivning av agiles nuläge och framtid. Men som vi har lärt oss i den agila kulturen och övat på i decennier är det yttersta målet för varje praktiker att lära sig, även om alla de grunder och principer vi har byggt vårt arbete på ställs under debatt.

### Problemet

Det har gått mer än två decennier sedan [**det agila manifestet**](https://agilemanifesto.org/) publicerades, men företagen upplever fortfarande inte de fördelar de hade förväntat sig. Nyligen visade två forskare vid [**Software Center i Göteborg**](https://www.software-center.se/) i en [**artikel**](https://doi.org/10.1016/j.jss.2026.113100), baserad på fjorton års samverkansforskning med 14 stora företag inom bland annat fordon, telekom, tillverkning samt säkerhet och övervakning, samt en serie workshops under 2024, att det finns en bristande överensstämmelse mellan agiles ursprungliga principer och verkligheten i storskalig produktutveckling, särskilt för inbyggda system (embedded systems). Dessa system är oftast en kombination av mekanik, elektronik, mjukvara och artificiell intelligens.

### Att gräva efter grundorsaken

Det agila manifestet skrevs av en grupp mjukvaruingenjörer som mest byggde skräddarsydd mjukvara åt en specifik, lättillgänglig kund. De företag som studerats i den här forskningen befinner sig i en helt annan situation: många kunder, många team och många produkter, med gemensamma komponenter. Enligt författarna ligger problemet inte inom de agila teamen, utan i att skala arbetssättet bortom teamnivån. Produktledning, systemteknik och affärsmodeller, alltså de mekanismer som företag använder för att skala, saknas i agile. Ramverk som SAFe gjorde enligt en av de intervjuade heller ingen skillnad: ”Vi införde SAFe, men ingenting förändrades.”

![Utmaningar när agile ska anpassas till mjukvaruföretagens behov - från artikeln](/images/blog/2026-11-09-The-end-of-agile-as-we-knew-it.png "Utmaningar när agile ska anpassas till mjukvaruföretagens behov - från artikeln")

### Centrala utmaningar

- **Syfte**: ingen tydlig, gemensam definition av agile; att mål och medel blandas ihop; att ”varför” och ”vad” glöms bort på grund av för stort fokus på ”hur”; och bristande överensstämmelse med resten av organisationen, som support och försäljning, till följd av täta releaser under produktens livstid.
- **Leverera värde kontinuerligt**: under allt strängare regelkrav; hur svårt det är att ställa om från traditionella affärsmodeller; hur leverans av funktioner – från start till mål – fortfarande är en utmaning, och hur agila arbetssätt inte har gjort mycket för att underlätta detta.
- **Superset-plattform**: Plattformar som innehåller alla systemets funktioner, både mjukvara och annat, så att varje produkt i praktiken bara är en konfiguration av plattformen med fler eller färre funktioner. Idén löser många problem, bland annat vattenfallstänkandet i design, MVP:er som kan testas före leverans, interna beroenden och skräddarsydda lösningar, och den gör teamen responsiva. Men dagens agila arbetssätt gör föga åt detta och överlåter genomförandet i praktiken åt teamen själva.
- **Lärloopar**: Traditionellt byggde företag funktioner som antingen realiserades eller inte. Nu skiftar fokus mot förmågor med kvantitativa KPI:er, och iterativ driftsättning låter företag experimentera och mäta effekten. Teamens mål är att förbättra förmågor i stället för att bygga oändliga listor med funktioner som kunderna inte använder, vilket ofta sker i dagens agila paradigm.
- **AI först**: utformas allt fler arbetsuppgifter på ett sätt som syftar till att maximera utnyttjandet av artificiell intelligens, där människor involveras först när detta arbetssätt inte leder till tillfredsställande resultat. Detta är en teknik som, när det agila konceptet introducerades, ännu inte hade någon praktisk tillämpning inom industrin och inte heller fick någon större uppmärksamhet..
- **Tvärfunktionella team**: brister i styrning och regelefterlevnad; att arbetssättet inte går att skala bortom teamnivån; och bristande anpassning till sammanhanget.
- **Data som infrastruktur**: Data samlas ofta in i silos, något agila team förstärker genom att samla in den för sina egna funktioner. Tveksam kvalitet och semantik gör att företag misstror den och till och med ignorerar den när den motsäger ledares åsikter. Data som infrastruktur skapar tillit och möjliggör strukturerad, företagsövergripande, genuint datadriven mätning av framsteg och värde.

![RADIKALT perspektiv på systemteknik – från artikeln](/images/blog/2026-11-09-The-end-of-agile-as-we-knew-it-Radical-framework.png "RADIKALT perspektiv på systemteknik – från artikeln")

### Systemutveckling genom RADICAL-linsen

Författarna föreslår också ett konceptuellt ramverk, ännu inte testat, som kallas RADICAL. Till skillnad från mycket akademiskt arbete som erbjuder förbättringar av tidigare metoder (här agile) hävdar de i grunden att något bör ersätta agile snarare än komplettera det. I det föreslagna ramverket har sju principer tagits fram och beskrivits som krav på ett alternativt paradigm: Responsive (responsivt), Architecture (arkitektur), Data-driven (datadrivet), Integrated cross-functional alignment (integrerad, tvärfunktionell samstämmighet), Continuous (kontinuerligt), Aligned on business goals (förankrat i affärsmålen) och Leadership (ledarskap).

### Begränsningar

RADICAL-ramverket är för närvarande bara ett första förslag och har ännu inte validerats, och resultaten gäller främst inbyggda system i stora företag. Det ger oss som arbetar med mjukvara utrymme att kritiskt granska våra nuvarande arbetssätt i team och organisation, lägga grunden för en grundläggande omprövning som passar den verksamhet och bransch vi arbetar i, och avsluta det långa arbetet med att anpassa allt efter agila principer. Forskningen genomfördes dessutom i en kontext av stora företag och organisationer i norra Europa och Skandinavien, så man bör vara försiktig när resultaten ska generaliseras till andra platser eller till miljöer före skalning, som startups.

[**Länk till originalartikeln**](https://doi.org/10.1016/j.jss.2026.113100)
