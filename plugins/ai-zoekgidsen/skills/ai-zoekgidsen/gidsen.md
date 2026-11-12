Stand: 12 november 2026, versie 0.1.0

# AI-zoekgidsen: wat de platforms zelf zeggen

Acht officiële gidsen van Google, Microsoft, Bing, OpenAI, Anthropic en Perplexity. Alle acht gelezen op 2 november 2026 en gecontroleerd op 12 november 2026.

## De rode draad

Alle platforms zeggen hetzelfde: AI-zoeken draait op de gewone zoekindex. Niemand vraagt om speciale bestanden, speciale schema's of speciale opmaak. Wat wel verandert is de eenheid die gekozen wordt: AI kiest passages, geen hele pagina's. Het werk is dus de basis van SEO/GEO/AEO op orde hebben en schrijven in blokken die op zichzelf staan en los te gebruiken zijn.

## Crawlers in het algemeen

- De crawlers van de platforms zijn standaard toegestaan. Wie niets regelt, is bereikbaar.
- Het advies uit de gidsen is om ze niet te blokkeren. Dat geldt voor robots.txt en ook voor de firewall of de botbeveiliging van de hostingpartij.
- ChatGPT-User en Perplexity-User halen een pagina op omdat een gebruiker daarom vraagt. Deze twee kunnen robots.txt negeren.

## 1. Google: AI features and your website

- Bron: Google Search Central, documentatie
- URL: https://developers.google.com/search/docs/appearance/ai-features
- Datum op de gids: bijgewerkt op 10 december 2025
- Gelezen op 2 november 2026, gecontroleerd op 12 november 2026

Kernpunten:

- Er zijn geen extra eisen voor AI Overviews of AI Mode. De pagina moet geïndexeerd zijn en in aanmerking komen voor een snippet.
- Google zegt uitdrukkelijk dat speciale AI-tekstbestanden, speciale opmaak en speciale schema's niet nodig zijn.
- AI Mode en AI Overviews werken met query fan-out: Google stelt veel verwante deelvragen en toont daardoor meer en meer verschillende links.
- AI Overviews verschijnen lang niet altijd. Alleen als Google denkt dat ze iets toevoegen.
- Verkeer uit AI-functies zit in Search Console, in het rapport Prestaties, zoektype "Web". Er is geen apart filter.
- Google stelt dat klikken vanaf pagina's met een AI Overview van hogere kwaliteit zijn (meer tijd op de site).
- Sturen kan met robots.txt voor Googlebot, nosnippet, data-nosnippet, max-snippet en noindex.
- Google-Extended regelt alleen training en grounding in andere Google-systemen (Gemini). Het heeft geen invloed op Google Zoeken.

## 2. Google: Succeeding in AI search

- Bron: Google Search Central Blog, John Mueller
- URL: https://developers.google.com/search/blog/2025/05/succeeding-in-ai-search
- Datum op de gids: 21 mei 2025
- Gelezen op 2 november 2026, gecontroleerd op 12 november 2026

Kernpunten:

- Maak unieke inhoud die niet overal al te vinden is. Gebruikers stellen langere, specifiekere vragen en vervolgvragen.
- Zorg voor een goede pagina-ervaring.
- De pagina moet te crawlen zijn: HTTP 200 en Googlebot niet geblokkeerd.
- Structured data moet overeenkomen met de zichtbare tekst.
- Denk multimodaal: goede afbeeldingen en video, een actueel Merchant Center en een actueel Bedrijfsprofiel.
- Beoordeel het resultaat op conversies en betrokkenheid, niet alleen op klikken.

## 3. Google: SEO Starter Guide

- Bron: Google Search Central, documentatie
- URL: https://developers.google.com/search/docs/fundamentals/seo-starter-guide
- Datum op de gids: bijgewerkt op 10 december 2025
- Gelezen op 2 november 2026, gecontroleerd op 12 november 2026

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
- Gelezen op 2 november 2026, gecontroleerd op 12 november 2026

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
- Gelezen op 2 november 2026, gecontroleerd op 12 november 2026

Kernpunten:

