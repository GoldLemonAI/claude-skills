Stand: 13 november 2026, versie 0.3.0

# AI-zoekgidsen: wat de platforms zelf zeggen

Tien officiële gidsen van Google, Microsoft, Bing, OpenAI, Anthropic en Perplexity. Alle tien gelezen op 13 november 2026, in de laatste versie die de platforms die dag online hadden.

## De rode draad

Alle platforms zeggen hetzelfde: AI-zoeken draait op de gewone zoekindex. Niemand vraagt om speciale bestanden, speciale schema's of speciale opmaak. Google noemt llms.txt, tekst opknippen in stukjes en herschrijven voor AI uitdrukkelijk als overbodig. Microsoft beschrijft dat Copilot een pagina zelf in stukken verdeelt en losse passages kiest. Het werk is dus de basis van SEO/GEO/AEO op orde hebben en schrijven voor mensen, in blokken die ook los van de rest kloppen.

Nieuw in 2026: zowel Google als Bing meten nu apart hoe vaak een site in AI-antwoorden verschijnt, en beide platforms hebben een eigen schakelaar voor deelname aan AI-functies.

## Crawlers in het algemeen

- De crawlers van de platforms zijn standaard toegestaan. Wie niets regelt, is bereikbaar.
- Het advies uit de gidsen is om ze niet te blokkeren. Dat geldt voor robots.txt en ook voor de firewall of de botbeveiliging van de hostingpartij.
- ChatGPT-User, Perplexity-User en Claude-User halen een pagina op omdat een gebruiker daarom vraagt. ChatGPT-User en Perplexity-User kunnen robots.txt negeren.
- Training en gebruik in antwoorden zijn bij de meeste platforms aparte keuzes. Je kunt training weigeren en toch zichtbaar blijven in AI-antwoorden.

## 1. Google: Optimizing your website for generative AI features on Google Search

- Bron: Google Search Central, documentatie (de hoofdgids van Google voor AI Overviews en AI Mode; vervangt in de praktijk "Succeeding in AI search" uit mei 2025)
- URL: https://developers.google.com/search/docs/fundamentals/ai-optimization-guide
- Datum op de gids: bijgewerkt op 10 juli 2026
- Gelezen op 13 november 2026 (laatste versie)

Kernpunten:

- De gewone SEO-basis blijft gelden. De AI-functies van Google draaien op de normale ranking- en kwaliteitssystemen, met grounding (RAG) en query fan-out: het model stelt zelf verwante deelvragen.
- Eigen, niet-inwisselbare inhoud weegt het zwaarst: een eigen invalshoek, eigen ervaring, expertise die verder gaat dan algemene kennis. "7 tips voor..." noemt Google inwisselbaar.
- Orden de tekst voor de lezer, met alinea's, secties en duidelijke koppen. Voeg goede afbeeldingen en video toe waar dat past.
- Maak geen aparte pagina's voor elke variant van een zoekvraag of fan-out-vraag. Google noemt dat misbruik van massaal gemaakte inhoud.
- Technisch: de pagina moet geïndexeerd zijn en in aanmerking komen voor een snippet. Daarnaast moet de site in Search Console zijn opgenomen in de generatieve AI-functies (Instellingen > Search generative AI). Opnemen is de standaard; sinds 31 augustus 2026 heeft elke site deze schakelaar.
- Zorg dat de inhoud te crawlen is, gebruik semantische HTML waar dat kan (perfect hoeft niet), volg de regels voor JavaScript-SEO, zorg voor een goede pagina-ervaring en beperk dubbele inhoud.
- Lokale bedrijven en webwinkels: houd het Bedrijfsprofiel en de Merchant Center-feeds actueel.
- Wat je niet hoeft te doen volgens Google: llms.txt of andere speciale AI-bestanden of opmaak, tekst opknippen in kleine stukjes, herschrijven voor AI, onechte vermeldingen verzamelen, en te veel focus op structured data. Structured data blijft nuttig voor rich results, maar er is geen speciaal schema voor AI.
- Meten: het rapport Generatieve AI-prestaties in Search Console toont vertoningen in AI Overviews en AI Mode per pagina, land, apparaat en datum. Sinds 31 augustus 2026 voor alle sites.
- Agents: browseragents lezen schermafbeeldingen, de DOM en de toegankelijkheidsboom. Google verwijst naar de richtlijnen voor agentvriendelijke websites en noemt het Universal Commerce Protocol als opkomend protocol. Google noemt dit iets voor wie er tijd voor heeft.

