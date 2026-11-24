# Trade Oracle V2 — Unified International Trade MCP Hub

Deterministic, zero-hallucination Model Context Protocol (MCP) gateway for EU TARIC Customs, CBAM & Anti-Dumping, PRC GACC/PIPL/MOFCOM regulations, Maritime FuelEU/ETS carbon compliance, and EU/US Sanctions screening.

## Available Tools (23 Deterministic Tools)
- **EU Customs**: TARIC classification, duty/VAT calculation, CBAM, Anti-dumping (C-codes).
- **PRC Compliance**: GACC import taxes, CCC/NMPA/CIFER clearances, MOFCOM export controls, GB standards.
- **Maritime Decarbonisation**: FuelEU pool optimizer, ETS surrender obligations, GHG intensity.
- **Sanctions & Export Controls**: OFAC (US), EU 833/2014, BIS EAR (15 CFR).

## Configuration (MCP Clients)

Add this server to your Claude Desktop, Cursor, or MCP-compatible client:

```json
{
  "mcpServers": {
    "trade-oracle": {
      "url": "https://mcp.trade-oracle.eu/mcp.php"
    }
  }
}