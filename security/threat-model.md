# KODEX-VisionFit Threat Model

## Boundaries & STRIDE Analysis
- **Browser to API:** Focus on spoofing, tampering, and session replay.
- **API to AI Gateway:** Focus on prompt injection, tool abuse, and cost exhaustion.
- **Tenant Isolation:** Focus on brand_id tampering and cross-tenant data access.

## Al & LLM Threats
1. Prompt Injection via user prompts or product descriptions.
2. Unauthorized tool calls outside the explicit allowlist.
3. Sensitive output leakage of raw measurements.