## 2. Google: AI features and your website

- Bron: Google Search Central, documentatie
- URL: https://developers.google.com/search/docs/appearance/ai-features
- Datum op de gids: bijgewerkt op 10 december 2025
- Gelezen op 13 november 2026 (laatste versie)
- Let op: de pagina staat op noindex (vastgesteld op 13 november 2026). Google bouwt hem af ten gunste van gids 1. Gebruik hem alleen voor de stuurmiddelen hieronder.

Kernpunten:

- Er zijn geen extra eisen voor AI Overviews of AI Mode. De pagina moet geïndexeerd zijn en in aanmerking komen voor een snippet.
- AI Overviews verschijnen lang niet altijd. Alleen als Google denkt dat ze iets toevoegen.
- Sturen per pagina kan met robots.txt voor Googlebot, nosnippet, data-nosnippet, max-snippet en noindex.
- Google-Extended regelt alleen training en grounding in andere Google-systemen (Gemini). Het heeft geen invloed op Google Zoeken en ook niet op de schakelaar voor AI-functies in Search Console.

## 3. Google: SEO Starter Guide

- Bron: Google Search Central, documentatie
- URL: https://developers.google.com/search/docs/fundamentals/seo-starter-guide
- Datum op de gids: bijgewerkt op 10 december 2025
- Gelezen op 13 november 2026 (laatste versie)

Kernpunten:

- Beschrijvende URL's en mappen per onderwerp.
- Goede linktekst, goede titellinks en goede snippets.
- Alt-tekst bij afbeeldingen; video waar dat past.
- Promotie via social, community en mond-tot-mondreclame.
- Google noemt deze punten uitdrukkelijk als niet van belang: meta keywords, zoekwoorden in de domeinnaam, een vast aantal woorden, een "straf" voor dubbele inhoud, de volgorde van koppen, en E-E-A-T als rankingfactor (Google: "No, it's not").

## 4. Microsoft: Optimizing your content for inclusion in AI search answers

- Bron: Microsoft Advertising Blog, Krishna Madhavan (Bing)
- URL: https://about.ads.microsoft.com/en/blog/post/october-2025/optimizing-your-content-for-inclusion-in-ai-search-answers
- Datum op de gids: 8 oktober 2025
- Gelezen op 13 november 2026 (laatste versie)

Kernpunten:

- Copilot knipt een pagina op in stukken. Die stukken worden beoordeeld en samengevoegd tot één antwoord uit meerdere bronnen.
- Title, meta description en H1 moeten op elkaar aansluiten.
- Schrijf H2 en H3 als echte vragen ("Wat maakt X stiller?") en niet als "Lees meer".
- Vraag-en-antwoordparen kunnen woordelijk worden overgenomen.
- Gebruik lijsten en tabellen voor stappen en vergelijkingen.
- Vermijd lange lappen tekst, antwoorden die verstopt zitten in tabs of uitklapblokken, en kerninformatie die alleen in een pdf of afbeelding staat.
- Concreet wint van vaag: "42 dB" zegt meer dan "stil". Een woord als "innovatief" zegt een AI niets.
- Houd leestekens eenvoudig. Wees voorzichtig met lange gedachtestreepjes en gebruik geen decoratieve symbolen.
- Een bruikbaar fragment is een of twee zinnen lang, staat op zichzelf en klopt ook zonder de rest van de pagina.

## 5. Bing Webmaster Guidelines

- Bron: Bing Webmaster Tools, helpdocumentatie (geldt ook voor Copilot en de grounding API)
- URL: https://www.bing.com/webmasters/help/webmaster-guidelines-30fba23a
- Datum op de gids: de pagina toont geen datum
- Gelezen op 13 november 2026 (laatste versie)

Kernpunten:

