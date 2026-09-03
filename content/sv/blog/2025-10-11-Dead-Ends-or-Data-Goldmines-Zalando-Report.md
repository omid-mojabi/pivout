---
title: "Återvändsgränder eller dataguldgruvor"
date: 2025-10-11
draft: false
thumbnail: "/images/blog/2025-10-11-Dead-Ends-or-Data-Goldmines-Zalando-Report.jpg"
tags:
  - AI
  - data
  - postmortem
---
## Investeringsinsikter från två års AI-driven analys av postmortems

![Dead Ends or Data Goldmines - Zalando Report 2025](/images/blog/2025-10-11-Dead-Ends-or-Data-Goldmines-Zalando-Report.jpg)

Zalando publicerade nyligen en [**rapport**](https://engineering.zalando.com/posts/2025/09/dead-ends-or-data-goldmines-ai-powered-postmortem-analysis.html) som visar hur företaget förvandlade sina postmortems (om du fortfarande lever på Scrum-planeten kan du tänka på dem som Retrospectives!) — från statiska rapporter om misslyckanden, med nedskrivna åtgärder begravda någonstans (förhoppningsvis på en Confluence-sida!) som teamen aldrig återvände till efter diskussionerna — till en kraftfull källa för strategiska insikter.

Traditionellt avslutades varje lärdom med en manuellt skriven postmortem eller något annat format avsett att dokumentera vad som gick fel och hur man skulle kunna undvika det i framtiden (kom igen! Det här är affärsvärlden! Det som gick bra glömdes definitivt bort med ljusets hastighet!). Men i takt med att dessa rapporter samlades på hög över tid förblev deras gemensamma värde inlåst — materialet var helt enkelt för omfattande och inkonsekvent för manuell analys. Och det är precis här en idé dyker upp i människosläktets kollektiva medvetande: 😁

👉 Tänk om all denna obearbetade information faktiskt kunde göra hela vårt system smartare?

Det var exakt den frågan som Zalandos SRE-team ställde sig när de tittade på sin omfattande samling av data om infrastrukturfel. För att besvara den byggde de en AI-pipeline i flera steg, driven av Large Language Models (LLM:er). Systemet sammanfattade automatiskt tusentals postmortems, identifierade vilka tekniker som var involverade (som AWS S3, DynamoDB eller Postgres), analyserade grundorsakerna och identifierade återkommande felmönster mellan olika system. Det som tidigare kunde kräva veckor av mänskligt arbete kunde nu omvandlas till konkreta och användbara insikter inom några timmar.

![Dead Ends or Data Goldmines - Zalando pipeline 2025](/images/blog/2025-10-11-Dead-Ends-or-Data-Goldmines-Zalando-pipeline.png)

Resultaten var slående: AI:n upptäckte återkommande problemområden — från felkonfigurationer och skalningsproblem till brister i förändringshanteringen — vilket hjälpte företaget att rikta sina investeringar bättre och förebygga liknande incidenter i framtiden.

Även om Zalando betonar att AI inte ersatte mänskligt omdöme (och som människa hoppas jag verkligen att det stämmer!), är det tydligt att AI-drivna system har hjälpt dem mycket — särskilt när vi ser till helheten. Det handlar om skala, noggrannhet, prestanda, tillförlitlighet, underhållbarhet och mycket mer — allt samverkar. 🚀