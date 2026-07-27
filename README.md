# Gardin

Gardin is a UK agritech company (Abingdon, Oxfordshire) whose product, **Gardin Pulse**, is a real-time plant-level crop intelligence platform built on an optical sensor that measures chlorophyll fluorescence to assess photosynthetic efficiency.

Gardin exposes plant-health data through the **Gardin API** — OAuth2 client-credentials-secured HTTP services:

- **Query API** — asynchronous bulk download of chlorophyll-fluorescence (ChF) and Gardin-indices data (submit → poll → download CSV).
- **Sensor Management API** — device registry, grouping, measurement/pick-poses jobs, schedules.
- **Notification API** — real-time plant-health alerts over webhooks and websockets (HMAC-SHA256 signed).

Developer portal: https://developers.gardin.ag/ · Status: https://status.gardin.ag/ · GitHub: https://github.com/gardinltd

Backed by: seedcamp — https://gardin.ag/