- Gebruik IndexNow bij elke nieuwe, gewijzigde of verwijderde pagina. Direct doorgeven werkt beter dan in batches.
- Sitemap met alleen canonieke URL's, een juiste lastmod en ETags.
- Verstop inhoud niet achter client-side rendering.
- NOARCHIVE blokkeert gebruik in Copilot-antwoorden. NOCACHE beperkt Copilot tot URL, titel en snippet. Let op: vanaf 1 maart 2027 leest Bing deze twee niet meer als voorkeur voor training of grounding (zie gids 7).
- Met het attribuut data-snippet geef je aan welke tekst Bing mag citeren.
- Inhoud moet op zichzelf te controleren zijn: feiten uitgeschreven, geen impliciete beweringen.
- Gebruik overal dezelfde namen voor mensen, bedrijf, producten en plaatsen.
- Eén onderwerp per URL. Zet de kern bovenaan, zonder lange inleiding.
- Meet verder dan klikken: vertoningen, citaties en grounding-verwijzingen. Minder klikken betekent niet minder zichtbaarheid.
- Bing noemt als misbruik: zoekwoorden opstapelen om citaties uit te lokken, massaal AI-teksten publiceren zonder controle, en prompt injection gericht op taalmodellen.

## 6. Bing: AI Performance in Bing Webmaster Tools

- Bron: Bing Webmaster Blog, twee berichten van het productteam van Microsoft AI
- URL's: https://blogs.bing.com/webmaster/2026/2/Introducing-AI-Performance-in-Bing-Webmaster-Tools-Public-Preview/ en https://blogs.bing.com/search/2026/6/New-AI-Visibility-Insights-in-Bing-Webmaster-Tools-Intents-Topics-Citation-Share-Compare/
- Datum op de gids: 10 februari 2026 en 16 juni 2026
- Gelezen op 13 november 2026 (laatste versie)

Kernpunten:

- Het rapport AI Performance in Bing Webmaster Tools toont hoe vaak een site als bron wordt genoemd in Copilot, in AI-samenvattingen in Bing en bij een aantal partners: totaal aantal citaties, gemiddeld aantal geciteerde pagina's per dag, citaties per URL, een tijdlijn en de grounding-zoekvragen (een steekproef).
- Sinds juni 2026 (preview, wereldwijd): Intents (soort vraag, zoals informatief, commercieel, lokaal), Topics (zoekvragen gegroepeerd per thema), Citation Share (jouw aandeel in alle citaties bij een grounding-zoekvraag) en Compare (twee periodes naast elkaar).
- Bing noemt Citation Share uitdrukkelijk geen ranking en geen scorebord. Het toont geen concurrenten en geen verkeersaandeel.
- Wat Bing aanraadt om vaker als bron te dienen: diepgang en expertise, duidelijke koppen, tabellen en FAQ-blokken, beweringen onderbouwen met voorbeelden en data, inhoud actueel houden (met IndexNow), en tekst, beeld en video laten kloppen met elkaar.
- Lokale bedrijven: houd adres, openingstijden en contactgegevens actueel in Bing Places for Business.

## 7. Bing: Your content, your choice (training en grounding)

- Bron: Bing Search Blog, Krishna Madhavan
- URL: https://blogs.bing.com/search/2026/10/your-content-your-choice-clearer-preferences-for-training-and-grounding/
- Datum op de gids: 30 oktober 2026
- Gelezen op 13 november 2026 (laatste versie)

Kernpunten:

- Twee losse voorkeuren, allebei standaard Allow: AI Training (voor modeltraining) en AI Grounding (gebruik als bron voor AI-antwoorden in Bing, Copilot en Microsoft 365). Geen van beide verandert iets aan de gewone zoekresultaten van Bing.
- Training voor een hele site of map, in robots.txt (de gedeelde regel uit het IETF-concept aipref):

  ```
  User-Agent: __usage_ai-training
  Disallow: /
  ```

- Training of grounding per pagina, met een meta-tag of een HTTP-header:

  ```
  <meta name="Bingbot" content="ai-training:disallow">
  <meta name="Bingbot" content="ai-grounding:disallow">
  X-Robots-Tag: Bingbot: ai-grounding:disallow
  ```

