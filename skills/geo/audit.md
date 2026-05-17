<!-- markdownlint-disable MD052 MD034 MD013 MD038 -->
# Audit geo — 2026-05-17

> Automatisch gegenereerd door audit-tooling. Niet handmatig bewerken; wijzig SKILL.md / reference.md en regenereer.

## Samenvatting

| Status | Aantal | % |
|--------|--------|---|
| UNSUPPORTED_ASSERTION | 3 | 14% |
| CONTRADICTED | 0 | 0% |
| PARTIALLY_GROUNDED | 8 | 36% |
| UNGROUNDED | 0 | 0% |
| NO_SOURCE | 0 | 0% |
| UNVERIFIABLE | 0 | 0% |
| KNOWN_DISCREPANCY | 0 | 0% |
| GROUNDED | 11 | 50% |

*Geverifieerd met sonnet, 16 calls, $1.1593.*

## UNSUPPORTED_ASSERTION — stellige bewering zonder enige bronsteun (mogelijke hallucinatie) (3)

### `geo-0001` — SKILL.md:22 *(§ Geonovum Geo-standaarden - Overzicht)*

> Geonovum is de Nederlandse organisatie die geo-standaarden ontwikkelt en beheert.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Geonovum organisatie

- **NOT_FOUND** (high) — [https://www.forumstandaardisatie.nl/open-standaarden](https://www.forumstandaardisatie.nl/open-standaarden)
  - *De brontekst betreft de website van Forum Standaardisatie en bevat geen informatie over Geonovum als organisatie of haar rol bij het ontwikkelen van geo-standaarden.*

### `geo-0002` — SKILL.md:22 *(§ Geonovum Geo-standaarden - Overzicht)*

> De geo-standaarden zijn gepubliceerd op docs.geostandaarden.nl.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Geonovum geo-standaarden publicatie

- **NOT_FOUND** (high) — [https://www.forumstandaardisatie.nl/open-standaarden](https://www.forumstandaardisatie.nl/open-standaarden)
  - *De brontekst bevat geen vermelding van docs.geostandaarden.nl of de publicatielocatie van geo-standaarden.*

### `geo-0015` — SKILL.md:85 *(§ Aanvullende Standaarden)*

> IMX-Geo is een semantisch model voor samenhang tussen basis- en kernregistraties, ontwikkeld door Kadaster en Geonovum.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** IMX-Geo standaard

<details><summary>4x NOT_FOUND (klap uit)</summary>

- **NOT_FOUND** (high) — [https://developer.kadaster.nl/](https://developer.kadaster.nl/)
  - *IMX-Geo, semantisch model, samenhang tussen registraties, en Geonovum worden nergens in de brontekst genoemd.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/rwgs/rw](https://docs.geostandaarden.nl/rwgs/rw)
  - *IMX-Geo wordt in de brontekst niet genoemd. De bron behandelt NEN 3610, MIM, sectorale informatiemodellen en basisregistraties, maar IMX-Geo als semantisch model voor samenhang tussen basis- en kernregistraties komt niet voor.*
- **NOT_FOUND** (high) — [https://www.geonovum.nl/geo-standaarden/geopackage](https://www.geonovum.nl/geo-standaarden/geopackage)
  - *De brontekst gaat uitsluitend over GeoPackage. IMX-Geo wordt nergens genoemd.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/nl-sbb/nl-sbb](https://docs.geostandaarden.nl/nl-sbb/nl-sbb)
  - *De bron gaat over NL-SBB en bevat geen informatie over IMX-Geo, Kadaster als ontwikkelaar van een semantisch model voor basis- en kernregistraties in die context.*
</details>

## PARTIALLY_GROUNDED — bron ondersteunt deel van de claim (8)

### `geo-0005` — SKILL.md:32 *(§ Forum Standaardisatie Status)*

> GML is verplicht (pas-toe-of-leg-uit) als data-encoding standaard onderdeel van het Geo-Standaarden-pakket.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Forum Standaardisatie verplichte geo-standaarden

- **PARTIALLY_SUPPORTED** (medium) — [https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden](https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden)
  > ISO 19136:2007 Geographic information - Geography Markup Language (GML), versie 2007 (geen specifiek toepassingsgebied)
  - *GML staat inderdaad op de pas-toe-of-leg-uit-lijst, maar de bron vermeldt expliciet 'geen specifiek toepassingsgebied' — de omschrijving 'data-encoding standaard' staat niet in de bron. Bovendien noemt de bron dat 'uitstekend beheer' niet van toepassing is op GML, wat de claim niet tegenspreekt maar wel nuanceert.*

### `geo-0012` — SKILL.md:60 *(§ Sleutelorganisaties)*

> PDOK (Publieke Dienstverlening Op de Kaart) is het nationale geo-dataportaal en host geo-services.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** PDOK organisatie

- **PARTIALLY_SUPPORTED** (medium) — [https://www.pdok.nl/how-to-faq](https://www.pdok.nl/how-to-faq)
  > PDOK Promotiefilm met Nederlandstalige en Engelstalige ondertiteling (via instellingen) [...] Iedereen mag kosteloos data afnemen bij PDOK. [...] Via PDOK kunnen diverse datasets worden "gedownload". [...] Uitleg over de belangrijkste OGC standaarden die in gebruik zijn bij PDOK staat op https://www.pdok.nl/services-en-api-s
  - *De bron bevestigt dat PDOK een geo-dataportaal is dat open geodata en geo-services aanbiedt. De volledige naam 'Publieke Dienstverlening Op de Kaart' wordt echter niet uitgeschreven in de brontekst, en de kwalificatie 'nationaal' wordt niet expliciet gebruikt.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/](https://docs.geostandaarden.nl/)
  - *De brontekst is een inhoudsopgave van Geonovum-documentatie op docs.geostandaarden.nl. PDOK wordt nergens vermeld in de aangeleverde tekst.*
- **NOT_FOUND** (high) — [https://www.geonovum.nl/geo-standaarden](https://www.geonovum.nl/geo-standaarden)
  - *De brontekst gaat over geo-standaarden die Geonovum beheert. PDOK wordt nergens in de tekst genoemd.*

### `geo-0013` — SKILL.md:61 *(§ Sleutelorganisaties)*

> Het Kadaster beheert basisregistraties (BAG, BRK), PDOK en de Landelijke Voorziening BGT.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Kadaster organisatie

- **PARTIALLY_SUPPORTED** (low) — [https://www.pdok.nl/how-to-faq](https://www.pdok.nl/how-to-faq)
  > Het Kadaster bepaalt niet een exacte maar een indicatieve grootte. Grootte is alleen authentiek als soort grootte de waarde "vastgesteld" heeft. [...] Deze informatie is te vinden in de modeldocumentatie van de Kadastrale kaart
  - *De bron noemt het Kadaster alleen in de context van oppervlaktegegevens bij de Kadastrale kaart. Dat het Kadaster basisregistraties (BAG, BRK) beheert, PDOK beheert, of de Landelijke Voorziening BGT beheert, staat niet in de brontekst. Deze specifieke beheerstaken worden niet vermeld.*
- **PARTIALLY_SUPPORTED** (low) — [https://www.geonovum.nl/geo-standaarden](https://www.geonovum.nl/geo-standaarden)
  > IMX-Geo | Semantisch model basis- en kernregistraties: 'Om hergebruik van gegevens uit de kernregistraties eenvoudiger te maken, werken Kadaster en Geonovum samen aan een semantisch samenhangend model.'
  - *De bron bevestigt dat Kadaster samenwerkt met Geonovum, maar noemt BAG, BRK, PDOK of Landelijke Voorziening BGT niet expliciet als producten die Kadaster beheert. De claim over specifieke basisregistraties en PDOK is niet terug te vinden in deze brontekst.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/](https://docs.geostandaarden.nl/)
  - *Het Kadaster, BAG, BRK, PDOK en de Landelijke Voorziening BGT worden geen van allen vermeld in de aangeleverde brontekst.*
- **NOT_FOUND** (high) — [https://developer.kadaster.nl/](https://developer.kadaster.nl/)
  - *De brontekst is een algemene developer-landingspagina van Kadaster. Er staat geen specifieke vermelding van BAG, BRK, BGT of PDOK als basisregistraties beheerd door Kadaster. PDOK wordt wel als naam genoemd maar niet in de context van beheer.*

### `geo-0014` — SKILL.md:83 *(§ Aanvullende Standaarden)*

> GeoPackage is verplicht formaat voor geodata-downloads bij de overheid sinds 2019.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** GeoPackage standaard overheid

- **PARTIALLY_SUPPORTED** (high) — [https://www.geonovum.nl/geo-standaarden/geopackage](https://www.geonovum.nl/geo-standaarden/geopackage)
  > In 2019 is deze standaard opgenomen op de Nederlandse Pas-toe-of-leg-uit-lijst. Dit betekent dat Nederlandse overheidsorganisaties bij het aanbieden van een download van hun data naast GML ook het GeoPackage formaat moeten kunnen leveren.
  - *De bron bevestigt de opname in 2019 en de verplichting voor overheidsorganisaties, maar nuanceert dat GeoPackage naast GML geleverd moet worden, niet als enig verplicht formaat. De claim 'verplicht formaat' is daarmee niet volledig juist: het is een aanvullende verplichting naast GML.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/rwgs/rw](https://docs.geostandaarden.nl/rwgs/rw)
  - *De bron vermeldt GeoPackage als uitwisselstandaard (tabel 6.1) en als INSPIRE good practice, maar er staat nergens dat het een verplicht formaat is voor geodata-downloads bij de overheid 'sinds 2019'. Er is geen verplichting of datum vermeld.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/nl-sbb/nl-sbb](https://docs.geostandaarden.nl/nl-sbb/nl-sbb)
  - *De bron gaat over NL-SBB (standaard voor het beschrijven van begrippen) en bevat geen informatie over GeoPackage of verplichte formaten voor geodata-downloads.*

### `geo-0019` — SKILL.md:70 *(§ Belangrijke Repositories)*

> Geonovum/NEN3610-Linkeddata bevat het NEN 3610 linked data profiel en is uitgebracht onder CC-BY-4.0 licentie.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** NEN 3610 linked data repository

- **SOURCE_UNAVAILABLE** (high) — [https://raw.githubusercontent.com/Geonovum/NEN3610-Linkeddata/main/LICENSE](https://raw.githubusercontent.com/Geonovum/NEN3610-Linkeddata/main/LICENSE)
  - *Bron status: unreachable*
- **SOURCE_UNAVAILABLE** (high) — [https://raw.githubusercontent.com/Geonovum/NEN3610-Linkeddata/master/LICENSE](https://raw.githubusercontent.com/Geonovum/NEN3610-Linkeddata/master/LICENSE)
  - *Bron status: unreachable*
- **PARTIALLY_SUPPORTED** (medium) — [https://github.com/Geonovum/NEN3610-Linkeddata](https://github.com/Geonovum/NEN3610-Linkeddata)
  > Repository voor het werken aan een linked data profiel op NEN3610. De concepttekst is hier te lezen: https://geonovum.github.io/NEN3610-Linkeddata
  - *De bron bevestigt dat de repository het NEN 3610 linked data profiel bevat, maar vermeldt nergens een CC-BY-4.0 licentie. Er is geen licentie-informatie aanwezig in de aangeleverde brontekst.*

### `geo-0020` — SKILL.md:72 *(§ Belangrijke Repositories)*

> Geonovum/inspire-handreiking bevat de INSPIRE implementatie handreiking en is uitgebracht onder CC-BY-ND-4.0 licentie.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** INSPIRE handreiking repository

- **SOURCE_UNAVAILABLE** (high) — [https://raw.githubusercontent.com/Geonovum/inspire-handreiking/main/LICENSE](https://raw.githubusercontent.com/Geonovum/inspire-handreiking/main/LICENSE)
  - *Bron status: unreachable*
- **SOURCE_UNAVAILABLE** (high) — [https://raw.githubusercontent.com/Geonovum/inspire-handreiking/master/LICENSE](https://raw.githubusercontent.com/Geonovum/inspire-handreiking/master/LICENSE)
  - *Bron status: unreachable*
- **PARTIALLY_SUPPORTED** (medium) — [https://github.com/Geonovum/inspire-handreiking](https://github.com/Geonovum/inspire-handreiking)
  > INSPIRE-handreiking Welkom op de INSPIRE-handreiking. De werkversie van de handreiking kan benaderd worden via: https://geonovum.github.io/inspire-handreiking/ De laatste officiele publicatie kan benaderd worden via: https://docs.geostandaarden.nl/eu/INSPIRE-handreiking/
  - *De bron bevestigt dat de repository de INSPIRE implementatie handreiking bevat. De CC-BY-ND-4.0 licentie wordt echter nergens in de aangeleverde brontekst vermeld — er is geen LICENSE-bestand of licentie-aanduiding zichtbaar in de weergegeven inhoud.*

### `geo-0021` — SKILL.md:73 *(§ Belangrijke Repositories)*

> Geonovum/IMGeo bevat het Informatiemodel Geografie (BGT/IMGeo) en is uitgebracht onder CC-BY-4.0 licentie.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** IMGeo repository

- **SOURCE_UNAVAILABLE** (high) — [https://raw.githubusercontent.com/Geonovum/IMGeo/main/LICENSE](https://raw.githubusercontent.com/Geonovum/IMGeo/main/LICENSE)
  - *Bron status: unreachable*
- **SOURCE_UNAVAILABLE** (high) — [https://raw.githubusercontent.com/Geonovum/IMGeo/master/LICENSE](https://raw.githubusercontent.com/Geonovum/IMGeo/master/LICENSE)
  - *Bron status: unreachable*
- **PARTIALLY_SUPPORTED** (medium) — [https://github.com/Geonovum/IMGeo](https://github.com/Geonovum/IMGeo)
  > Geonovum / IMGeo Public ... BGT|IMGeo standaarden ... About IMGeo volgens mappenstructuur op register.geostandaarden.nl
  - *De bron bevestigt dat de repository Geonovum/IMGeo het BGT|IMGeo informatiemodel bevat. De CC-BY-4.0 licentie wordt nergens in de aangeleverde brontekst vermeld; er is geen licentie-informatie zichtbaar in de weergegeven GitHub-pagina.*

### `geo-0022` — SKILL.md:74 *(§ Belangrijke Repositories)*

> Geonovum/MIM-Werkomgeving bevat het Metamodel Informatie Modellering en is uitgebracht onder CC-BY-4.0 licentie.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** MIM repository

- **SOURCE_UNAVAILABLE** (high) — [https://raw.githubusercontent.com/Geonovum/MIM-Werkomgeving/main/LICENSE](https://raw.githubusercontent.com/Geonovum/MIM-Werkomgeving/main/LICENSE)
  - *Bron status: unreachable*
- **SOURCE_UNAVAILABLE** (high) — [https://raw.githubusercontent.com/Geonovum/MIM-Werkomgeving/master/LICENSE](https://raw.githubusercontent.com/Geonovum/MIM-Werkomgeving/master/LICENSE)
  - *Bron status: unreachable*
- **PARTIALLY_SUPPORTED** (high) — [https://github.com/Geonovum/MIM-Werkomgeving](https://github.com/Geonovum/MIM-Werkomgeving)
  > Dit is de repository van het Metamodel Informatie Modellering (MIM). Hierin staat de werkversie van het MIM.
  - *De bron bevestigt dat de repository het Metamodel Informatie Modellering bevat. Er is echter geen vermelding van een CC-BY-4.0 licentie in de aangeleverde brontekst. Het licentiedeel kan dus niet worden ondersteund.*

## GROUNDED — minstens één bron ondersteunt de claim (11)

<details>
<summary>Klap uit voor alle GROUNDED claims</summary>

### `geo-0003` — SKILL.md:26 *(§ Forum Standaardisatie Status)*

> De geo-standaarden staan op de 'pas-toe-of-leg-uit'-lijst van het Forum Standaardisatie.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Forum Standaardisatie status geo-standaarden

- **SUPPORTED** (high) — [https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden](https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden)
  > De Geo-standaarden op de 'Pas toe of leg uit'-lijst van het Forum Standaardisatie bestaan thans uit: Nederlands metadataprofiel op ISO 19115 voor geografie, versie 2.1.0 [...] NEN 3610:2022 [...] ISO 19136:2007 [...] GeoPackage 1.3.1 [...]

### `geo-0004` — SKILL.md:26 *(§ Forum Standaardisatie Status)*

> Sinds september 2024 is de samenstelling van de geo-standaarden op de pas-toe-of-leg-uit-lijst gewijzigd.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Forum Standaardisatie status geo-standaarden

- **SUPPORTED** (high) — [https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden](https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden)
  > Op 19 september 2024 stemde het OBDO in met het verplichten van OGC-API – Features Part 1: Core en Part 2: Coordinate Reference Systems by Reference en OGC-API – Tiles - Part 1: Core door plaatsing op de 'pas toe of leg uit'-lijst en het aanbevelen van Nederlands WFS profiel 1.1 [...] en Nederlands profiel op ISO 19128 [...] (WMS) door plaatsing op de lijst aanbevolen standaarden.

### `geo-0006` — SKILL.md:33 *(§ Forum Standaardisatie Status)*

> OGC API Features is verplicht (pas-toe-of-leg-uit) als REST API service standaard onderdeel van het Geo-Standaarden-pakket.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Forum Standaardisatie verplichte geo-standaarden

- **SUPPORTED** (high) — [https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden](https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden)
  > OGC-API – Features Part 1: Core en Part 2: Coordinate Reference Systems by Reference (specifiek toepassingsgebied: OGC-API - Features Part 1 en Part 2 moeten worden toegepast bij het per REST API aanbieden voor derden van geografische object-informatie)

### `geo-0007` — SKILL.md:34 *(§ Forum Standaardisatie Status)*

> OGC API Tiles is verplicht (pas-toe-of-leg-uit) als tileservice standaard onderdeel van het Geo-Standaarden-pakket.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Forum Standaardisatie verplichte geo-standaarden

- **SUPPORTED** (high) — [https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden](https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden)
  > OGC-API – Tiles - Part 1: Core (specifiek toepassingsgebied : OGC-API – OGC-API – Tiles Part 1 moet worden toegepast bij het per REST API aanbieden voor derden van geografische informatie als verbeelding)

### `geo-0008` — SKILL.md:35 *(§ Forum Standaardisatie Status)*

> NEN 3610 is verplicht (pas-toe-of-leg-uit) als informatiemodel onderdeel van het Geo-Standaarden-pakket.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Forum Standaardisatie verplichte geo-standaarden

- **SUPPORTED** (high) — [https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden](https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden)
  > NEN 3610:2022 (nl) Basismodel Geo-informatie - Termen, definities, relaties en algemene regels voor de uitwisseling van informatie over aan de aarde gerelateerde ruimtelijke objecten, versie 2022 (specifiek toepassingsgebied : metadatering van geografische datasets en dataset series)
  - *De bron noemt 'informatiemodel' niet letterlijk, maar NEN 3610 is beschreven als 'Basismodel Geo-informatie' en staat op de verplichte lijst. De typering 'informatiemodel' is een correcte parafrase.*

### `geo-0009` — SKILL.md:36 *(§ Forum Standaardisatie Status)*

> ISO 19115/19119 is verplicht (pas-toe-of-leg-uit) als metadata standaard onderdeel van het Geo-Standaarden-pakket.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Forum Standaardisatie verplichte geo-standaarden

- **SUPPORTED** (high) — [https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden](https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden)
  > Nederlands metadataprofiel op ISO 19115 voor geografie, versie 2.1.0 (specifiek toepassingsgebied : metadatering van geografische datasets en dataset series) Nederlands metadata profiel op ISO 19119 voor services, versie 2.1.0 (specifiek toepassingsgebied : metadatering van geografische informatie services)

### `geo-0010` — SKILL.md:38 *(§ Forum Standaardisatie Status)*

> WMS is sinds september 2024 verplaatst van verplicht naar aanbevolen (als viewservice).

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Forum Standaardisatie status WMS

- **SUPPORTED** (high) — [https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden](https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden)
  > Op 19 september 2024 stemde het OBDO in met [...] het aanbevelen van [...] Nederlands profiel op ISO 19128 Geographic information - Web Map Server Interface (WMS) door plaatsing op de lijst aanbevolen standaarden.
  - *De bron bevestigt dat WMS per september 2024 is verplaatst naar de aanbevolen lijst. Dat het daarvoor verplicht was staat niet expliciet in de bron, maar de beweging van verplicht naar aanbevolen is consistent met de septemberbeslissing die de bron beschrijft.*

### `geo-0011` — SKILL.md:38 *(§ Forum Standaardisatie Status)*

> WFS is sinds september 2024 verplaatst van verplicht naar aanbevolen (als downloadservice).

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Forum Standaardisatie status WFS

- **SUPPORTED** (high) — [https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden](https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden)
  > Op 19 september 2024 stemde het OBDO in met [...] het aanbevelen van Nederlands WFS profiel 1.1 op ISO 19142 voor Web Feature Services 2.0, versie 1.1 (WFS) [...] door plaatsing op de lijst aanbevolen standaarden.
  - *Zelfde redenering als geo-0010: de bron bevestigt plaatsing op de aanbevolen lijst per september 2024.*

### `geo-0016` — SKILL.md:82 *(§ Aanvullende Standaarden)*

> Het Raamwerk Geo-Standaarden is een overzichtsdocument dat beschrijft hoe alle geo-standaarden samenhangen, gepubliceerd op docs.geostandaarden.nl/rwgs/rw/.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Raamwerk Geo-Standaarden

- **SUPPORTED** (high) — [https://docs.geostandaarden.nl/rwgs/rw](https://docs.geostandaarden.nl/rwgs/rw)
  > "Het Raamwerk van Geostandaarden helpt daarbij. Het benoemt de internationale en nationale standaarden die voor Nederland binnen het geo-domein van toepassing zijn voor aansluiting met andere domeinen." De bron is gepubliceerd op https://docs.geostandaarden.nl/rwgs/rw/ zoals vermeld in de header.
  - *De claim dat het een overzichtsdocument is dat beschrijft hoe alle geo-standaarden samenhangen en gepubliceerd op docs.geostandaarden.nl/rwgs/rw/ wordt volledig bevestigd door de bron zelf.*
- **NOT_FOUND** (high) — [https://www.geonovum.nl/geo-standaarden/geopackage](https://www.geonovum.nl/geo-standaarden/geopackage)
  - *De brontekst gaat uitsluitend over GeoPackage. Het Raamwerk Geo-Standaarden en docs.geostandaarden.nl worden niet genoemd.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/nl-sbb/nl-sbb](https://docs.geostandaarden.nl/nl-sbb/nl-sbb)
  - *De bron gaat over NL-SBB en bevat geen informatie over het Raamwerk Geo-Standaarden of docs.geostandaarden.nl/rwgs/rw/.*

### `geo-0017` — SKILL.md:84 *(§ Aanvullende Standaarden)*

> NL-SBB is de standaard voor het beschrijven van begrippen, gepubliceerd op docs.geostandaarden.nl/nl-sbb/nl-sbb/.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** NL-SBB standaard

- **SUPPORTED** (high) — [https://docs.geostandaarden.nl/rwgs/rw](https://docs.geostandaarden.nl/rwgs/rw)
  > "[SBB] Standaard voor het Beschrijven van Begrippen . Geonovum. 2024-10-10. Vastgestelde versie. URL: https://docs.geostandaarden.nl/nl-sbb/nl-sbb/"
  - *De bron noemt de SBB expliciet als 'Standaard voor het Beschrijven van Begrippen' met exact de genoemde URL. De afkorting NL-SBB wordt in de bron ook gebruikt ('NL-SBB' verschijnt in de tekst als verwijzing naar dezelfde standaard).*
- **SUPPORTED** (high) — [https://docs.geostandaarden.nl/nl-sbb/nl-sbb](https://docs.geostandaarden.nl/nl-sbb/nl-sbb)
  > NL-SBB - Standaard voor het beschrijven van begrippen Geonovum Standaard Vastgestelde versie 10 oktober 2024 [...] Laatste gepubliceerde versie: https://docs.geostandaarden.nl/nl-sbb/nl-sbb/
  - *De brontekst bevestigt expliciet dat NL-SBB de standaard is voor het beschrijven van begrippen en gepubliceerd is op docs.geostandaarden.nl/nl-sbb/nl-sbb/.*
- **NOT_FOUND** (high) — [https://www.geonovum.nl/geo-standaarden/geopackage](https://www.geonovum.nl/geo-standaarden/geopackage)
  - *De brontekst gaat uitsluitend over GeoPackage. NL-SBB wordt niet genoemd.*

### `geo-0018` — SKILL.md:69 *(§ Belangrijke Repositories)*

> De Geonovum ogc-checker (github.com/Geonovum/ogc-checker) is een validatietool voor OGC services, uitgebracht onder EUPL-1.2 licentie.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Geonovum ogc-checker repository

- **PARTIALLY_SUPPORTED** (medium) — [https://raw.githubusercontent.com/Geonovum/ogc-checker/main/LICENSE](https://raw.githubusercontent.com/Geonovum/ogc-checker/main/LICENSE)
  > EUROPEAN UNION PUBLIC LICENCE v. 1.2 EUPL © the European Union 2007, 2016 This European Union Public Licence (the 'EUPL') applies to the Work (as defined below) which is provided under the terms of this Licence.
  - *De bron bevestigt dat de EUPL v1.2 licentie van toepassing is op dit werk (het LICENSE-bestand van de ogc-checker repository). Het deel over 'validatietool voor OGC services' wordt niet door de brontekst bevestigd — een LICENSE-bestand bevat geen beschrijving van de functionaliteit van de software.*
- **PARTIALLY_SUPPORTED** (high) — [https://raw.githubusercontent.com/Geonovum/ogc-checker/master/LICENSE](https://raw.githubusercontent.com/Geonovum/ogc-checker/master/LICENSE)
  > EUROPEAN UNION PUBLIC LICENCE v. 1.2 EUPL © the European Union 2007, 2016 This European Union Public Licence (the 'EUPL') applies to the Work (as defined below) which is provided under the terms of this Licence.
  - *De bron bevestigt dat de EUPL v1.2 licentie van toepassing is op de ogc-checker repository (het bestand is afkomstig van github.com/Geonovum/ogc-checker/master/LICENSE). Dat de tool een validatietool voor OGC services is, wordt niet vermeld in deze licentiefile — een LICENSE-bestand bevat geen functionele beschrijving van de software.*
- **SUPPORTED** (high) — [https://github.com/Geonovum/ogc-checker](https://github.com/Geonovum/ogc-checker)
  > Geonovum OGC Checker Validates JSON-FG documents and OGC API endpoints against OGC specifications. [...] License EUPL-1.2

</details>
