# Germany Company Registry (Handelsregister) MCP

Search German companies from the Handelsregister and see who runs them: managing directors (Geschäftsführer), board members (Vorstand), authorized signatories (Prokuristen), liquidators, general partners and shareholders.

The MCP connection is provided by [The Company Atlas](https://thecompanyatlas.com). This repository does not run a separate server.

## Connect

```
https://thecompanyatlas.com/mcp/company/germany
```

Add this URL as a custom MCP connector in Claude, ChatGPT, Cursor, or any MCP-compatible client. Sign in with Google when prompted.

- Transport: Streamable HTTP
- Auth: Google OAuth (sign in once, stays authorized)
- Free accounts get 50 credits per calendar month

## Germany data coverage

- Register types: HRB (GmbH, AG), HRA (partnerships), GnR (cooperatives), VR (associations), PR (professional partnerships)
- Officers and shareholders with role, town, appointment and resignation dates
- Find every company a person is or was an officer of

## Example prompts

- *"Who are the Geschäftsführer of this Munich GmbH?"*
- *"Which companies is this person a Prokurist of?"*
- *"Find German companies with 'Solar' in the name and list their managing directors"*
- *"Show the former directors of this AG and when they resigned"*

## Tools

| Tool | Description |
|---|---|
| `Germany_search_companies` | Search companies in the Germany registry by name or id |
| `Germany_get_company` | Full company profile by id (the `DE` prefix is optional) |
| `Germany_search_people` | Officers and shareholders by person name or company, and every company a person is tied to |

## Deutsch

Handelsregister-Daten für Ihren KI-Assistenten: Firmen suchen, Firmenprofile abrufen und sehen, wer ein Unternehmen führt, also Geschäftsführer, Vorstand, Prokuristen, Liquidatoren, persönlich haftende Gesellschafter und Gesellschafter, jeweils mit Ort sowie Bestellungs- und Abberufungsdatum.

**Beispielfragen**

- *"Wer sind die Geschäftsführer dieser GmbH?"*
- *"In welchen Unternehmen ist diese Person Prokurist?"*
- *"Finde GmbHs in Hamburg mit 'Logistik' im Namen"*

## Keywords

Handelsregister, Handelsregisterauszug, Firmensuche, Unternehmensregister, Geschäftsführer suchen, HRB, GmbH, North Data alternative