- `ai-grounding:disallowextended` beperkt grounding tot de eigen diensten van Microsoft (zoals Copilot en AI-samenvattingen) en sluit diensten voor derden uit, zoals Web IQ en de grounding-API in Foundry. Voor grounding bestaat geen regel in robots.txt.
- Bing waarschuwt: Disallow of DisallowExtended voor grounding vermindert de zichtbaarheid in AI-antwoorden aanzienlijk.
- Tijdlijn: vanaf 15 december 2026 een tijdelijke grounding-voorkeur in Webmaster Tools (alleen voor sites die nu NOARCHIVE of NOCACHE gebruiken); vanaf 1 februari 2027 leest Bing de nieuwe voorkeuren bij het crawlen; uiterlijk 1 maart 2027 instellen. Daarna tellen NOARCHIVE en NOCACHE niet meer als voorkeur voor training of grounding. Wie dan niets heeft ingesteld, staat op Allow.
- Een voorkeur werkt pas als Bing de pagina opnieuw heeft gecrawld. IndexNow maakt een nieuwe crawl waarschijnlijker, maar garandeert geen datum.

## 8. OpenAI: Overview of OpenAI crawlers

- Bron: OpenAI, ontwikkelaarsdocumentatie
- URL: https://developers.openai.com/api/docs/bots
- Datum op de gids: de pagina toont geen datum
- Gelezen op 13 november 2026 (laatste versie)

Kernpunten:

| Bot | Doel | Let op |
|---|---|---|
| OAI-SearchBot | Zoekresultaten in ChatGPT | Geblokkeerd betekent: niet getoond in zoekantwoorden van ChatGPT, wel nog als navigatielink. Een wijziging in robots.txt werkt na ongeveer 24 uur door |
| GPTBot | Training | Staat los van OAI-SearchBot |
| ChatGPT-User | Bezoeken op verzoek van een gebruiker | Kan robots.txt negeren; wordt niet gebruikt voor Search |
| OAI-AdsBot | Controleert pagina's die als advertentie in ChatGPT zijn ingediend | Gebruikt de data niet voor training |

- Elke instelling staat los van de andere. Je kunt zoeken toestaan en training weigeren.
- OpenAI raadt aan OAI-SearchBot toe te laten in robots.txt en ook de gepubliceerde IP-adressen niet te blokkeren.

## 9. Anthropic: hoe Claude het web crawlt

- Bron: Claude Help Center, "Does Anthropic crawl data from the web, and how can site owners block the crawler?"
- URL: https://support.claude.com/en/articles/8896518-does-anthropic-crawl-data-from-the-web-and-how-can-site-owners-block-the-crawler
- Datum op de gids: de pagina toont geen paginadatum, maar bevat tekst die gedateerd is op 30 oktober 2026
- Gelezen op 13 november 2026 (laatste versie)

Kernpunten:

| Bot | Doel | Geblokkeerd betekent |
|---|---|---|
| ClaudeBot | Training | Toekomstige inhoud blijft buiten de training |
| Claude-SearchBot | Kwaliteit van de zoekindex | Minder zichtbaarheid in de zoekfunctie van Claude |
| Claude-User | Ophalen op verzoek van een gebruiker | Claude kan de pagina niet ophalen als een gebruiker erom vraagt |

- De bots houden zich aan robots.txt en aan Crawl-delay.
- Blokkeren op IP-adres is geen betrouwbare manier om je af te melden.
- Sinds 30 oktober 2026 herkent Anthropic een machineleesbaar voorkeurssignaal "geen AI-training" (het concept van de IETF-werkgroep aipref, dezelfde regel die Bing gebruikt).
- Een regel in robots.txt die ClaudeBot bij naam noemt, gaat voor op dat signaal.
- Browsers die Claude namens een gebruiker bedient, bijvoorbeeld in Claude Duet, heten Claude-Agent. Die staan op een aparte helppagina en vallen buiten deze drie bots.

## 10. Perplexity: Perplexity crawlers

- Bron: Perplexity, documentatie
- URL: https://docs.perplexity.ai/docs/resources/perplexity-crawlers
- Datum op de gids: de pagina toont geen datum
- Gelezen op 13 november 2026 (laatste versie)

Kernpunten:

- PerplexityBot bouwt de zoekindex en wordt niet gebruikt voor training. Sta deze bot toe in robots.txt als je in de zoekresultaten van Perplexity wilt staan.
- Perplexity-User haalt pagina's op als een gebruiker daarom vraagt en negeert robots.txt meestal.
- Let op de firewall: Cloudflare Bot Fight Mode kan Perplexity nog steeds tegenhouden, ook als er een regel staat die de bot toelaat. Combineer bij een eigen firewallregel de user-agent met de gepubliceerde IP-adressen.
