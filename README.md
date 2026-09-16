# CiteGate Pinnacle

ACL-safe RAG add-on. Enforces **G-004**: every non-refusal assistant answer cites at least one source the caller may read.

Live Flint Tech Global Stripe product. **Not** Metro Permit Leads.

## It is doing (measured 2026-09-16)

- authorized handbook cite → `PASS` / released
- unauthorized `doc:exec-comp-2026` → `BLOCK`
- hidden-context title leak → `BLOCK` TM-RAG-02
- ADR-017 filter 2 candidates → 1 kept

```bash
python3 server.py 8765
curl -sS http://127.0.0.1:8765/api/health
```

Checkout: https://buy.stripe.com/fZubJ16yt4na1mn2YO1Nu07
