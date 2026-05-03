# TheSports

TheSports provides real-time sports data feeds, live trackers, and widgets covering football, basketball, tennis, esports, and other major sports worldwide. Their API delivers live scores, match statistics, player data, standings, and comprehensive sports analytics for media, broadcasters, OTT platforms, and developers.

**Website:** [https://www.thesports.com/](https://www.thesports.com/)

## APIs

| Name | Description | Documentation |
|------|-------------|---------------|
| [TheSports Football API](https://www.thesports.com/) | Real-time football data feeds covering competitions, teams, players, matches, live scores, lineups, statistics, and standings worldwide. | [Docs](https://www.thesports.com/docs) |
| [TheSports Basketball API](https://www.thesports.com/) | Real-time basketball data for NBA, EuroLeague, and other major leagues. | [Docs](https://www.thesports.com/docs) |
| [TheSports Tennis API](https://www.thesports.com/) | Tennis data for ATP, WTA, and Grand Slam tournaments. | [Docs](https://www.thesports.com/docs) |
| [TheSports Esports API](https://www.thesports.com/) | Esports data for CS:GO, League of Legends, and other major titles. | [Docs](https://www.thesports.com/docs) |

## Common Resources

- **Documentation:** [https://www.thesports.com/docs](https://www.thesports.com/docs)
- **Sign Up:** [https://www.thesports.com/register](https://www.thesports.com/register)
- **Pricing / Free Trial:** [https://www.thesports.com/api](https://www.thesports.com/api)

## OpenAPI Specifications

| File | Description |
|------|-------------|
| [thesports-football-openapi.yml](openapi/thesports-football-openapi.yml) | TheSports Football API - competitions, teams, players, matches, standings |

## JSON Schemas

| File | Description |
|------|-------------|
| [thesports-match-schema.json](json-schema/thesports-match-schema.json) | Football match schema |
| [thesports-team-schema.json](json-schema/thesports-team-schema.json) | Football team schema |

## JSON Structures

| File | Description |
|------|-------------|
| [thesports-match-structure.json](json-structure/thesports-match-structure.json) | Match data structure documentation |

## JSON-LD

| File | Description |
|------|-------------|
| [thesports-context.jsonld](json-ld/thesports-context.jsonld) | JSON-LD context mapping sports vocabulary to schema.org |

## Examples

| File | Description |
|------|-------------|
| [thesports-list-competitions-example.json](examples/thesports-list-competitions-example.json) | List competitions request/response |
| [thesports-get-match-details-example.json](examples/thesports-get-match-details-example.json) | Get match details request/response |
| [thesports-get-standings-example.json](examples/thesports-get-standings-example.json) | Get standings request/response |

## Spectral Rules

| File | Description |
|------|-------------|
| [thesports-rules.yml](rules/thesports-rules.yml) | Spectral ruleset enforcing TheSports API conventions |

## Naftiko Capabilities

### Shared Definitions

| File | Description |
|------|-------------|
| [capabilities/shared/football-api.yaml](capabilities/shared/football-api.yaml) | Per-API consumed definition for TheSports Football API |

### Workflow Capabilities

| File | Description | Tools |
|------|-------------|-------|
| [capabilities/sports-data.yaml](capabilities/sports-data.yaml) | Sports data retrieval for competitions, teams, matches, and standings | 11 tools |

## Vocabulary

| File | Description |
|------|-------------|
| [thesports-vocabulary.yml](vocabulary/thesports-vocabulary.yml) | Domain vocabulary for sports data concepts |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

---

*Profiled by [API Evangelist](https://apievangelist.com) on 2026-05-03*
