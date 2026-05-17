<!-- markdownlint-disable MD052 MD034 MD013 -->
# Audit geo-meta — 2026-05-17

> Automatisch gegenereerd door audit-tooling. Niet handmatig bewerken; wijzig SKILL.md / reference.md en regenereer.

## Samenvatting

| Status | Aantal | % |
|--------|--------|---|
| UNSUPPORTED_ASSERTION | 19 | 34% |
| CONTRADICTED | 0 | 0% |
| PARTIALLY_GROUNDED | 1 | 2% |
| UNGROUNDED | 34 | 61% |
| NO_SOURCE | 0 | 0% |
| UNVERIFIABLE | 0 | 0% |
| KNOWN_DISCREPANCY | 0 | 0% |
| GROUNDED | 2 | 4% |

*Geverifieerd met sonnet, 5 calls, $0.5966.*

## UNSUPPORTED_ASSERTION — stellige bewering zonder enige bronsteun (mogelijke hallucinatie) (19)

### `geo-meta-0002` — SKILL.md:22 *(§ Metadata voor Geodata)*

> Het Nationaal Georegister (NGR) is het centrale portaal voor het zoeken en publiceren van metadata over Nederlandse geodatasets en -services.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** NGR — Nationaal Georegister

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/mdprofiel-iso19115](https://docs.geostandaarden.nl/md/mdprofiel-iso19115)
  - *De brontekst bevat geen vermelding van het Nationaal Georegister (NGR) als centraal portaal.*

### `geo-meta-0014` — SKILL.md:149 *(§ CSW (Catalogue Service for the Web))*

> CSW 2.0.2 is het OGC-protocol voor het zoeken en harvesten van metadata.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** CSW — Catalogue Service for the Web

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over CSW 2.0.2.*

### `geo-meta-0015` — SKILL.md:153 *(§ CSW (Catalogue Service for the Web))*

> Het NGR biedt een CSW-endpoint op https://www.nationaalgeoregister.nl/geonetwork/srv/dut/csw.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** NGR — CSW-endpoint

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over het NGR CSW-endpoint.*

### `geo-meta-0017` — SKILL.md:198 *(§ DCAT voor Geodata)*

> GeoDCAT-AP biedt een mapping van ISO 19115 naar DCAT.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** GeoDCAT-AP — ISO 19115 mapping

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over GeoDCAT-AP.*

### `geo-meta-0018` — SKILL.md:198 *(§ DCAT voor Geodata)*

> DCAT-AP-NL is het Nederlandse profiel op DCAT-AP.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** DCAT-AP-NL

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over DCAT-AP-NL.*

### `geo-meta-0019` — SKILL.md:216 *(§ Verhouding ISO 19115 en DCAT)*

> ISO 19115 element 'Titel' mapt naar DCAT property `dct:title`.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** GeoDCAT-AP — ISO 19115 naar DCAT mapping

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over GeoDCAT-AP mappings.*

### `geo-meta-0020` — SKILL.md:217 *(§ Verhouding ISO 19115 en DCAT)*

> ISO 19115 element 'Samenvatting' mapt naar DCAT property `dct:description`.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** GeoDCAT-AP — ISO 19115 naar DCAT mapping

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over GeoDCAT-AP mappings.*

### `geo-meta-0021` — SKILL.md:218 *(§ Verhouding ISO 19115 en DCAT)*

> ISO 19115 element 'Verantwoordelijke organisatie' mapt naar DCAT property `dct:publisher`.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** GeoDCAT-AP — ISO 19115 naar DCAT mapping

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over GeoDCAT-AP mappings.*

### `geo-meta-0022` — SKILL.md:219 *(§ Verhouding ISO 19115 en DCAT)*

> ISO 19115 element 'Trefwoorden' mapt naar DCAT property `dcat:keyword`.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** GeoDCAT-AP — ISO 19115 naar DCAT mapping

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over GeoDCAT-AP mappings.*

### `geo-meta-0023` — SKILL.md:220 *(§ Verhouding ISO 19115 en DCAT)*

> ISO 19115 element 'Datum (publicatie)' mapt naar DCAT property `dct:issued`.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** GeoDCAT-AP — ISO 19115 naar DCAT mapping

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over GeoDCAT-AP mappings.*

### `geo-meta-0024` — SKILL.md:221 *(§ Verhouding ISO 19115 en DCAT)*

> ISO 19115 element 'Distributie (URL)' mapt naar DCAT property `dcat:distribution`.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** GeoDCAT-AP — ISO 19115 naar DCAT mapping

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over GeoDCAT-AP mappings.*

### `geo-meta-0025` — SKILL.md:222 *(§ Verhouding ISO 19115 en DCAT)*

> ISO 19115 element 'Ruimtelijke dekking (bbox)' mapt naar DCAT property `dct:spatial`.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** GeoDCAT-AP — ISO 19115 naar DCAT mapping

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over GeoDCAT-AP mappings.*

### `geo-meta-0026` — SKILL.md:223 *(§ Verhouding ISO 19115 en DCAT)*

> ISO 19115 element 'Temporele dekking' mapt naar DCAT property `dct:temporal`.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** GeoDCAT-AP — ISO 19115 naar DCAT mapping

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over GeoDCAT-AP mappings.*

### `geo-meta-0051` — reference.md:110 *(§ DCAT metadata (SHACL-validatie))*

> DCAT-AP profielen worden gedefinieerd in SHACL; DCAT-AP-NL bouwt voort op de SHACL-shapes van DCAT-AP met aanvullende Nederlandse regels.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** DCAT-AP-NL — SHACL validatie

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over SHACL-validatie voor DCAT-AP-NL.*

### `geo-meta-0052` — reference.md:110 *(§ DCAT metadata (SHACL-validatie))*

> Er zijn meerdere validatieniveaus voor DCAT-AP-NL: alleen verplichte eigenschappen, aanbevolen eigenschappen, of inclusief HVD-eisen (High-Value Datasets).

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** DCAT-AP-NL — SHACL validatie niveaus

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over validatieniveaus voor DCAT-AP-NL.*

### `geo-meta-0053` — reference.md:183 *(§ DCAT en GeoDCAT-AP)*

> GeoDCAT-AP is een Europees profiel dat ISO 19115 metadata mapt naar DCAT (RDF), relevant voor koppeling met data.overheid.nl en het Europese data-portaal.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** GeoDCAT-AP

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over GeoDCAT-AP.*

### `geo-meta-0054` — SKILL.md:85 *(§ Voorbeeld Metadata XML (NL profiel))*

> Het NL profiel op ISO 19115 heeft versienummer 2.1.0 (`metadataStandardVersion`).

**Type:** version_claim  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Nederlands profiel ISO 19115 — versie

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over versienummer van het NL profiel op ISO 19115.*

### `geo-meta-0055` — reference.md:163 *(§ Optie C: GeoNetwork REST API)*

> Metadata uploaden via de GeoNetwork REST API kan via PUT op https://www.nationaalgeoregister.nl/geonetwork/srv/api/records met een X-XSRF-TOKEN header.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** NGR — GeoNetwork REST API publicatie

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is een directory-index van docs.geostandaarden.nl/md met alleen bestandsnamen en datums. Er staat niets over GeoNetwork REST API, PUT-requests, of X-XSRF-TOKEN headers.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De aangeleverde brontekst is een directory-listing van docs.geostandaarden.nl/mim en bevat geen informatie over de GeoNetwork REST API, PUT-endpoints of X-XSRF-TOKEN headers.*

### `geo-meta-0056` — reference.md:134 *(§ DCAT metadata (SHACL-validatie))*

> DCAT metadata maakt gebruik van URI's naar externe registraties, zoals TOOI URI's voor overheidsorganisaties; bij validatie zijn externe URI-verwijzingen niet altijd te controleren zonder ze te volgen.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** DCAT-AP-NL — validatie beperkingen

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is een directory-index van docs.geostandaarden.nl/md met alleen bestandsnamen en datums. Er staat niets over DCAT-AP-NL, URI-validatie, of TOOI URI's.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De aangeleverde brontekst is een directory-listing van docs.geostandaarden.nl/mim en bevat geen informatie over DCAT-AP-NL, URI-validatie of TOOI URI's voor overheidsorganisaties.*

## PARTIALLY_GROUNDED — bron ondersteunt deel van de claim (1)

### `geo-meta-0001` — SKILL.md:20 *(§ Metadata voor Geodata)*

> Metadata (ISO 19115/19119) is verplicht onder 'pas-toe-of-leg-uit' van het Forum Standaardisatie.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** ISO 19115/19119 — Forum Standaardisatie

- **PARTIALLY_SUPPORTED** (medium) — [https://docs.geostandaarden.nl/md/mdprofiel-iso19115](https://docs.geostandaarden.nl/md/mdprofiel-iso19115)
  > Beide profielen staan op de Pas-toe-of-leg-uit-lijst van het College Standaardisatie.
  - *De bron bevestigt dat beide profielen (ISO 19115 en ISO 19119) op de pas-toe-of-leg-uit-lijst staan, maar noemt het 'College Standaardisatie', niet het 'Forum Standaardisatie'. Dit kan dezelfde instantie zijn onder een andere naam, maar de bron gebruikt expliciet 'College Standaardisatie'.*

## UNGROUNDED — geen bron ondersteunt de claim (34)

### `geo-meta-0004` — SKILL.md:28 *(§ Standaarden Overzicht)*

> ISO 19115:2003/19115-1:2014 heeft Forum Standaardisatie status 'Verplicht' voor beschrijving van datasets.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** ISO 19115 — Forum Standaardisatie

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is een directory-index van docs.geostandaarden.nl/md/ met alleen bestandsnamen en datums. Geen inhoud over Forum Standaardisatie-statussen.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/ op docs.geostandaarden.nl. Bevat geen informatie over Forum Standaardisatie-status van ISO 19115.*

### `geo-meta-0005` — SKILL.md:29 *(§ Standaarden Overzicht)*

> ISO 19119:2005 heeft Forum Standaardisatie status 'Verplicht' voor beschrijving van services.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** ISO 19119 — Forum Standaardisatie

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst bevat alleen een directory-listing. Geen informatie over Forum Standaardisatie-status van ISO 19119.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over Forum Standaardisatie-status van ISO 19119.*

### `geo-meta-0006` — SKILL.md:30 *(§ Standaarden Overzicht)*

> Het NL profiel op ISO 19115 heeft Forum Standaardisatie status 'Verplicht'.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115 — Forum Standaardisatie

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst bevat alleen een directory-listing. Geen informatie over Forum Standaardisatie-status van het NL profiel.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over Forum Standaardisatie-status van het NL profiel op ISO 19115.*

### `geo-meta-0007` — SKILL.md:32 *(§ Standaarden Overzicht)*

> DCAT-AP-NL heeft Forum Standaardisatie status 'Aanbevolen' voor geodata-metadata.

**Type:** normative_requirement  ·  **Modaliteit:** SHOULD  ·  **Scope:** DCAT-AP-NL — Forum Standaardisatie

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst bevat alleen een directory-listing. Geen informatie over DCAT-AP-NL of Forum Standaardisatie.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over DCAT-AP-NL.*

### `geo-meta-0009` — SKILL.md:54 *(§ Verplichte elementen (dataset))*

> Het verplichte element 'Trefwoorden' vereist minstens 1 trefwoord (`identificationInfo/descriptiveKeywords`).

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115 — dataset metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over verplichte elementen in het NL profiel op ISO 19115.*

### `geo-meta-0010` — SKILL.md:56 *(§ Verplichte elementen (dataset))*

> Het verplichte element 'Ruimtelijk referentiesysteem' bevat het CRS, bijvoorbeeld EPSG:28992 (`referenceSystemInfo`).

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115 — dataset metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over referenceSystemInfo of CRS-eisen.*

### `geo-meta-0011` — SKILL.md:58 *(§ Verplichte elementen (dataset))*

> Het verplichte element 'Taal' geeft de taal van de dataset aan als 'dut' of 'nld' (`identificationInfo/language`).

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115 — dataset metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over taal-elementen in het NL profiel.*

### `geo-meta-0012` — SKILL.md:63 *(§ Verplichte elementen (dataset))*

> Het verplichte element 'Metadata-standaard' heeft de waarde 'ISO 19115' (`metadataStandardName`).

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115 — dataset metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over metadataStandardName.*

### `geo-meta-0013` — SKILL.md:65 *(§ Verplichte elementen (dataset))*

> Het verplichte element 'Metadata-taal' heeft de waarde 'dut' of 'nld' (`language`).

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115 — dataset metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over metadata-taal.*

### `geo-meta-0016` — SKILL.md:233 *(§ Veelvoorkomende Problemen)*

> In CSW CQL-syntax wordt het procent-teken (%) gebruikt als wildcard bij `AnyText like '%term%'`.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** CSW — CQL query syntax

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over CSW CQL-syntax.*

### `geo-meta-0027` — SKILL.md:232 *(§ Veelvoorkomende Problemen)*

> Om metadata vindbaar te maken voor INSPIRE moeten INSPIRE-trefwoorden (GEMET thesaurus) worden toegevoegd.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** INSPIRE — metadata trefwoorden

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over INSPIRE-trefwoorden of GEMET thesaurus.*

### `geo-meta-0028` — reference.md:11 *(§ Dataset Metadata)*

> Het element `fileIdentifier` is verplicht, niet herhaalbaar, en bevat een unieke UUID van het metadata-record.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115 — volledige elementenlijst dataset

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over fileIdentifier.*

### `geo-meta-0029` — reference.md:12 *(§ Dataset Metadata)*

> Het element `language` (metadata-taal) is verplicht en niet herhaalbaar; waarde is 'dut' of 'nld'.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115 — volledige elementenlijst dataset

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over metadata-taal element.*

### `geo-meta-0030` — reference.md:13 *(§ Dataset Metadata)*

> Het element `characterSet` is conditioneel en niet herhaalbaar; de standaardwaarde is 'utf8'.

**Type:** normative_requirement  ·  **Modaliteit:** MAY  ·  **Scope:** Nederlands profiel ISO 19115 — volledige elementenlijst dataset

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over characterSet.*

### `geo-meta-0031` — reference.md:14 *(§ Dataset Metadata)*

> Het element `hierarchyLevel` is verplicht en niet herhaalbaar; mogelijke waarden zijn 'dataset', 'series' of 'service'.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115 — volledige elementenlijst dataset

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over hierarchyLevel.*

### `geo-meta-0032` — reference.md:15 *(§ Dataset Metadata)*

> Het element `contact` is verplicht en herhaalbaar; het bevat contactgegevens van de metadata-beheerder.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115 — volledige elementenlijst dataset

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over contact-element.*

### `geo-meta-0033` — reference.md:16 *(§ Dataset Metadata)*

> Het element `dateStamp` is verplicht, niet herhaalbaar, en heeft het formaat YYYY-MM-DD.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115 — volledige elementenlijst dataset

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over dateStamp.*

### `geo-meta-0034` — reference.md:17 *(§ Dataset Metadata)*

> Het element `metadataStandardName` is verplicht, niet herhaalbaar, en heeft de waarde 'ISO 19115'.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115 — volledige elementenlijst dataset

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over metadataStandardName.*

### `geo-meta-0035` — reference.md:19 *(§ Dataset Metadata)*

> Het element `referenceSystemInfo` is verplicht en herhaalbaar; het bevat het CRS, bijvoorbeeld EPSG:28992.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115 — volledige elementenlijst dataset

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over referenceSystemInfo.*

### `geo-meta-0036` — reference.md:21 *(§ Dataset Metadata)*

> Het element `distributionInfo` is verplicht en niet herhaalbaar in het NL profiel op ISO 19115.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115 — volledige elementenlijst dataset

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over distributionInfo.*

### `geo-meta-0037` — reference.md:35 *(§ Identificatie-elementen (MD_DataIdentification))*

> Het identificatie-element `descriptiveKeywords` (trefwoorden) is verplicht en vereist minstens 1 trefwoord.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115 — MD_DataIdentification

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over descriptiveKeywords.*

### `geo-meta-0038` — reference.md:36 *(§ Identificatie-elementen (MD_DataIdentification))*

> Het identificatie-element `resourceConstraints` (gebruiksbeperkingen) is verplicht.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115 — MD_DataIdentification

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over resourceConstraints.*

### `geo-meta-0039` — reference.md:38 *(§ Identificatie-elementen (MD_DataIdentification))*

> Het identificatie-element `spatialResolution` (schaal of grondresolutie) is verplicht.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115 — MD_DataIdentification

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over spatialResolution.*

### `geo-meta-0040` — reference.md:41 *(§ Identificatie-elementen (MD_DataIdentification))*

> Het identificatie-element `topicCategory` (ISO-categorie) is verplicht en vereist minstens 1 categorie.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115 — MD_DataIdentification

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over topicCategory.*

### `geo-meta-0041` — reference.md:42 *(§ Identificatie-elementen (MD_DataIdentification))*

> Het identificatie-element `extent` (ruimtelijke en temporele dekking) is verplicht.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115 — MD_DataIdentification

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over extent-element.*

### `geo-meta-0042` — reference.md:66 *(§ Service Metadata (ISO 19119))*

> Voor service metadata (ISO 19119) is het element `serviceType` verplicht; waarden zijn OGC:WMS, OGC:WFS, OGC:CSW, etc.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** ISO 19119 — service metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over serviceType voor ISO 19119.*

### `geo-meta-0043` — reference.md:67 *(§ Service Metadata (ISO 19119))*

> Voor service metadata is het element `serviceTypeVersion` (versie van het service-protocol) verplicht.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** ISO 19119 — service metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over serviceTypeVersion.*

### `geo-meta-0044` — reference.md:68 *(§ Service Metadata (ISO 19119))*

> Voor service metadata is het element `couplingType` verplicht; mogelijke waarden zijn 'tight', 'mixed' of 'loose'.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** ISO 19119 — service metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over couplingType.*

### `geo-meta-0045` — reference.md:69 *(§ Service Metadata (ISO 19119))*

> Voor service metadata is het element `containsOperations` (operaties zoals GetCapabilities, GetMap) verplicht.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** ISO 19119 — service metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over containsOperations.*

### `geo-meta-0046` — reference.md:70 *(§ Service Metadata (ISO 19119))*

> Voor service metadata is het element `operatesOn` (link naar dataset-metadata) conditioneel.

**Type:** normative_requirement  ·  **Modaliteit:** MAY  ·  **Scope:** ISO 19119 — service metadata

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over operatesOn.*

### `geo-meta-0047` — reference.md:77 *(§ Structurele validatie)*

> Metadata moet voldoen aan het ISO 19115 XML-schema (gmd namespace) voor structurele validatie.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** ISO 19115 — structurele validatie

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over ISO 19115 XML-schema validatie.*

### `geo-meta-0048` — reference.md:88 *(§ Inhoudelijke validatie (NL profiel))*

> Bij inhoudelijke validatie (NL profiel) moet de samenvatting minimaal 25 tekens bevatten.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115 — inhoudelijke validatie

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over inhoudelijke validatieregels.*

### `geo-meta-0049` — reference.md:89 *(§ Inhoudelijke validatie (NL profiel))*

> Bij inhoudelijke validatie moeten contactgegevens een organisatienaam en e-mailadres bevatten.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115 — inhoudelijke validatie

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over contactgegevens-eisen.*

### `geo-meta-0050` — reference.md:90 *(§ Inhoudelijke validatie (NL profiel))*

> De bounding box moet binnen of gelijk aan Nederland vallen (lat: 50.75-53.47, lon: 3.37-7.21) of breder zijn.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Nederlands profiel ISO 19115 — inhoudelijke validatie

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/md/](https://docs.geostandaarden.nl/md/)
  - *De brontekst is uitsluitend een directory-index zonder specificatie-inhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/mim/](https://docs.geostandaarden.nl/mim/)
  - *De brontekst is een directorylijst van /mim/. Bevat geen informatie over bounding box-eisen.*

## GROUNDED — minstens één bron ondersteunt de claim (2)

<details>
<summary>Klap uit voor alle GROUNDED claims</summary>

### `geo-meta-0003` — SKILL.md:22 *(§ Metadata voor Geodata)*

> Geonovum beheert het Nederlands profiel op ISO 19115/19119 als basis voor alle metadata.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Nederlands profiel ISO 19115/19119

- **SUPPORTED** (high) — [https://docs.geostandaarden.nl/md/mdprofiel-iso19115](https://docs.geostandaarden.nl/md/mdprofiel-iso19115)
  > Geonovum ontwikkelt en beheert de Nederlandse metadata profielen. Deze profielen zijn een verbijzondering van de internationale metadatastandaarden van ISO en zijn bedoeld om de interoperabiliteit binnen Nederland te bevorderen.

### `geo-meta-0008` — SKILL.md:44 *(§ Nederlands Profiel ISO 19115)*

> Het Nederlands profiel specificeert welke metadata-elementen verplicht, conditioneel of optioneel zijn voor Nederlandse geodatasets.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Nederlands profiel ISO 19115

- **SUPPORTED** (high) — [https://docs.geostandaarden.nl/md/mdprofiel-iso19115](https://docs.geostandaarden.nl/md/mdprofiel-iso19115)
  > In de volgende tabel staan de verplichte of bij conditie verplichte elementen. [...] Naast de verplichte kernset heeft dit metadata profiel tevens een optionele set.
  - *De bron bevat een uitgebreide tabel (hoofdstuk 5.1) met verplichte (V), conditionele (C) en optionele elementen voor Nederlandse geodatasets, wat de claim volledig ondersteunt.*

</details>
