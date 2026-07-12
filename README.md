# Utility Converter MCP Server

A simple remote MCP server (Streamable HTTP, no authentication) providing 7 everyday utility tools.

## Tools

- `get_exchange_rate` — Latest currency exchange rates (Frankfurter API)
- `generate_uuid` — Generate random UUID v4 strings
- `hash_text` — MD5 / SHA1 / SHA256 / SHA512 text hashing
- `encode_decode_base64` — Base64 encode / decode
- `convert_timestamp` — Unix timestamp ↔ human-readable datetime
- `calculate` — Safe arithmetic expression evaluator
- `convert_units` — Length / weight / temperature unit conversion

## Run

```bash
pip install -r requirements.txt
python server.py
```

Endpoint: `http://localhost:8000/mcp`
