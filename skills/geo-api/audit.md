<!-- markdownlint-disable MD052 MD034 MD013 MD038 -->
# Audit geo-api — 2026-05-17

> Automatisch gegenereerd door audit-tooling. Niet handmatig bewerken; wijzig SKILL.md / reference.md en regenereer.

## Samenvatting

| Status | Aantal | % |
|--------|--------|---|
| UNSUPPORTED_ASSERTION | 9 | 27% |
| CONTRADICTED | 1 | 3% |
| PARTIALLY_GROUNDED | 7 | 21% |
| UNGROUNDED | 7 | 21% |
| NO_SOURCE | 0 | 0% |
| UNVERIFIABLE | 0 | 0% |
| KNOWN_DISCREPANCY | 0 | 0% |
| GROUNDED | 9 | 27% |

*Geverifieerd met sonnet, 11 calls, $0.9129.*

## UNSUPPORTED_ASSERTION — stellige bewering zonder enige bronsteun (mogelijke hallucinatie) (9)

### `geo-api-0004` — SKILL.md:24 *(§ OGC API Services & Kaartdiensten)*

> Geonovum beheert de Nederlandse profielen en de ogc-checker validatietool.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Geonovum — ogc-checker

<details><summary>3x NOT_FOUND (klap uit)</summary>

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *Geonovum en ogc-checker worden niet vermeld in de directory-index.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *Geonovum wordt enkel vermeld als editor, niet als beheerder van profielen of ogc-checker.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  - *De ogc-checker of Geonovum's beheersrol over Nederlandse profielen en validatietool worden niet vermeld in de bron.*
</details>

### `geo-api-0005` — SKILL.md:30 *(§ Standaarden Overzicht)*

> OGC API Features is een REST-gebaseerde opvolger van WFS met JSON/GeoJSON en heeft Forum-status 'Verplicht'.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** OGC API Features — Forum Standaardisatie

<details><summary>3x NOT_FOUND (klap uit)</summary>

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *De brontekst bevat geen inhoudelijke informatie over OGC API Features.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *OGC API Features wordt niet behandeld in deze bron.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  - *OGC API Features als REST-opvolger van WFS wordt niet als zodanig beschreven en Forum-status 'Verplicht' staat niet in de bron.*
</details>

### `geo-api-0006` — SKILL.md:31 *(§ Standaarden Overzicht)*

> OGC API Tiles is de opvolger van WMTS voor voorgerenderde kaarttegels en heeft Forum-status 'Verplicht'.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** OGC API Tiles — Forum Standaardisatie

<details><summary>3x NOT_FOUND (klap uit)</summary>

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *De brontekst bevat geen inhoudelijke informatie over OGC API Tiles.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *OGC API Tiles wordt niet behandeld in deze bron.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  - *OGC API Tiles en WMTS worden niet besproken in de bron.*
</details>

### `geo-api-0007` — SKILL.md:32 *(§ Standaarden Overzicht)*

> WMS 1.3.0 heeft Forum-status 'Aanbevolen' en wordt gebruikt voor het opvragen van kaartafbeeldingen (PNG/JPEG).

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** WMS 1.3.0 — Forum Standaardisatie

<details><summary>3x NOT_FOUND (klap uit)</summary>

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *De brontekst bevat geen inhoudelijke informatie over WMS 1.3.0 of Forum status.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *WMS 1.3.0 wordt niet behandeld in deze bron.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  - *WMS 1.3.0 en Forum-status 'Aanbevolen' worden niet besproken in de bron.*
</details>

### `geo-api-0008` — SKILL.md:33 *(§ Standaarden Overzicht)*

> WFS 2.0 heeft Forum-status 'Aanbevolen' en wordt gebruikt voor het opvragen van vector features (GML/GeoJSON).

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** WFS 2.0 — Forum Standaardisatie

<details><summary>3x NOT_FOUND (klap uit)</summary>

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *De brontekst bevat geen inhoudelijke informatie over WFS 2.0 of Forum status.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *WFS 2.0 wordt niet behandeld in deze bron.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  - *WFS 2.0 en Forum-status 'Aanbevolen' worden niet besproken in de bron.*
</details>

