# OpenMapp MCP

Remote MCP server for [OpenMapp](https://www.openmapp.com), a Brazilian Jiu-Jitsu gym map for the contiguous United States.

Endpoint (streamable HTTP, no auth): `https://www.openmapp.com/mcp`

Official registry name: `com.openmapp/openmapp`

## Tools

- `find_gyms` — gyms near a city, neighborhood, or ZIP
- `get_gym` — full public card: address, drop-in policy, visitor fee when known, weekly timetable
- `list_cities` — coverage by city and state
- `map_url` — OpenMapp map link

A drop-in price is a visitor day-pass, per-class fee, or weekly pass the gym published. Trials, memberships, and punch cards are not listed as the drop-in price. Unknown stays unknown.

This repo is the public listing package (manifest only). The site lives at [openmapp.com](https://www.openmapp.com).

## Listings

- [Official MCP Registry](https://registry.modelcontextprotocol.io/?search=openmapp)
- [Smithery](https://smithery.ai/servers/burmanharry/openmapp)
- [Glama](https://glama.ai/mcp/connectors/com.openmapp/openmapp)