- Gebruik IndexNow bij elke nieuwe, gewijzigde of verwijderde pagina. Direct doorgeven werkt beter dan in batches.
- Sitemap met alleen canonieke URL's, een juiste lastmod en ETags.
- Verstop inhoud niet achter client-side rendering.
- NOARCHIVE blokkeert gebruik in Copilot-antwoorden. NOCACHE beperkt Copilot tot URL, titel en snippet.
- Met het attribuut data-snippet geef je aan welke tekst Bing mag citeren.
- Inhoud moet op zichzelf te controleren zijn: feiten uitgeschreven, geen impliciete beweringen.
- Gebruik overal dezelfde namen voor mensen, bedrijf, producten en plaatsen.
- Eén onderwerp per URL. Zet de kern bovenaan, zonder lange inleiding.
- Meet verder dan klikken: vertoningen, citaties en grounding-verwijzingen. Minder klikken betekent niet minder zichtbaarheid.
- Bing noemt als misbruik: zoekwoorden opstapelen om citaties uit te lokken, massaal AI-teksten publiceren zonder controle, en prompt injection gericht op taalmodellen.

## 6. OpenAI: Overview of OpenAI crawlers

- Bron: OpenAI, ontwikkelaarsdocumentatie
- URL: https://developers.openai.com/api/docs/bots
- Datum op de gids: de pagina toont geen datum
- Gelezen op 2 november 2026, gecontroleerd op 12 november 2026

Kernpunten:

| Bot | Doel | Let op |
|---|---|---|
| OAI-SearchBot | Zoekresultaten in ChatGPT | Geblokkeerd betekent: niet getoond in zoekantwoorden van ChatGPT. Een wijziging in robots.txt werkt na ongeveer 24 uur door |
| GPTBot | Training | Staat los van OAI-SearchBot |
| ChatGPT-User | Bezoeken op verzoek van een gebruiker | Kan robots.txt negeren; wordt niet gebruikt voor Search |
| OAI-AdsBot | Controleert pagina's die als advertentie in ChatGPT zijn ingediend | Nieuw |

- Elke instelling staat los van de andere. Je kunt zoeken toestaan en training weigeren.

## 7. Anthropic: hoe Claude het web crawlt

- Bron: Claude Help Center, "Does Anthropic crawl data from the web, and how can site owners block the crawler?"
- URL: https://support.claude.com/en/articles/8896518-does-anthropic-crawl-data-from-the-web-and-how-can-site-owners-block-the-crawler
- Datum op de gids: de pagina toont geen paginadatum, maar bevat tekst die gedateerd is op 30 oktober 2026
- Gelezen op 2 november 2026, gecontroleerd op 12 november 2026

Kernpunten:

| Bot | Doel | Geblokkeerd betekent |
|---|---|---|
| ClaudeBot | Training | Toekomstige inhoud blijft buiten de training |
| Claude-SearchBot | Kwaliteit van de zoekindex | Minder zichtbaarheid in de zoekfunctie van Claude |
| Claude-User | Ophalen op verzoek van een gebruiker | Claude kan de pagina niet ophalen als een gebruiker erom vraagt |

- De bots houden zich aan robots.txt en aan Crawl-delay.
- Blokkeren op IP-adres is geen betrouwbare manier om je af te melden.
- Sinds 30 oktober 2026 herkent Anthropic een machineleesbaar voorkeurssignaal "geen AI-training" (het concept van de IETF-werkgroep aipref).
- Een regel in robots.txt die ClaudeBot bij naam noemt, gaat voor op dat signaal.

## 8. Perplexity: Perplexity crawlers

- Bron: Perplexity, documentatie
- URL: https://docs.perplexity.ai/docs/resources/perplexity-crawlers
- Datum op de gids: de pagina toont geen datum
- Gelezen op 2 november 2026, gecontroleerd op 12 november 2026

Kernpunten:

- PerplexityBot bouwt de zoekindex en wordt niet gebruikt voor training. Sta deze bot toe in robots.txt als je in de zoekresultaten van Perplexity wilt staan.
- Perplexity-User haalt pagina's op als een gebruiker daarom vraagt en kan robots.txt negeren.
- Let op de firewall: Cloudflare Bot Fight Mode kan Perplexity nog steeds tegenhouden, ook als er een regel staat die de bot toelaat.
