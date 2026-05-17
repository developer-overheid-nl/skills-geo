<!-- markdownlint-disable MD052 MD034 MD013 -->
# Audit geo — 2026-05-17

> Automatisch gegenereerd door audit-tooling. Niet handmatig bewerken; wijzig SKILL.md / reference.md en regenereer.

## Samenvatting

| Status | Aantal | % |
|--------|--------|---|
| UNSUPPORTED_ASSERTION | 3 | 13% |
| CONTRADICTED | 0 | 0% |
| PARTIALLY_GROUNDED | 9 | 39% |
| UNGROUNDED | 0 | 0% |
| NO_SOURCE | 0 | 0% |
| UNVERIFIABLE | 0 | 0% |
| KNOWN_DISCREPANCY | 0 | 0% |
| GROUNDED | 11 | 48% |

*Geverifieerd met sonnet, 15 calls, $1.0929.*

## UNSUPPORTED_ASSERTION — stellige bewering zonder enige bronsteun (mogelijke hallucinatie) (3)

### `geo-0001` — SKILL.md:22 *(§ Geonovum Geo-standaarden - Overzicht)*

> Geonovum is de Nederlandse organisatie die geo-standaarden ontwikkelt en beheert.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Geonovum organisatie

- **NOT_FOUND** (high) — [https://www.forumstandaardisatie.nl/open-standaarden](https://www.forumstandaardisatie.nl/open-standaarden)
  - *De brontekst betreft de website van Forum Standaardisatie (forumstandaardisatie.nl) en bevat geen informatie over Geonovum of haar rol als beheerder van geo-standaarden.*

### `geo-0002` — SKILL.md:22 *(§ Geonovum Geo-standaarden - Overzicht)*

> De geo-standaarden zijn gepubliceerd op docs.geostandaarden.nl.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Geonovum geo-standaarden publicatie

- **NOT_FOUND** (high) — [https://www.forumstandaardisatie.nl/open-standaarden](https://www.forumstandaardisatie.nl/open-standaarden)
  - *De brontekst bevat geen verwijzing naar docs.geostandaarden.nl of de publicatielocatie van geo-standaarden.*

### `geo-0023` — SKILL.md:85 *(§ Aanvullende Standaarden)*

> IMX-Geo is een semantisch model voor samenhang tussen basis- en kernregistraties, ontwikkeld door Kadaster en Geonovum.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** IMX-Geo standaard

<details><summary>4x NOT_FOUND (klap uit)</summary>

- **NOT_FOUND** (high) — [https://developer.kadaster.nl/](https://developer.kadaster.nl/)
  - *IMX-Geo, semantische modellen of een samenwerking met Geonovum worden in de brontekst niet vermeld.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/rwgs/rw](https://docs.geostandaarden.nl/rwgs/rw)
  - *IMX-Geo wordt nergens in de brontekst genoemd. De bron vermeldt wel Kadaster en Geonovum als organisaties, maar niet in relatie tot een IMX-Geo semantisch model voor samenhang tussen basis- en kernregistraties.*
- **NOT_FOUND** (high) — [https://www.geonovum.nl/geo-standaarden/geopackage](https://www.geonovum.nl/geo-standaarden/geopackage)
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/nl-sbb/nl-sbb](https://docs.geostandaarden.nl/nl-sbb/nl-sbb)
  - *IMX-Geo wordt nergens in deze brontekst genoemd. De bron gaat uitsluitend over NL-SBB. Kadaster wordt wel als organisatie van auteurs vermeld (Jesse Bakker, Arjen Santema), maar IMX-Geo als semantisch model voor basis- en kernregistraties wordt niet behandeld.*
</details>

## PARTIALLY_GROUNDED — bron ondersteunt deel van de claim (9)

### `geo-0012` — SKILL.md:60 *(§ Sleutelorganisaties)*

> PDOK (Publieke Dienstverlening Op de Kaart) is het nationale geo-dataportaal en host geo-services.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** PDOK organisatie

- **PARTIALLY_SUPPORTED** (medium) — [https://www.pdok.nl/how-to-faq](https://www.pdok.nl/how-to-faq)
  > Open geodata portaal Open overheidsdata [...] Iedereen mag kosteloos data afnemen bij PDOK. [...] Via PDOK kunnen diverse datasets worden "gedownload". [...] Uitleg over de belangrijkste OGC standaarden die in gebruik zijn bij PDOK staat op https://www.pdok.nl/services-en-api-s
  - *De bron bevestigt dat PDOK een open geodataportaal is dat geo-services en datasets aanbiedt. De uitbreiding 'Publieke Dienstverlening Op de Kaart' en de kwalificatie 'nationaal' worden niet expliciet vermeld in de brontekst.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/](https://docs.geostandaarden.nl/)
  - *De brontekst is een inhoudsopgave van Geonovum-documentatie en bevat geen informatie over PDOK of haar rol als nationaal geo-dataportaal.*
- **NOT_FOUND** (high) — [https://www.geonovum.nl/geo-standaarden](https://www.geonovum.nl/geo-standaarden)
  - *De brontekst gaat over geo-standaarden die Geonovum beheert. PDOK wordt nergens in de tekst genoemd.*

### `geo-0013` — SKILL.md:61 *(§ Sleutelorganisaties)*

> Het Kadaster beheert de basisregistraties BAG en BRK, beheert PDOK, en de Landelijke Voorziening BGT.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Kadaster organisatie

- **PARTIALLY_SUPPORTED** (low) — [https://www.geonovum.nl/geo-standaarden](https://www.geonovum.nl/geo-standaarden)
  > "In de verschillende registraties die de overheid beheert, is veel praktische basisinformatie te vinden. [...] werken Kadaster en Geonovum samen aan een semantisch samenhangend model." en "Het ministerie van VRO, Kadaster en Geonovum, werken vanuit het programma Zicht op Nederland Datafundament (ZoN DF) aan een Informatiemodel Bestuurlijke Gebieden"
  - *De bron noemt Kadaster als samenwerkingspartner bij IMX-Geo en Informatiemodel Bestuurlijke Gebieden, maar vermeldt niets over BAG, BRK, PDOK-beheer, of de Landelijke Voorziening BGT. Het grootste deel van de claim is niet te verifiëren op basis van deze bron.*
<details><summary>3x NOT_FOUND (klap uit)</summary>

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/](https://docs.geostandaarden.nl/)
  - *De brontekst bevat geen informatie over het Kadaster, BAG, BRK, PDOK-beheer of de Landelijke Voorziening BGT.*
- **NOT_FOUND** (high) — [https://www.pdok.nl/how-to-faq](https://www.pdok.nl/how-to-faq)
  - *De brontekst vermeldt het Kadaster alleen in de context van de Kadastrale kaart en oppervlakteberekeningen. Er staat niets over BAG, BRK, beheer van PDOK door het Kadaster, of de Landelijke Voorziening BGT.*
- **NOT_FOUND** (high) — [https://developer.kadaster.nl/](https://developer.kadaster.nl/)
  - *De brontekst is de homepage van developer.kadaster.nl en noemt geen specifieke basisregistraties (BAG, BRK), PDOK-beheer of Landelijke Voorziening BGT. Alleen een algemene verwijzing naar 'datasets' en 'PDOK.nl' staat in de tekst.*
</details>

### `geo-0015` — SKILL.md:70 *(§ Belangrijke Repositories)*

> De Geonovum/NEN3610-Linkeddata repository bevat het NEN 3610 linked data profiel en heeft de CC-BY-4.0 licentie.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** NEN3610-Linkeddata repository

- **PARTIALLY_SUPPORTED** (medium) — [https://github.com/Geonovum/NEN3610-Linkeddata](https://github.com/Geonovum/NEN3610-Linkeddata)
  > Repository voor het werken aan een linked data profiel op NEN3610. Dit profiel wordt beschreven in een document.
  - *De bron bevestigt dat de repository het NEN3610 linked data profiel bevat. Er is echter geen vermelding van de CC-BY-4.0 licentie in de aangeleverde brontekst.*

### `geo-0016` — SKILL.md:71 *(§ Belangrijke Repositories)*

> De Geonovum/Metadata-ISO19115 repository bevat het Nederlands profiel ISO 19115 metadata en heeft de CC-BY-4.0 licentie.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Metadata-ISO19115 repository

- **PARTIALLY_SUPPORTED** (medium) — [https://github.com/Geonovum/Metadata-ISO19115](https://github.com/Geonovum/Metadata-ISO19115)
  > Werkversie Nederlands profiel op ISO 19115 voor geografie versie 2.X.X
  - *De bron bevestigt dat de repository het Nederlands profiel op ISO 19115 bevat. De CC-BY-4.0 licentie wordt nergens in de aangeleverde brontekst vermeld.*

### `geo-0017` — SKILL.md:72 *(§ Belangrijke Repositories)*

> De Geonovum/inspire-handreiking repository bevat de INSPIRE implementatie handreiking en heeft de CC-BY-ND-4.0 licentie.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** inspire-handreiking repository

- **PARTIALLY_SUPPORTED** (medium) — [https://github.com/Geonovum/inspire-handreiking](https://github.com/Geonovum/inspire-handreiking)
  > INSPIRE-handreiking Welkom op de INSPIRE-handreiking. De werkversie van de handreiking kan benaderd worden via: https://geonovum.github.io/inspire-handreiking/
  - *De bron bevestigt dat de repository de INSPIRE implementatie handreiking bevat. De licentie (CC-BY-ND-4.0) wordt nergens in de aangeleverde brontekst vermeld.*

### `geo-0018` — SKILL.md:73 *(§ Belangrijke Repositories)*

> De Geonovum/IMGeo repository bevat het Informatiemodel Geografie (BGT/IMGeo) en heeft de CC-BY-4.0 licentie.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** IMGeo repository

- **PARTIALLY_SUPPORTED** (medium) — [https://github.com/Geonovum/IMGeo](https://github.com/Geonovum/IMGeo)
  > Geonovum / IMGeo Public ... About IMGeo volgens mappenstructuur op register.geostandaarden.nl
  - *De bron bevestigt dat het een IMGeo repository van Geonovum betreft met mappen zoals 'informatiemodel', 'praktijkrichtlijn', etc., wat overeenkomt met het Informatiemodel Geografie (BGT/IMGeo). De CC-BY-4.0 licentie wordt nergens in de aangeleverde brontekst vermeld.*

### `geo-0019` — SKILL.md:74 *(§ Belangrijke Repositories)*

> De Geonovum/MIM-Werkomgeving repository bevat het Metamodel Informatie Modellering en heeft de CC-BY-4.0 licentie.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** MIM-Werkomgeving repository

- **PARTIALLY_SUPPORTED** (high) — [https://github.com/Geonovum/MIM-Werkomgeving](https://github.com/Geonovum/MIM-Werkomgeving)
  > Dit is de repository van het Metamodel Informatie Modellering (MIM). Hierin staat de werkversie van het MIM.
  - *De bron bevestigt dat de repository het Metamodel Informatie Modellering bevat. De CC-BY-4.0 licentie wordt nergens in de aangeleverde brontekst vermeld.*

### `geo-0020` — SKILL.md:83 *(§ Aanvullende Standaarden)*

> GeoPackage is een verplicht formaat voor geodata-downloads bij de overheid sinds 2019.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** GeoPackage standaard overheid

- **PARTIALLY_SUPPORTED** (high) — [https://www.geonovum.nl/geo-standaarden/geopackage](https://www.geonovum.nl/geo-standaarden/geopackage)
  > In 2019 is deze standaard opgenomen op de Nederlandse Pas-toe-of-leg-uit-lijst. Dit betekent dat Nederlandse overheidsorganisaties bij het aanbieden van een download van hun data naast GML ook het GeoPackage formaat moeten kunnen leveren.
  - *De bron bevestigt dat GeoPackage verplicht is sinds 2019, maar het is geen vervanging van GML: overheidsorganisaties moeten GeoPackage naast GML aanbieden, niet in plaats daarvan. 'Verplicht formaat' dekt de lading dus niet volledig; het is een aanvullende verplichting.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/rwgs/rw](https://docs.geostandaarden.nl/rwgs/rw)
  - *De bron vermeldt GeoPackage als uitwisselformaat-standaard (tabel 6.1) maar er staat nergens dat het een verplicht formaat is voor geodata-downloads bij de overheid, noch een datum van 2019. GeoPackage staat niet op de 'pas toe of leg uit' lijst volgens de brontekst.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/nl-sbb/nl-sbb](https://docs.geostandaarden.nl/nl-sbb/nl-sbb)
  - *De brontekst gaat volledig over NL-SBB (standaard voor het beschrijven van begrippen). GeoPackage, geodata-downloads of verplichte formaten worden nergens genoemd.*

### `geo-0021` — SKILL.md:82 *(§ Aanvullende Standaarden)*

> Het Raamwerk Geo-Standaarden is een overzichtsdocument dat beschrijft hoe alle geo-standaarden samenhangen, gepubliceerd op docs.geostandaarden.nl/rwgs/rw/.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Raamwerk Geo-Standaarden

- **PARTIALLY_SUPPORTED** (medium) — [https://docs.geostandaarden.nl/rwgs/rw](https://docs.geostandaarden.nl/rwgs/rw)
  > Het Raamwerk van geostandaarden is richtinggevend voor het gebruik van standaarden binnen de Nederlandse geo-informatie infrastructuur. [...] Het benoemt de internationale en nationale standaarden die voor Nederland binnen het geo-domein van toepassing zijn voor aansluiting met andere domeinen.
  - *De bron bevestigt dat het Raamwerk een overzichtsdocument is dat samenhang van geostandaarden beschrijft. De URL docs.geostandaarden.nl/rwgs/rw/ is vermeld als 'Laatst gepubliceerde versie' in de header. De omschrijving 'hoe alle geo-standaarden samenhangen' is een juiste parafrase. Volledig ondersteund op inhoud, URL alleen impliciet aanwezig als metadata van het document zelf.*
- **NOT_FOUND** (high) — [https://www.geonovum.nl/geo-standaarden/geopackage](https://www.geonovum.nl/geo-standaarden/geopackage)
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/nl-sbb/nl-sbb](https://docs.geostandaarden.nl/nl-sbb/nl-sbb)
  - *Het Raamwerk Geo-Standaarden wordt niet genoemd in deze brontekst. De bron gaat uitsluitend over NL-SBB.*

## GROUNDED — minstens één bron ondersteunt de claim (11)

<details>
<summary>Klap uit voor alle GROUNDED claims</summary>

### `geo-0003` — SKILL.md:26 *(§ Forum Standaardisatie Status)*

> De geo-standaarden staan op de 'pas-toe-of-leg-uit'-lijst van het Forum Standaardisatie.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Forum Standaardisatie status geo-standaarden

- **SUPPORTED** (high) — [https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden](https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden)
  > De Geo-standaarden op de 'Pas toe of leg uit'-lijst van het Forum Standaardisatie bestaan thans uit: Nederlands metadataprofiel op ISO 19115 voor geografie, versie 2.1.0 [...] NEN 3610:2022 [...] ISO 19136:2007 [...] GeoPackage 1.3.1 [...] OGC-API – Features Part 1 [...] OGC-API – Tiles - Part 1: Core

### `geo-0004` — SKILL.md:26 *(§ Forum Standaardisatie Status)*

> Sinds september 2024 is de samenstelling van de geo-standaarden op de pas-toe-of-leg-uit-lijst gewijzigd.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Forum Standaardisatie status geo-standaarden

- **SUPPORTED** (high) — [https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden](https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden)
  > Op 19 september 2024 stemde het OBDO in met het verplichten van OGC-API – Features Part 1: Core en Part 2: Coordinate Reference Systems by Reference en OGC-API – Tiles - Part 1: Core door plaatsing op de 'pas toe of leg uit'-lijst en het aanbevelen van Nederlands WFS profiel 1.1 [...] en Nederlands profiel op ISO 19128 [...] (WMS) door plaatsing op de lijst aanbevolen standaarden.

### `geo-0005` — SKILL.md:32 *(§ Forum Standaardisatie Status)*

> GML is verplicht (pas-toe-of-leg-uit) als data-encoding standaard onderdeel van het Geo-Standaarden-pakket.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Forum Standaardisatie verplichte geo-standaarden

- **SUPPORTED** (high) — [https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden](https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden)
  > ISO 19136:2007 Geographic information - Geography Markup Language (GML), versie 2007 (geen specifiek toepassingsgebied)
  - *GML (ISO 19136:2007) staat expliciet op de 'pas toe of leg uit'-lijst. Dat er geen specifiek toepassingsgebied wordt vermeld is opvallend, maar de opname op de lijst is duidelijk.*

### `geo-0006` — SKILL.md:33 *(§ Forum Standaardisatie Status)*

> OGC API Features is verplicht (pas-toe-of-leg-uit) als REST API service onderdeel van het Geo-Standaarden-pakket.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Forum Standaardisatie verplichte geo-standaarden

- **SUPPORTED** (high) — [https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden](https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden)
  > OGC-API – Features Part 1: Core en Part 2: Coordinate Reference Systems by Reference (specifiek toepassingsgebied: OGC-API - Features Part 1 en Part 2 moeten worden toegepast bij het per REST API aanbieden voor derden van geografische object-informatie)

### `geo-0007` — SKILL.md:34 *(§ Forum Standaardisatie Status)*

> OGC API Tiles is verplicht (pas-toe-of-leg-uit) als tileservice onderdeel van het Geo-Standaarden-pakket.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Forum Standaardisatie verplichte geo-standaarden

- **SUPPORTED** (high) — [https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden](https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden)
  > OGC-API – Tiles - Part 1: Core (specifiek toepassingsgebied : OGC-API – OGC-API – Tiles Part 1 moet worden toegepast bij het per REST API aanbieden voor derden van geografische informatie als verbeelding)

### `geo-0008` — SKILL.md:35 *(§ Forum Standaardisatie Status)*

> NEN 3610 is verplicht (pas-toe-of-leg-uit) als informatiemodel onderdeel van het Geo-Standaarden-pakket.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Forum Standaardisatie verplichte geo-standaarden

- **SUPPORTED** (high) — [https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden](https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden)
  > NEN 3610:2022 (nl) Basismodel Geo-informatie - Termen, definities, relaties en algemene regels voor de uitwisseling van informatie over aan de aarde gerelateerde ruimtelijke objecten, versie 2022 (specifiek toepassingsgebied : metadatering van geografische datasets en dataset series)

### `geo-0009` — SKILL.md:36 *(§ Forum Standaardisatie Status)*

> ISO 19115/19119 is verplicht (pas-toe-of-leg-uit) als metadata standaard onderdeel van het Geo-Standaarden-pakket.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Forum Standaardisatie verplichte geo-standaarden

- **SUPPORTED** (high) — [https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden](https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden)
  > Nederlands metadataprofiel op ISO 19115 voor geografie, versie 2.1.0 (specifiek toepassingsgebied : metadatering van geografische datasets en dataset series) Nederlands metadata profiel op ISO 19119 voor services, versie 2.1.0 (specifiek toepassingsgebied : metadatering van geografische informatie services)

### `geo-0010` — SKILL.md:38 *(§ Forum Standaardisatie Status)*

> WMS is sinds september 2024 verplaatst van verplicht naar aanbevolen als viewservice.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Forum Standaardisatie status WMS

- **SUPPORTED** (high) — [https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden](https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden)
  > Op 19 september 2024 stemde het OBDO in met [...] het aanbevelen van [...] Nederlands profiel op ISO 19128 Geographic information - Web Map Server Interface (WMS) door plaatsing op de lijst aanbevolen standaarden.
  - *De bron bevestigt dat WMS naar 'aanbevolen' is gegaan per september 2024. Dat het eerder verplicht was staat niet expliciet in deze tekst, maar de verplaatsing naar aanbevolen is duidelijk.*

### `geo-0011` — SKILL.md:38 *(§ Forum Standaardisatie Status)*

> WFS is sinds september 2024 verplaatst van verplicht naar aanbevolen als downloadservice.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Forum Standaardisatie status WFS

- **SUPPORTED** (high) — [https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden](https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden)
  > Op 19 september 2024 stemde het OBDO in met [...] het aanbevelen van Nederlands WFS profiel 1.1 op ISO 19142 voor Web Feature Services 2.0, versie 1.1 (WFS) [...] door plaatsing op de lijst aanbevolen standaarden.
  - *De bron bevestigt dat WFS naar 'aanbevolen' is gegaan per september 2024. Dat het eerder verplicht was staat niet expliciet in deze tekst, maar de verplaatsing naar aanbevolen is duidelijk.*

### `geo-0014` — SKILL.md:69 *(§ Belangrijke Repositories)*

> De Geonovum/ogc-checker repository is een validatietool voor OGC services en heeft de EUPL-1.2 licentie.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** ogc-checker repository

- **SUPPORTED** (high) — [https://github.com/Geonovum/ogc-checker](https://github.com/Geonovum/ogc-checker)
  > Validates JSON-FG documents and OGC API endpoints against OGC specifications. [...] License EUPL-1.2

### `geo-0022` — SKILL.md:84 *(§ Aanvullende Standaarden)*

> NL-SBB is een standaard voor het beschrijven van begrippen, gepubliceerd op docs.geostandaarden.nl/nl-sbb/nl-sbb/.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** NL-SBB standaard

- **SUPPORTED** (high) — [https://docs.geostandaarden.nl/rwgs/rw](https://docs.geostandaarden.nl/rwgs/rw)
  > Standaard voor het Beschrijven van Begrippen [ SBB ] [...] URL: https://docs.geostandaarden.nl/nl-sbb/nl-sbb/
  - *De bron vermeldt SBB (Standaard voor het Beschrijven van Begrippen) meerdere malen en geeft exact de URL docs.geostandaarden.nl/nl-sbb/nl-sbb/ in de referenties. De claim gebruikt de naam 'NL-SBB' terwijl de bron 'SBB' of 'NL-SBB' gebruikt; dit is dezelfde standaard.*
- **SUPPORTED** (high) — [https://docs.geostandaarden.nl/nl-sbb/nl-sbb](https://docs.geostandaarden.nl/nl-sbb/nl-sbb)
  > NL-SBB - Standaard voor het beschrijven van begrippen Geonovum Standaard Vastgestelde versie 10 oktober 2024 [...] Deze versie: https://docs.geostandaarden.nl/nl-sbb/def-st-nl-sbb-20241010 Laatst gepubliceerde versie: https://docs.geostandaarden.nl/nl-sbb/nl-sbb/
  - *De bron bevestigt expliciet dat NL-SBB een standaard is voor het beschrijven van begrippen, gepubliceerd op docs.geostandaarden.nl/nl-sbb/nl-sbb/.*
- **NOT_FOUND** (high) — [https://www.geonovum.nl/geo-standaarden/geopackage](https://www.geonovum.nl/geo-standaarden/geopackage)

</details>
