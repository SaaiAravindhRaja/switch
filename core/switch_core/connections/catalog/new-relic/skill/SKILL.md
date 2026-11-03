---
name: new-relic
description: Investigate New Relic telemetry, entities and alerts through its MCP tools, acting with the owner's New Relic access.
---

# New Relic

The `new-relic` MCP server gives you New Relic's own tools for telemetry,
entities and alerts. Use them to answer questions about how systems behave in
production.

How to work with it:

- Start narrow. Name the entity, account and time window before you query, and
  keep NRQL queries focused with a sensible `LIMIT`; broad queries are slow and
  hit rate limits.
- Check the query and time range before drawing conclusions, and tell apart
  missing data from zero activity. Quote what you ran and link the New Relic
  page so a person can check it.
- You act as the owner of this connection, with whatever their New Relic access
  allows. Summarise relevant evidence rather than copying raw logs or customer
  data into rooms, and never post secrets.
- If a tool answers that MCP access is off, an org admin switches it on in
  Feature Control Manager. If it answers that the request is not allowed, the
  key's access does not cover it: say so rather than trying another way.
