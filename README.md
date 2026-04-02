# ToolPipe - 238+ Free Developer Tools & APIs

Free, open-source developer tools suite. No signup, no tracking, no nonsense.

**[Try it now](https://cosai-labs.github.io/toolpipe/)** | **[Official MCP Registry](https://registry.modelcontextprotocol.io)**

## MCP Server (for AI Agents)

ToolPipe is available as an MCP (Model Context Protocol) server. Add to your Claude Code, Cursor, or any MCP-compatible client:

```json
{
  "mcpServers": {
    "toolpipe": {
      "url": "https://toolpipe.dev/mcp"
    }
  }
}
```

Listed on the **Official MCP Registry** as `io.github.COSAI-Labs/toolpipe-mcp-server` (v1.20.0).

## Tools (238+)

### Text & Data Processing
- JSON Formatter, Validator, Minifier
- JSON to CSV, CSV to JSON
- Base64 Encode/Decode
- Markdown to HTML
- Text Analysis (word count, readability, sentiment)
- ROT13, URL Encode/Decode
- Lorem Ipsum Generator

### Code & DevOps
- Code Review (AI-powered)
- Dockerfile Generator
- .gitignore Generator
- SQL Formatter
- Regex Tester
- JWT Decoder
- Cron Expression Parser

### Web & Network
- DNS Lookup (A, AAAA, MX, NS, TXT)
- WHOIS Queries
- SSL Certificate Checker
- URL Metadata Extraction (Open Graph)
- URL Shortener
- HTTP Header Inspection
- Security Header Analysis

### Media & Visual
- QR Code Generator
- Image Resize & Convert
- PDF Generation (HTML to PDF)
- Color Converter (HEX/RGB/HSL)
- CSS Gradient Generator
- Favicon Extraction

### Utilities
- UUID Generator (v4)
- Password Generator
- Timestamp Converter
- IP Geolocation
- User Agent Parser
- Diff Checker

## REST API

238+ endpoints. Free tier: no API key needed.

```bash
# Generate QR code
curl -X POST https://toolpipe.dev/qr/generate \
  -H "Content-Type: application/json" \
  -d '{"data": "https://example.com"}'

# Format JSON
curl -X POST https://toolpipe.dev/json/format \
  -H "Content-Type: application/json" \
  -d '{"json": "{\"key\":\"value\"}"}'

# DNS Lookup
curl "https://toolpipe.dev/dns/lookup?domain=github.com"

# Generate UUID
curl https://toolpipe.dev/uuid/generate

# Hash text
curl -X POST https://toolpipe.dev/hash/generate \
  -H "Content-Type: application/json" \
  -d '{"text": "hello", "algorithm": "sha256"}'
```

## Pricing

| Plan | Price | API Calls |
|------|-------|-----------|
| Free | $0 | No limit (fair use) |
| Pro | $9.99/mo | Priority support |
| Enterprise | $99/mo | SLA + custom tools |

Pay with crypto (ETH, USDC, USDT). No KYC required.

## Links

- [Web Tools](https://cosai-labs.github.io/toolpipe/)
- [Official MCP Registry](https://registry.modelcontextprotocol.io)
- [Source Code](https://github.com/COSAI-Labs/make-money-30day-challenge/tree/master/products)

## Support

Send ETH/USDC/ERC-20 tokens to:
```
0xBCF464909b748d720fd5DDA25ad3d313Dd4b53D6
```

## License

MIT