### `geo-api-0009` — SKILL.md:34 *(§ Standaarden Overzicht)*

> WCS 2.0 heeft geen Forum Standaardisatie status en wordt gebruikt voor het ophalen van rasterdata (gridded data).

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** WCS 2.0 — Forum Standaardisatie

<details><summary>3x NOT_FOUND (klap uit)</summary>

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *WCS 2.0 wordt niet vermeld in de directory-index.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *WCS 2.0 wordt niet behandeld in deze bron.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  - *WCS 2.0 en rasterdata worden niet besproken in de bron.*
</details>

### `geo-api-0010` — SKILL.md:35 *(§ Standaarden Overzicht)*

> GeoPackage 1.3.1 heeft Forum-status 'Verplicht' en is een SQLite-gebaseerd bestandsformaat voor lokale opslag van vector- en rasterdata.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** GeoPackage 1.3.1 — Forum Standaardisatie

<details><summary>3x NOT_FOUND (klap uit)</summary>

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *GeoPackage wordt niet vermeld in de directory-index.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *GeoPackage wordt niet behandeld in deze bron.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  - *GeoPackage wordt niet vermeld in de bron.*
</details>

### `geo-api-0012` — SKILL.md:48 *(§ WMS (Web Map Service))*

> WMS ondersteunt drie operaties: GetCapabilities, GetMap en GetFeatureInfo.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** WMS — operaties

<details><summary>3x NOT_FOUND (klap uit)</summary>

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *WMS-operaties worden niet beschreven in de directory-index.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *WMS-operaties worden niet behandeld in deze bron.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  - *WMS-operaties (GetCapabilities, GetMap, GetFeatureInfo) worden niet besproken in de bron.*
</details>

### `geo-api-0013` — SKILL.md:77 *(§ WFS (Web Feature Service))*

> WFS ondersteunt de operaties GetCapabilities, DescribeFeatureType en GetFeature.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** WFS — operaties

<details><summary>3x NOT_FOUND (klap uit)</summary>

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *WFS-operaties worden niet beschreven in de directory-index.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *WFS-operaties worden niet behandeld in deze bron.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  - *WFS-operaties worden niet besproken in de bron.*
</details>

## CONTRADICTED — bron spreekt de claim expliciet tegen (1)

### `geo-api-0019` — reference.md:12 *(§ Belangrijkste CRS-en in Nederland)*

> ETRS89 / UTM zone 31N heeft EPSG-code 25831 en wordt gebruikt voor INSPIRE en Europese data, met coördinaatvolgorde x, y (oost, noord) in meters.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** CRS — ETRS89

- **CONTRADICTED** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  > ETRS89 4258 latitude, longitude (φ, λ) 2D European
  - *De claim stelt ETRS89/UTM zone 31N met EPSG:25831, maar de bron beschrijft ETRS89 als EPSG:4258 (geografisch, lat/lon). EPSG:25831 (UTM zone 31N) wordt niet vermeld. De coördinaatvolgorde in de claim (x, y oost/noord in meters) klopt niet met de bron (lat, lon in graden).*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *ETRS89 / EPSG:25831 wordt niet vermeld in de directory-index.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *ETRS89 / UTM zone 31N (EPSG:25831) wordt niet behandeld in deze bron.*

## PARTIALLY_GROUNDED — bron ondersteunt deel van de claim (7)

### `geo-api-0003` — SKILL.md:24 *(§ OGC API Services & Kaartdiensten)*

> PDOK is het nationale portaal voor geo-webservices in Nederland.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** PDOK

