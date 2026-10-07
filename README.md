# Twilio Flex + Multiple WABAs reference blueprint

This repository contains a self-contained reference-architecture page for a hub-and-spoke approach to connecting one Twilio Flex account to multiple WhatsApp Business Accounts.

Open [`index.html`](./index.html) directly, or preview it through any static web server:

```bash
python3 -m http.server 4173
```

Then visit:

```text
http://localhost:4173/
```

The page has no external runtime dependencies and can be published on GitHub Pages or another static host as-is.

## What the blueprint covers

- One Flex hub with N WABA-specific Twilio subaccount spokes
- Inbound and outbound message paths
- Queue-bound, context-derived, agent-selectable and hybrid sender policies
- A canonical WABA context contract
- Per-subaccount template discovery and the WhatsApp 24-hour service window
- Data ownership, security, reliability and long-lived task handling
- Production checklist and logical reference endpoints

This is a solution pattern, not a deployable Flex plugin or a statement that the logical reference endpoints are provided out of the box by Twilio.
