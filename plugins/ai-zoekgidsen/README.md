# AI-zoekgidsen

Een plugin voor Claude Code van Gold Lemon. Versie 0.1.0, kennis met stand 12 november 2026.

## Wat het doet

De plugin bevat één skill. Die toetst een webpagina of een stuk tekst aan wat acht officiële gidsen zeggen over AI-zoeken: drie van Google, en één van Microsoft, Bing, OpenAI, Anthropic en Perplexity.

Je krijgt:

- de datum van de gebruikte kennis, met een waarschuwing als die ouder is dan drie maanden;
- per gids een oordeel: in orde, niet in orde of niet te controleren;
- maximaal tien concrete verbeterpunten, elk met de gids waar het uit komt.

De skill belooft geen posities en geen citaten in AI-antwoorden. De gidsen beschrijven voorwaarden, geen garanties.

De skill probeert eerst de actuele kennis op te halen van `https://goldlemon.nl/skills/ai-zoekgidsen/kennis/`. Lukt dat niet, dan gebruikt hij het meegeleverde bestand `gidsen.md`.

## Installeren in drie stappen

Typ deze commando's in een sessie van Claude Code.

1. Voeg de marketplace toe:

   ```
   /plugin marketplace add GoldLemonAI/claude-skills
   ```

2. Installeer de plugin en kies in het venster dat opent voor wie je hem installeert:

   ```
   /plugin install ai-zoekgidsen@goldlemon
   ```

3. Gebruik de skill met een URL of een stuk tekst:

   ```
   /ai-zoekgidsen:ai-zoekgidsen https://voorbeeld.nl/pagina/
   ```

   Zie je de skill nog niet, typ dan eerst `/reload-plugins`.

Liever vanuit de gewone terminal, zonder sessie? Dan zijn stap 1 en 2:

```
claude plugin marketplace add GoldLemonAI/claude-skills
claude plugin install ai-zoekgidsen@goldlemon
```

## Bijwerken

Automatisch bijwerken staat voor deze marketplace standaard uit. Werk zo bij vanuit de terminal:

```
claude plugin marketplace update goldlemon
claude plugin update ai-zoekgidsen@goldlemon
```

In een sessie kan het ook: typ `/plugin`, ga naar het tabblad Marketplaces, kies `goldlemon` en daarna Update marketplace. Wil je dat het voortaan vanzelf gaat, kies daar dan Enable auto-update.

Na een update typ je `/reload-plugins` of start je een nieuwe sessie.

## Mappen

```
.claude-plugin/marketplace.json
plugins/ai-zoekgidsen/.claude-plugin/plugin.json
plugins/ai-zoekgidsen/skills/ai-zoekgidsen/SKILL.md
plugins/ai-zoekgidsen/skills/ai-zoekgidsen/gidsen.md
README.md
```

## Wijzigingen

- 12 november 2026: kennis gecontroleerd en bijgewerkt, stand 12 november 2026. Datums van de gidsen aangevuld, het voorkeurssignaal "geen AI-training" van Anthropic toegevoegd (30 oktober 2026) en een algemeen deel over crawlers toegevoegd.
- 0.1.0 (12 november 2026): eerste versie. Eén skill, kennis uit acht officiële gidsen, gelezen op 2 november 2026.