- **PARTIALLY_SUPPORTED** (medium) — [https://www.pdok.nl/how-to-faq](https://www.pdok.nl/how-to-faq)
  > Iedereen mag kosteloos data afnemen bij PDOK. [...] Via PDOK kunnen diverse datasets worden "gedownload". [...] De Nederlandse geo-infrastructuur ontsluit gegevens middels een aantal Open Geospatial Consortium (OGC) standaarden.
  - *De bron beschrijft PDOK als een portaal voor open geodata en geo-webservices, maar gebruikt nergens expliciet de term 'nationaal portaal'. De rol als nationaal portaal is impliciet aanwezig maar niet letterlijk gesteld.*
<details><summary>3x NOT_FOUND (klap uit)</summary>

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *PDOK wordt niet genoemd in de directory-index.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *PDOK wordt niet vermeld in deze bron.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  - *PDOK wordt in de brontekst niet genoemd.*
</details>

### `geo-api-0011` — SKILL.md:41 *(§ Repositories)*

> De ogc-checker van Geonovum heeft versie v1.0.4 en is gepubliceerd onder EUPL-1.2 licentie.

**Type:** version_claim  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Geonovum ogc-checker

- **PARTIALLY_SUPPORTED** (high) — [https://raw.githubusercontent.com/Geonovum/ogc-checker/main/LICENSE](https://raw.githubusercontent.com/Geonovum/ogc-checker/main/LICENSE)
  > EUROPEAN UNION PUBLIC LICENCE v. 1.2 EUPL © the European Union 2007, 2016
  - *De bron bevestigt de EUPL-1.2 licentie, maar bevat geen informatie over versienummer v1.0.4. Versie-metadata staat zelden in de LICENSE-file zelf.*
- **PARTIALLY_SUPPORTED** (high) — [https://raw.githubusercontent.com/Geonovum/ogc-checker/master/LICENSE](https://raw.githubusercontent.com/Geonovum/ogc-checker/master/LICENSE)
  > EUROPEAN UNION PUBLIC LICENCE v. 1.2 EUPL © the European Union 2007, 2016
  - *De bron bevestigt de EUPL-1.2 licentie. De versieclaim 'v1.0.4' staat niet in de brontekst — een LICENSE-bestand bevat geen versie-metadata van de software zelf.*
<details><summary>3x NOT_FOUND (klap uit)</summary>

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *De ogc-checker versie en licentie worden niet vermeld in de directory-index.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *De ogc-checker van Geonovum wordt niet behandeld in deze bron.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  - *De ogc-checker, versienummer en licentie worden niet vermeld in de bron.*
</details>

### `geo-api-0017` — SKILL.md:270 *(§ Veelvoorkomende Problemen)*

> OGC API Features geeft HTML terug als er geen Accept-header wordt meegegeven; oplossing is `Accept: application/geo+json` header toevoegen.

**Type:** normative_requirement  ·  **Modaliteit:** SHOULD  ·  **Scope:** OGC API Features — content negotiation

- **PARTIALLY_SUPPORTED** (medium) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  > Note The Geospatial Module is focused on JSON-based encoding of data. However, consider also supporting text/html, as recommended in OGC API Features [ogcapi-features-1]. Sharing data on the Web should include publication in HTML, as this allows discovery of the data through common search engines as well as viewing the data directly in a browser.
  - *De bron bevestigt dat HTML ondersteund wordt in OGC API Features, maar zegt niets over het standaard gedrag zonder Accept-header (HTML teruggeven) of de aanbeveling om Accept: application/geo+json toe te voegen als oplossing.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *Content negotiation bij OGC API Features wordt niet behandeld in de directory-index.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *OGC API Features content negotiation wordt niet behandeld in deze bron.*

### `geo-api-0020` — reference.md:13 *(§ Belangrijkste CRS-en in Nederland)*

> WGS 84 heeft EPSG-code 4326, wordt gebruikt voor GPS en internationaal gebruik, met coördinaatvolgorde lat, lon (breedte, lengte) in graden.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** CRS — WGS 84

- **PARTIALLY_SUPPORTED** (medium) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  > WGS 84 longitude-latitude CRS84 longitude, latitude (λ, φ) 2D Global http://www.opengis.net/def/crs/OGC/1.3/CRS84
  - *De bron vermeldt WGS 84 maar koppelt het primair aan CRS84 (OGC) met lon/lat volgorde. EPSG:4326 met lat/lon volgorde voor GPS/internationaal gebruik wordt niet expliciet als zodanig beschreven. De bron noemt WGS 84 Pseudo Mercator EPSG:3857 apart.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *WGS 84 / EPSG:4326 wordt niet vermeld in de directory-index.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *WGS 84 (EPSG:4326) coördinaatvolgorde wordt niet behandeld in deze bron.*

### `geo-api-0022` — reference.md:15 *(§ Belangrijkste CRS-en in Nederland)*

> ETRS89 geografisch heeft EPSG-code 4258, is verplicht voor INSPIRE, en heeft coördinaatvolgorde lat, lon (breedte, lengte) in graden.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** CRS — ETRS89 geografisch, INSPIRE

- **PARTIALLY_SUPPORTED** (medium) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  > ETRS89 4258 latitude, longitude (φ, λ) 2D European
  - *De bron bevestigt EPSG:4258 en lat/lon volgorde voor ETRS89 geografisch. Dat het 'verplicht voor INSPIRE' is wordt niet in de bron vermeld.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *ETRS89 geografisch / EPSG:4258 wordt niet vermeld in de directory-index.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *ETRS89 geografisch (EPSG:4258) en INSPIRE worden niet behandeld in deze bron.*

### `geo-api-0032` — reference.md:93 *(§ OGC API Features Endpoints)*

> OGC API Features definieert de endpoints `/`, `/conformance`, `/collections`, `/collections/{id}`, `/collections/{id}/items`, `/collections/{id}/items/{featureId}` en `/api`.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** OGC API Features — endpoints

- **PARTIALLY_SUPPORTED** (medium) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  > According to OGC API Features - part 1 - 7.13. Feature collections an OGC API Features API shall provide a GET operation on the /collections endpoint which returns a collections object.
  - *De bron noemt `/collections` en `/collections/{id}` (storageCRS context) en `/collections/{id}/items` (via bbox-voorbeelden). De endpoints `/`, `/conformance`, `/collections/{id}/items/{featureId}` en `/api` worden niet expliciet als lijst opgesomd. De claim is gebaseerd op OGC API Features part 1 maar de bron vermeldt niet alle genoemde endpoints expliciet.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *OGC API Features endpoints worden niet behandeld in de directory-index.*
- **OUT_OF_SCOPE** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *De bron behandelt geen OGC API Features endpoints. De geospatiale module wordt slechts als verwijzing naar een extern document vermeld.*

### `geo-api-0033` — reference.md:101 *(§ OGC API Features Endpoints)*

> OGC API Features `/items` endpoint ondersteunt query parameters: `limit`, `bbox` (lon_min,lat_min,lon_max,lat_max), `datetime` (ISO 8601), `crs` (standaard CRS84) en additionele property-filters.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** OGC API Features — /items query parameters

- **PARTIALLY_SUPPORTED** (medium) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  > Support the OGC API Features part 1 bbox query parameter in conformance to the standard. [...] Support the OGC API Features part 2 crs parameter in conformance to the standard. [...] The default CRS, i.e. the CRS which is assumed when not specified by either the API or the client, is CRS84.
  - *De bron bevestigt `bbox` en `crs` als query parameters voor `/items`. De parameters `limit`, `datetime` en additionele property-filters worden in deze brontekst niet expliciet bij het `/items` endpoint vermeld, ook de exacte volgorde `lon_min,lat_min,lon_max,lat_max` voor bbox wordt niet letterlijk bevestigd (wel impliciet via OGC API Features conformance).*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *OGC API Features /items query parameters worden niet behandeld in de directory-index.*
- **OUT_OF_SCOPE** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *De bron behandelt geen OGC API Features `/items` endpoint of bijbehorende query parameters. Dit valt buiten de scope van de NLGov REST API Design Rules.*

## UNGROUNDED — geen bron ondersteunt de claim (7)

### `geo-api-0015` — SKILL.md:266 *(§ Veelvoorkomende Problemen)*

> Bij WMS 1.3.0 geeft een lege response bij bbox-filter een oorzaak: verkeerde coördinaatvolgorde. Voor EPSG:4326 is de asvolgorde lat/lon; voor EPSG:28992 is het x/y.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** WMS 1.3.0 — CRS coördinaatvolgorde

<details><summary>3x NOT_FOUND (klap uit)</summary>

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *Coördinaatvolgorde en bbox-problemen bij WMS 1.3.0 worden niet behandeld in de directory-index.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *WMS 1.3.0 coördinaatvolgorde wordt niet behandeld in deze bron.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  - *WMS 1.3.0 bbox-filter problemen en coördinaatvolgorde als debugtip worden niet besproken in de bron.*
</details>

### `geo-api-0024` — reference.md:26 *(§ Coördinaatvolgorde)*

> WMS 1.3.0 volgt de CRS-definitie voor asvolgorde: voor EPSG:4326 is dat lat/lon (y,x), voor EPSG:28992 is dat x,y.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** WMS 1.3.0 — coördinaatvolgorde

<details><summary>3x NOT_FOUND (klap uit)</summary>

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *WMS 1.3.0 coördinaatvolgorde wordt niet behandeld in de directory-index.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *WMS 1.3.0 coördinaatvolgorde wordt niet behandeld in deze bron.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  - *WMS 1.3.0 coördinaatvolgorde per CRS wordt niet besproken in de bron; de bron gaat over REST API / OGC API Features regels.*
</details>

### `geo-api-0025` — reference.md:27 *(§ Coördinaatvolgorde)*

> WFS 2.0 volgt de CRS-definitie voor asvolgorde, tenzij anders geconfigureerd.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** WFS 2.0 — coördinaatvolgorde

<details><summary>3x NOT_FOUND (klap uit)</summary>

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *WFS 2.0 coördinaatvolgorde wordt niet behandeld in de directory-index.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *WFS 2.0 coördinaatvolgorde wordt niet behandeld in deze bron.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  - *WFS 2.0 coördinaatvolgorde wordt niet besproken in de bron.*
</details>

### `geo-api-0028` — reference.md:62 *(§ WMS 1.3.0 Parameters)*

> WMS 1.3.0 GetMap vereist de parameters layers, crs, bbox (minx,miny,maxx,maxy), width/height en format.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** WMS 1.3.0 — GetMap parameters

<details><summary>1x NOT_FOUND + 2x OUT_OF_SCOPE (klap uit)</summary>

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *WMS 1.3.0 GetMap parameters worden niet behandeld in de directory-index.*
- **OUT_OF_SCOPE** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *De bron behandelt geen WMS 1.3.0 of GetMap parameters. Dit valt buiten de scope van de NLGov REST API Design Rules.*
- **OUT_OF_SCOPE** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  - *Deze bron gaat over de OGC API Features / REST API Geospatial module. WMS 1.3.0 GetMap parameters worden nergens behandeld.*
</details>

### `geo-api-0029` — reference.md:62 *(§ WMS 1.3.0 Parameters)*

> WMS 1.3.0 GetFeatureInfo vereist de parameters layers, crs, bbox, width/height, query_layers, i/j en info_format.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** WMS 1.3.0 — GetFeatureInfo parameters

<details><summary>1x NOT_FOUND + 2x OUT_OF_SCOPE (klap uit)</summary>

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *WMS 1.3.0 GetFeatureInfo parameters worden niet behandeld in de directory-index.*
- **OUT_OF_SCOPE** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *De bron behandelt geen WMS 1.3.0 of GetFeatureInfo parameters. Dit valt buiten de scope van de NLGov REST API Design Rules.*
- **OUT_OF_SCOPE** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  - *WMS 1.3.0 GetFeatureInfo wordt niet behandeld in deze bron.*
</details>

### `geo-api-0030` — reference.md:77 *(§ WFS 2.0 Parameters)*

> WFS 2.0 GetFeature vereist de parameter typeName; count, outputFormat, bbox, Filter en sortBy zijn optioneel.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** WFS 2.0 — GetFeature parameters

<details><summary>1x NOT_FOUND + 2x OUT_OF_SCOPE (klap uit)</summary>

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *WFS 2.0 GetFeature parameters worden niet behandeld in de directory-index.*
- **OUT_OF_SCOPE** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *De bron behandelt geen WFS 2.0 of GetFeature parameters. Dit valt buiten de scope van de NLGov REST API Design Rules.*
- **OUT_OF_SCOPE** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  - *WFS 2.0 GetFeature parameters worden niet behandeld in deze bron.*
</details>

### `geo-api-0031` — reference.md:77 *(§ WFS 2.0 Parameters)*

> WFS 2.0 DescribeFeatureType vereist de parameter typeName.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** WFS 2.0 — DescribeFeatureType parameters

<details><summary>1x NOT_FOUND + 2x OUT_OF_SCOPE (klap uit)</summary>

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *WFS 2.0 DescribeFeatureType parameters worden niet behandeld in de directory-index.*
- **OUT_OF_SCOPE** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *De bron behandelt geen WFS 2.0 of DescribeFeatureType parameters. Dit valt buiten de scope van de NLGov REST API Design Rules.*
- **OUT_OF_SCOPE** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  - *WFS 2.0 DescribeFeatureType wordt niet behandeld in deze bron.*
</details>

## GROUNDED — minstens één bron ondersteunt de claim (9)

<details>
<summary>Klap uit voor alle GROUNDED claims</summary>

### `geo-api-0001` — SKILL.md:22 *(§ OGC API Services & Kaartdiensten)*

> OGC API Features en OGC API Tiles zijn verplicht onder 'pas-toe-of-leg-uit' op forumstandaardisatie.nl.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** Forum Standaardisatie — OGC API Features, OGC API Tiles

- **SUPPORTED** (high) — [https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden](https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden)
  > Op 19 september 2024 stemde het OBDO in met het verplichten van OGC-API – Features Part 1: Core en Part 2: Coordinate Reference Systems by Reference en OGC-API – Tiles - Part 1: Core door plaatsing op de 'pas toe of leg uit'-lijst
<details><summary>4x NOT_FOUND (klap uit)</summary>

- **NOT_FOUND** (high) — [https://www.forumstandaardisatie.nl/open-standaarden](https://www.forumstandaardisatie.nl/open-standaarden)
  - *De brontekst bevat alleen navigatie-elementen en categoriekoppen van de pagina (zoals ''Pas toe of leg uit'-standaarden' en 'Aanbevolen standaarden'), maar geen concrete lijst van standaarden. OGC API Features en OGC API Tiles worden nergens genoemd.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *De brontekst is een directory-index van docs.geostandaarden.nl/api zonder inhoudelijke informatie over Forum Standaardisatie status.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *De bron is de NL GOV REST API Design Rules spec. Forum Standaardisatie-status van OGC API Features of OGC API Tiles wordt niet behandeld.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  - *De bron beschrijft de inhoud van de GEO module v1.0; Forum Standaardisatie 'pas-toe-of-leg-uit' status voor OGC API Features of OGC API Tiles wordt niet vermeld.*
</details>

### `geo-api-0002` — SKILL.md:22 *(§ OGC API Services & Kaartdiensten)*

> WMS en WFS zijn aanbevolen standaarden op het Forum Standaardisatie (sinds september 2024).

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** Forum Standaardisatie — WMS, WFS

- **SUPPORTED** (high) — [https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden](https://www.forumstandaardisatie.nl/open-standaarden/geo-standaarden)
  > Op 19 september 2024 stemde het OBDO in met... het aanbevelen van Nederlands WFS profiel 1.1 op ISO 19142 voor Web Feature Services 2.0, versie 1.1 (WFS) en Nederlands profiel op ISO 19128 Geographic information - Web Map Server Interface (WMS) door plaatsing op de lijst aanbevolen standaarden.
<details><summary>4x NOT_FOUND (klap uit)</summary>

- **NOT_FOUND** (high) — [https://www.forumstandaardisatie.nl/open-standaarden](https://www.forumstandaardisatie.nl/open-standaarden)
  - *De brontekst bevat geen concrete standaarden of datums. WMS en WFS worden niet vermeld. De pagina toont alleen navigatie en categoriekoppen, niet de daadwerkelijke lijstinhoud.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *De brontekst bevat geen informatie over WMS/WFS Forum Standaardisatie status.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *WMS en WFS worden niet vermeld in deze bron.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  - *WMS en WFS worden niet besproken in de context van Forum Standaardisatie aanbevelingen of statuswijzigingen.*
</details>

### `geo-api-0014` — SKILL.md:134 *(§ OGC API Features)*

> OGC API Features gebruikt JSON/GeoJSON, een OpenAPI-specificatie en standaard HTTP-methoden.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** OGC API Features

- **SUPPORTED** (medium) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  > For representing geometric information in an API, use the convention for describing geometry as defined in the GeoJSON format [rfc7946]. Support GeoJSON as described in OGC API Features part 4
  - *De bron bevestigt gebruik van JSON/GeoJSON en OGC API Features. OpenAPI-specificatie en standaard HTTP-methoden worden impliciet beschreven via OGC API Features conformiteit, maar niet expliciet als kenmerken van OGC API Features opgesomd.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *De brontekst bevat geen inhoudelijke informatie over OGC API Features technische details.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *OGC API Features wordt niet behandeld in deze bron.*

### `geo-api-0016` — SKILL.md:269 *(§ Veelvoorkomende Problemen)*

> PDOK-services zijn open en vereisen geen API-key.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** PDOK — toegang

- **SUPPORTED** (high) — [https://www.pdok.nl/how-to-faq](https://www.pdok.nl/how-to-faq)
  > Heb ik een gebruikersnaam en wachtwoord nodig voor het gebruik van PDOK services en/of downloads? Nee, iedereen heeft vrij toegang tot de open services en/of downloads van PDOK.
  - *De bron bevestigt expliciet dat geen inloggegevens nodig zijn. De claim spreekt over 'API-key' terwijl de bron 'gebruikersnaam en wachtwoord' noemt, maar de strekking is identiek: geen authenticatie vereist.*
<details><summary>3x NOT_FOUND (klap uit)</summary>

- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *PDOK-toegang en API-key vereisten worden niet vermeld in de directory-index.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *PDOK-toegang en API-keys worden niet behandeld in deze bron.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  - *PDOK-services en API-key vereisten worden niet vermeld in de bron.*
</details>

### `geo-api-0018` — reference.md:11 *(§ Belangrijkste CRS-en in Nederland)*

> RD New (Amersfoort) heeft EPSG-code 28992, wordt gebruikt voor Nederlandse kaarten en data, met coördinaatvolgorde x, y (oost, noord) in meters.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** CRS — RD New

- **SUPPORTED** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  > Amersfoort / RD New 28992 easting, northing (x, y) 2D Dutch http://www.opengis.net/def/crs/EPSG/9.9.1/28992
  - *De bron bevestigt EPSG-code 28992, Nederlandse scope, en coördinaatvolgorde x/y. 'In meters' staat niet expliciet maar is inherent aan RD New.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *RD New / EPSG:28992 wordt niet vermeld in de directory-index.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *RD New (EPSG:28992) wordt niet behandeld in deze bron.*

### `geo-api-0021` — reference.md:14 *(§ Belangrijkste CRS-en in Nederland)*

> CRS84 is het OGC API standaard CRS voor WGS 84 met coördinaatvolgorde lon, lat (lengte, breedte) in graden.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** CRS — CRS84, OGC API Features

- **SUPPORTED** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  > The default CRS for GeoJSON and for OGC API Features is CRS84 (OGC:CRS84), this CRS uses the WGS 84 datum with an ellipsoidal coordinate system in the order longitude-latitude.
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *CRS84 wordt niet vermeld in de directory-index.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *CRS84 en OGC API Features standaard CRS worden niet behandeld in deze bron.*

### `geo-api-0023` — reference.md:19 *(§ Coördinaatvolgorde)*

> EPSG:4326 en CRS84 verwijzen beide naar WGS 84 maar zijn niet inwisselbaar: EPSG:4326 heeft asvolgorde lat/lon, terwijl CRS84 (OGC:CRS84) lon/lat aanhoudt.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** CRS — EPSG:4326 vs CRS84

- **SUPPORTED** (medium) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  > The default CRS for GeoJSON and for OGC API Features is CRS84 (OGC:CRS84), this CRS uses the WGS 84 datum with an ellipsoidal coordinate system in the order longitude-latitude.
  - *De bron bevestigt impliciet het verschil: CRS84 heeft lon/lat volgorde. Dat EPSG:4326 lat/lon heeft en ze niet inwisselbaar zijn wordt ondersteund door de tabel (CRS84 = longitude-latitude) en de notitie 'Officially, WGS 84 longitude-latitude (OGC:CRS84) is the only CRS allowed in GeoJSON', maar de expliciete vergelijking met EPSG:4326 ontbreekt.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *Het verschil tussen EPSG:4326 en CRS84 wordt niet behandeld in de directory-index.*
- **NOT_FOUND** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *Het verschil tussen EPSG:4326 en CRS84 wordt niet behandeld in deze bron.*

### `geo-api-0026` — reference.md:28 *(§ Coördinaatvolgorde)*

> OGC API Features gebruikt standaard CRS84 (lon/lat); andere CRS zijn beschikbaar via de `crs` parameter.

**Type:** factual_assertion  ·  **Modaliteit:** STATEMENT  ·  **Scope:** OGC API Features — standaard CRS

- **SUPPORTED** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3](https://gitdocumentatie.logius.nl/publicatie/api/mod-geo/1.0.3)
  > The default CRS, i.e. the CRS which is assumed when not specified by either the API or the client, is CRS84, in line with GeoJSON and OGC API Features. [...] Support the OGC API Features part 2 crs parameter in conformance to the standard.
  - *De bron bevestigt CRS84 als standaard en de `crs` query parameter voor het specificeren van een alternatief CRS.*
- **NOT_FOUND** (high) — [https://docs.geostandaarden.nl/api/](https://docs.geostandaarden.nl/api/)
  - *OGC API Features standaard CRS wordt niet behandeld in de directory-index.*
- **OUT_OF_SCOPE** (high) — [https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0](https://gitdocumentatie.logius.nl/publicatie/api/adr/2.1.0)
  - *De bron is de NLGov REST API Design Rules 2.1.0. Deze behandelt geen OGC API Features, CRS84, of de `crs` parameter. De geospatiale module wordt enkel kort aangehaald als verwijzing naar een apart document.*

### `geo-api-0027` — reference.md:29 *(§ Coördinaatvolgorde)*

> GeoJSON (RFC 7946) gebruikt altijd lon/lat (WGS 84) als coördinaatvolgorde.

**Type:** normative_requirement  ·  **Modaliteit:** MUST  ·  **Scope:** GeoJSON — RFC 7946

- **SUPPORTED** (high) — [https://www.rfc-editor.org/rfc/rfc7946.txt](https://www.rfc-editor.org/rfc/rfc7946.txt)
  > The coordinate reference system for all GeoJSON coordinates is a geographic coordinate reference system, using the World Geodetic System 1984 (WGS 84) [WGS84] datum, with longitude and latitude units of decimal degrees. [...] The first two elements are longitude and latitude, or easting and northing, precisely in that order
  - *De bron bevestigt zowel WGS 84 als de lon/lat volgorde expliciet. De claim zegt 'altijd', wat overeenkomt met de normatieve tekst die stelt dat dit geldt voor 'all GeoJSON coordinates'.*

</details>
