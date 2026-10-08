# Twilio Flex + Multiple WABAs reference blueprint

[View the published blueprint](https://rbangueses.github.io/flex-multi-waba-reference-blueprint/)

[View the customer-facing high-level design](https://rbangueses.github.io/flex-multi-waba-reference-blueprint/high-level-design.html)

## What the blueprint covers

- One Flex hub with multiple WABA-specific Twilio subaccounts
- Inbound and outbound message paths
- Queue-based, context-based, agent-selectable and hybrid sender assignment
- The data needed to keep each task, conversation and message tied to the correct WABA
- Template discovery and the WhatsApp 24-hour customer service window
- Account responsibilities, credentials and webhook validation
- Adding or removing WABAs, acceptance tests and go-live checks

This is a solution pattern, not a deployable Flex plugin or a statement that the example integration endpoints are provided by Twilio.
