<!-- markdownlint-disable MD052 MD034 MD013 MD038 -->
# Audit geo-meta — 2026-05-17

> Automatisch gegenereerd door audit-tooling. Niet handmatig bewerken; wijzig SKILL.md / reference.md en regenereer.

## Samenvatting

| Status | Aantal | % |
|--------|--------|---|
| UNSUPPORTED_ASSERTION | 22 | 40% |
| CONTRADICTED | 0 | 0% |
| PARTIALLY_GROUNDED | 0 | 0% |
| UNGROUNDED | 29 | 53% |
| NO_SOURCE | 0 | 0% |
| UNVERIFIABLE | 0 | 0% |
| KNOWN_DISCREPANCY | 0 | 0% |
| GROUNDED | 4 | 7% |

*Geverifieerd met sonnet, 6 calls, $0.6475.*

## UNSUPPORTED_ASSERTION — stellige bewering zonder enige bronsteun (mogelijke hallucinatie) (22)

### `geo-meta-0002` — SKILL.md:22 *(§ Metadata voor Geodata)*

> Het Nationaal Georegister (NGR) is het centrale portaal voor het zoeken en publiceren van metadata over Nederlandse geodatasets en -services.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Nationaal Georegister (NGR)

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/mdprofiel-iso19115](https://docs.geostandaarden.nl/md/mdprofiel-iso19115)
  - *De bron beschrijft het Nederlandse metadata profiel op ISO 19115, maar noemt het Nationaal Georegister (NGR) nergens.*

### `geo-meta-0010` — SKILL.md:56 *(§ Verplichte elementen (dataset))*

> Het verplichte element Ruimtelijk referentiesysteem (`referenceSystemInfo`) bevat het CRS (bijv. EPSG:28992).

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Nederlands profiel ISO 19115, dataset metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen inhoudelijke specificaties over referenceSystemInfo.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen inhoudelijke informatie over referenceSystemInfo of CRS.*

### `geo-meta-0014` — SKILL.md:149 *(§ CSW (Catalogue Service for the Web))*

> CSW is het OGC-protocol voor het zoeken en harvesten van metadata. Het NGR biedt een CSW-endpoint.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** CSW 2.0.2, NGR

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen informatie over CSW of NGR.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen informatie over CSW of NGR.*

### `geo-meta-0015` — SKILL.md:153 *(§ CSW (Catalogue Service for the Web))*

> Het NGR CSW-endpoint is bereikbaar op https://www.nationaalgeoregister.nl/geonetwork/srv/dut/csw met versie 2.0.2.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** NGR CSW endpoint

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen URL-informatie over NGR CSW-endpoint.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen informatie over het NGR CSW-endpoint.*

### `geo-meta-0017` — SKILL.md:198 *(§ DCAT voor Geodata)*

> GeoDCAT-AP biedt een mapping van ISO 19115 naar DCAT (RDF) voor koppeling met data.overheid.nl en het Europese data-portaal.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** GeoDCAT-AP, ISO 19115, DCAT

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen informatie over GeoDCAT-AP of ISO 19115 naar DCAT mapping.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen informatie over GeoDCAT-AP of ISO 19115 naar DCAT mapping.*

### `geo-meta-0018` — SKILL.md:198 *(§ DCAT voor Geodata)*

> DCAT-AP-NL is het Nederlandse profiel op DCAT-AP.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** DCAT-AP-NL

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen informatie over DCAT-AP-NL.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen informatie over DCAT-AP-NL.*

### `geo-meta-0019` — SKILL.md:216 *(§ Verhouding ISO 19115 en DCAT)*

> ISO 19115 element Titel mapt naar DCAT property `dct:title`.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** ISO 19115 naar DCAT mapping

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen mapping-informatie.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen mapping-informatie.*

### `geo-meta-0020` — SKILL.md:217 *(§ Verhouding ISO 19115 en DCAT)*

> ISO 19115 element Samenvatting mapt naar DCAT property `dct:description`.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** ISO 19115 naar DCAT mapping

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen mapping-informatie.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen mapping-informatie.*

### `geo-meta-0021` — SKILL.md:218 *(§ Verhouding ISO 19115 en DCAT)*

> ISO 19115 element Verantwoordelijke organisatie mapt naar DCAT property `dct:publisher`.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** ISO 19115 naar DCAT mapping

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen mapping-informatie.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen mapping-informatie.*

### `geo-meta-0022` — SKILL.md:219 *(§ Verhouding ISO 19115 en DCAT)*

> ISO 19115 element Trefwoorden mapt naar DCAT property `dcat:keyword`.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** ISO 19115 naar DCAT mapping

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen mapping-informatie.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen mapping-informatie.*

### `geo-meta-0023` — SKILL.md:220 *(§ Verhouding ISO 19115 en DCAT)*

> ISO 19115 element Datum (publicatie) mapt naar DCAT property `dct:issued`.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** ISO 19115 naar DCAT mapping

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen mapping-informatie.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen mapping-informatie.*

### `geo-meta-0024` — SKILL.md:221 *(§ Verhouding ISO 19115 en DCAT)*

> ISO 19115 element Distributie (URL) mapt naar DCAT property `dcat:distribution`.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** ISO 19115 naar DCAT mapping

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen mapping-informatie.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen mapping-informatie.*

### `geo-meta-0025` — SKILL.md:222 *(§ Verhouding ISO 19115 en DCAT)*

> ISO 19115 element Ruimtelijke dekking (bbox) mapt naar DCAT property `dct:spatial`.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** ISO 19115 naar DCAT mapping

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen mapping-informatie.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen mapping-informatie.*

### `geo-meta-0026` — SKILL.md:223 *(§ Verhouding ISO 19115 en DCAT)*

> ISO 19115 element Temporele dekking mapt naar DCAT property `dct:temporal`.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** ISO 19115 naar DCAT mapping

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen mapping-informatie.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen mapping-informatie.*

### `geo-meta-0046` — reference.md:100 *(§ ISO XML metadata)*

> De Geonovum validator voor ISO XML metadata is bereikbaar op https://validatie.geostandaarden.nl/etf-webapp/v2/TestRuns.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Validatietools, Nederlands profiel ISO 19115

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen informatie over validatietools of URLs daarvoor.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen informatie over validatietools of validatie.geostandaarden.nl.*

### `geo-meta-0047` — reference.md:110 *(§ DCAT metadata (SHACL-validatie))*

> DCAT-AP profielen worden gedefinieerd in SHACL. DCAT-AP-NL bouwt voort op de SHACL-shapes van DCAT-AP met aanvullende Nederlandse regels.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** DCAT-AP-NL, SHACL-validatie

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen informatie over SHACL of DCAT-AP profielen.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen informatie over SHACL of DCAT-AP profielen.*

### `geo-meta-0048` — reference.md:110 *(§ DCAT metadata (SHACL-validatie))*

> Er zijn meerdere DCAT-AP validatieniveaus: alleen verplichte eigenschappen, aanbevolen eigenschappen, of inclusief HVD-eisen (High-Value Datasets).

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** DCAT-AP-NL, SHACL-validatie

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen informatie over DCAT-AP validatieniveaus.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen informatie over DCAT-AP validatieniveaus.*

### `geo-meta-0049` — reference.md:113 *(§ DCAT metadata (SHACL-validatie))*

> De DCAT-AP online validator (Europa) is beschikbaar op https://www.itb.ec.europa.eu/shacl/semic-shacl/upload en ondersteunt verschillende versies en niveaus van DCAT-AP.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** DCAT-AP validatietools

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen informatie over DCAT-AP validatietools of URLs.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen informatie over DCAT-AP validatietools.*

### `geo-meta-0050` — reference.md:134 *(§ DCAT metadata (SHACL-validatie))*

> DCAT metadata maakt vaak gebruik van URI's naar externe registraties, zoals TOOI URI's voor overheidsorganisaties.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** DCAT-AP-NL metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen informatie over DCAT metadata of TOOI URI's.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen informatie over DCAT metadata of TOOI URI's.*

### `geo-meta-0051` — reference.md:164 *(§ Optie C: GeoNetwork REST API)*

> Metadata uploaden via GeoNetwork REST API kan via PUT naar https://www.nationaalgeoregister.nl/geonetwork/srv/api/records met X-XSRF-TOKEN header.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** NGR publicatieworkflow, GeoNetwork REST API

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen informatie over GeoNetwork REST API of uploadmethoden.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen informatie over GeoNetwork REST API of uploaden van metadata.*

### `geo-meta-0052` — reference.md:183 *(§ DCAT en GeoDCAT-AP)*

> GeoDCAT-AP is een Europees profiel dat ISO 19115 metadata mapt naar DCAT (RDF), relevant voor koppeling met data.overheid.nl en het Europese data-portaal.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** GeoDCAT-AP

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen informatie over GeoDCAT-AP.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen informatie over GeoDCAT-AP.*

### `geo-meta-0055` — SKILL.md:85 *(§ Voorbeeld Metadata XML (NL profiel))*

> Het metadataStandardVersion element in het XML-voorbeeld heeft de waarde 'Nederlands metadata profiel op ISO 19115 voor geografie 2.1.0'.

**Type:** version_claim  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Nederlands profiel ISO 19115

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen XML-voorbeelden of waarden van metadataStandardVersion.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen inhoudelijke informatie over metadataStandardVersion waarden.*

## UNGROUNDED — geen bron ondersteunt de claim (29)

### `geo-meta-0004` — SKILL.md:28 *(§ Standaarden Overzicht)*

> ISO 19115:2003/19115-1:2014 heeft Forum Standaardisatie status 'Verplicht' voor beschrijving van datasets.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** ISO 19115, Forum Standaardisatie

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is een directory-index van /md op docs.geostandaarden.nl. Geen inhoudelijke informatie over Forum Standaardisatie status.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index van docs.geostandaarden.nl/mim en bevat geen informatie over Forum Standaardisatie status van ISO 19115.*

### `geo-meta-0005` — SKILL.md:29 *(§ Standaarden Overzicht)*

> ISO 19119:2005 heeft Forum Standaardisatie status 'Verplicht' voor beschrijving van services.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** ISO 19119, Forum Standaardisatie

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen informatie over Forum Standaardisatie status van ISO 19119.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen informatie over Forum Standaardisatie status van ISO 19119.*

### `geo-meta-0006` — SKILL.md:30 *(§ Standaarden Overzicht)*

> Het NL profiel ISO 19115 heeft Forum Standaardisatie status 'Verplicht' als Nederlandse invulling van ISO 19115.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115, Forum Standaardisatie

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen informatie over Forum Standaardisatie status van het NL profiel ISO 19115.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen informatie over Forum Standaardisatie status van het NL profiel ISO 19115.*

### `geo-meta-0007` — SKILL.md:32 *(§ Standaarden Overzicht)*

> DCAT-AP-NL heeft Forum Standaardisatie status 'Aanbevolen' voor geo-extensie via GeoDCAT-AP.

**Type:** normative_requirement  ·  **Modaliteit:** SHOULD  ·  **Scope:** DCAT-AP-NL, Forum Standaardisatie

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen informatie over DCAT-AP-NL of Forum Standaardisatie status.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen informatie over DCAT-AP-NL of Forum Standaardisatie status.*

### `geo-meta-0009` — SKILL.md:54 *(§ Verplichte elementen (dataset))*

> Het verplichte element Trefwoorden (`identificationInfo/descriptiveKeywords`) vereist minstens 1 trefwoord.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115, dataset metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen inhoudelijke specificaties over verplichte elementen.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen inhoudelijke informatie over het NL profiel ISO 19115.*

### `geo-meta-0011` — SKILL.md:58 *(§ Verplichte elementen (dataset))*

> Het verplichte element Taal (`identificationInfo/language`) bevat de taal van de dataset als 'dut' of 'nld'.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115, dataset metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen inhoudelijke specificaties over taal-elementen.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen informatie over taal-elementen in het NL profiel.*

### `geo-meta-0012` — SKILL.md:63 *(§ Verplichte elementen (dataset))*

> Het verplichte element Metadata-standaard (`metadataStandardName`) heeft de waarde 'ISO 19115'.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115, dataset metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen inhoudelijke specificaties over metadataStandardName.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen informatie over metadataStandardName.*

### `geo-meta-0013` — SKILL.md:65 *(§ Verplichte elementen (dataset))*

> Het verplichte element Metadata-taal (`language`) heeft de waarde 'dut' of 'nld'.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115, dataset metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen inhoudelijke specificaties over metadata-taal.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen informatie over metadata-taal elementen.*

### `geo-meta-0016` — SKILL.md:233 *(§ Veelvoorkomende Problemen)*

> In CSW CQL-queries wordt het procent-teken gebruikt als wildcard in AnyText like '%term%'.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** CSW 2.0.2 CQL_TEXT queries

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen informatie over CSW CQL-queries.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen informatie over CSW CQL-queries of wildcards.*

### `geo-meta-0027` — SKILL.md:242 *(§ Publiceren in het NGR)*

> Metadata valideren tegen het NL profiel is vereist voordat gepubliceerd wordt in het NGR.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** NGR publicatieworkflow, Nederlands profiel ISO 19115

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen informatie over NGR publicatieworkflow of validatievereisten.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen informatie over NGR publicatieworkflow of validatie.*

### `geo-meta-0028` — reference.md:11 *(§ Dataset Metadata)*

> Het NL profiel vereist voor dataset metadata het element `fileIdentifier` als unieke UUID van het metadata-record.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115, dataset metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen inhoudelijke specificaties over fileIdentifier.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen inhoudelijke informatie over fileIdentifier.*

### `geo-meta-0029` — reference.md:14 *(§ Dataset Metadata)*

> Het NL profiel vereist voor dataset metadata het element `hierarchyLevel` met waarde dataset, series, of service.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115, dataset metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen inhoudelijke specificaties over hierarchyLevel.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen inhoudelijke informatie over hierarchyLevel.*

### `geo-meta-0030` — reference.md:16 *(§ Dataset Metadata)*

> Het NL profiel vereist voor dataset metadata het element `dateStamp` in formaat YYYY-MM-DD.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115, dataset metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen inhoudelijke specificaties over dateStamp.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen inhoudelijke informatie over dateStamp.*

### `geo-meta-0031` — reference.md:17 *(§ Dataset Metadata)*

> Het NL profiel vereist voor dataset metadata het element `metadataStandardName` met waarde 'ISO 19115'.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115, dataset metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen inhoudelijke specificaties over metadataStandardName.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen inhoudelijke informatie over metadataStandardName.*

### `geo-meta-0032` — reference.md:18 *(§ Dataset Metadata)*

> Het NL profiel vereist voor dataset metadata het element `metadataStandardVersion` met de versie van het NL profiel.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115, dataset metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen inhoudelijke specificaties over metadataStandardVersion.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen inhoudelijke informatie over metadataStandardVersion.*

### `geo-meta-0033` — reference.md:19 *(§ Dataset Metadata)*

> Het NL profiel vereist voor dataset metadata het element `referenceSystemInfo` (herhaalbaar) met het CRS (bijv. EPSG:28992).

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115, dataset metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen inhoudelijke specificaties over referenceSystemInfo.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen inhoudelijke informatie over referenceSystemInfo.*

### `geo-meta-0034` — reference.md:21 *(§ Dataset Metadata)*

> Het NL profiel vereist voor dataset metadata het element `distributionInfo` met distributie-informatie.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115, dataset metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen inhoudelijke specificaties over distributionInfo.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen inhoudelijke informatie over distributionInfo.*

### `geo-meta-0035` — reference.md:35 *(§ Identificatie-elementen (MD_DataIdentification))*

> Het NL profiel vereist voor identificatie-elementen `descriptiveKeywords` met minstens 1 trefwoord.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115, MD_DataIdentification

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen inhoudelijke specificaties over descriptiveKeywords.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen inhoudelijke informatie over descriptiveKeywords.*

### `geo-meta-0036` — reference.md:36 *(§ Identificatie-elementen (MD_DataIdentification))*

> Het NL profiel vereist voor identificatie-elementen `resourceConstraints` met gebruiksbeperkingen.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115, MD_DataIdentification

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen inhoudelijke specificaties over resourceConstraints.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen inhoudelijke informatie over resourceConstraints.*

### `geo-meta-0037` — reference.md:41 *(§ Identificatie-elementen (MD_DataIdentification))*

> Het NL profiel vereist voor identificatie-elementen `topicCategory` met minstens 1 ISO-categorie.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115, MD_DataIdentification

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen inhoudelijke specificaties over topicCategory.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen inhoudelijke informatie over topicCategory.*

### `geo-meta-0038` — reference.md:66 *(§ Service Metadata (ISO 19119))*

> Voor services (WMS, WFS, CSW) is het element `serviceType` verplicht met waarden zoals OGC:WMS, OGC:WFS, OGC:CSW.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** ISO 19119, service metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen informatie over service metadata elementen.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen informatie over ISO 19119 service metadata elementen.*

### `geo-meta-0039` — reference.md:67 *(§ Service Metadata (ISO 19119))*

> Voor services is het element `serviceTypeVersion` verplicht met de versie van het service-protocol.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** ISO 19119, service metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen informatie over serviceTypeVersion.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen informatie over serviceTypeVersion.*

### `geo-meta-0040` — reference.md:68 *(§ Service Metadata (ISO 19119))*

> Voor services is het element `couplingType` verplicht met waarde tight, mixed of loose.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** ISO 19119, service metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen informatie over couplingType.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen informatie over couplingType.*

### `geo-meta-0041` — reference.md:69 *(§ Service Metadata (ISO 19119))*

> Voor services is het element `containsOperations` verplicht met de operaties (GetCapabilities, GetMap, etc.).

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** ISO 19119, service metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen informatie over containsOperations.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen informatie over containsOperations.*

### `geo-meta-0042` — reference.md:77 *(§ Structurele validatie)*

> Het metadata-record moet voldoen aan het ISO 19115 XML-schema (gmd namespace) met correcte namespace-declaraties.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** ISO 19115 structurele validatie

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen informatie over XML-schema validatie of namespace-declaraties.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen informatie over XML-schema validatie of gmd namespace.*

### `geo-meta-0043` — reference.md:87 *(§ Inhoudelijke validatie (NL profiel))*

> Inhoudelijke validatie vereist dat de samenvatting minimaal 25 tekens bevat.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115, inhoudelijke validatie

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen inhoudelijke validatieregels.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen inhoudelijke validatieregels.*

### `geo-meta-0044` — reference.md:89 *(§ Inhoudelijke validatie (NL profiel))*

> Inhoudelijke validatie vereist dat contactgegevens een organisatienaam en e-mailadres bevatten.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115, inhoudelijke validatie

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen inhoudelijke validatieregels over contactgegevens.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen inhoudelijke validatieregels over contactgegevens.*

### `geo-meta-0045` — reference.md:90 *(§ Inhoudelijke validatie (NL profiel))*

> Inhoudelijke validatie vereist dat de bounding box valt binnen Nederland (lat: 50.75-53.47, lon: 3.37-7.21) of breder is.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115, inhoudelijke validatie

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen validatieregels over bounding box coördinaten.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen informatie over bounding box validatie.*

### `geo-meta-0054` — SKILL.md:232 *(§ Veelvoorkomende Problemen)*

> Voor INSPIRE-metadata moeten INSPIRE-thematrefwoorden worden toegevoegd uit de GEMET thesaurus.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** INSPIRE metadata, NGR

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *Directory-index bevat geen informatie over INSPIRE-metadata of GEMET thesaurus.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directory-index en bevat geen informatie over INSPIRE-metadata of GEMET thesaurus.*

## GROUNDED — minstens één bron ondersteunt de claim (4)

<details>
<summary>Klap uit voor alle GROUNDED claims</summary>

### `geo-meta-0001` — SKILL.md:20 *(§ Metadata voor Geodata)*

> Metadata (ISO 19115/19119) is verplicht onder 'pas-toe-of-leg-uit' van het Forum Standaardisatie.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** ISO 19115/19119 metadata, Forum Standaardisatie

- **SUPPORTED** (high) — [https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden](https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden)
  > Nederlands metadataprofiel op ISO 19115 voor geografie, versie 2.1.0 (specifiek toepassingsgebied : metadatering van geografische datasets en dataset series) Nederlands metadata profiel op ISO 19119 voor services, versie 2.1.0 (specifiek toepassingsgebied : metadatering van geografische informatie services)
  - *De bron bevestigt expliciet dat beide metadataprofielen (ISO 19115 en ISO 19119) onderdeel zijn van de Geo-standaarden op de 'Pas toe of leg uit'-lijst van het Forum Standaardisatie.*
- **PARTIALLY_SUPPORTED** (medium) — [https://docs.geostandaarden.nl/md/mdprofiel-iso19115](https://docs.geostandaarden.nl/md/mdprofiel-iso19115)
  > Beide profielen staan op de Pas-toe-of-leg-uit-lijst van het College Standaardisatie.
  - *De bron bevestigt de Pas-toe-of-leg-uit-status, maar noemt 'College Standaardisatie' in plaats van 'Forum Standaardisatie'. Dit zijn verschillende organen. Verder vermeldt de bron alleen het dataset-profiel (ISO 19115) en het services-profiel (ISO 19119) als beide op de lijst staand, wat de claim ondersteunt, maar de naamsverschil levert een lichte discrepantie op.*
- **NOT_FOUND** (medium) — [https://www.forumstandaardisatie.nl/open-standaarden](https://www.forumstandaardisatie.nl/open-standaarden)
  - *De brontekst bevat alleen de navigatiestructuur en algemene paginaindeling van de Forum Standaardisatie 'Lijst open standaarden'-pagina. Er staat geen concrete lijst van standaarden met namen zoals ISO 19115 of ISO 19119. De claim kan hiermee niet worden bevestigd of weerlegd.*

### `geo-meta-0003` — SKILL.md:22 *(§ Metadata voor Geodata)*

> Geonovum beheert het Nederlands profiel op ISO 19115/19119 als basis voor alle metadata.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Nederlands profiel ISO 19115/19119

- **SUPPORTED** (high) — [https://docs.geostandaarden.nl/md/mdprofiel-iso19115](https://docs.geostandaarden.nl/md/mdprofiel-iso19115)
  > Geonovum ontwikkelt en beheert de Nederlandse metadata profielen. Deze profielen zijn een verbijzondering van de internationale metadatastandaarden van ISO en zijn bedoeld om de interoperabiliteit binnen Nederland te bevorderen. De volgende metadata profielen worden ondersteund en gebruikt: datasets: Nederlands metadata profiel op ISO 19115 voor geografie versie 2.0.0 services: Nederlands metad...

### `geo-meta-0008` — SKILL.md:44 *(§ Nederlands Profiel ISO 19115)*

> Het Nederlands profiel specificeert welke metadata-elementen verplicht, conditioneel of optioneel zijn voor Nederlandse geodatasets.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Nederlands profiel ISO 19115

- **SUPPORTED** (high) — [https://docs.geostandaarden.nl/md/mdprofiel-iso19115](https://docs.geostandaarden.nl/md/mdprofiel-iso19115)
  > In de volgende tabel staan de verplichte of bij conditie verplichte elementen. Bij elk conditioneel element is de conditie benoemd. [...] Naast de verplichte kernset heeft dit metadata profiel tevens een optionele set.
  - *De bron bevat een uitgebreide tabel (hoofdstuk 5.1) met verplichte (V), conditionele (C) en optionele elementen, en hoofdstuk 6 beschrijft de optionele set expliciet. Dit ondersteunt de claim volledig.*

### `geo-meta-0053` — SKILL.md:210 *(§ Samenhang metadata standaarden)*

> MDTO (Metagegevens Duurzaam Toegankelijke Overheidsinformatie) gaat uit van informatie-objecten en bestanden, terwijl DCAT en ISO 19115 werken met datasets en distributies.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** MDTO, DCAT, ISO 19115, samenhang metadata standaarden

- **SUPPORTED** (high) — [https://www.geonovum.nl/geo-standaarden/metadataprofiel-dcat-ap-nl/relaties-verschillende-metadata-standaarden](https://www.geonovum.nl/geo-standaarden/metadataprofiel-dcat-ap-nl/relaties-verschillende-metadata-standaarden)
  > MDTO gaat uit van informatieobjecten en DCAT en ISO 19115 van datasets [...] MDTO gaat uit van bestanden en DCAT en ISO 19115 van distributies

</details>
