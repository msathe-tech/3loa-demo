# Zero-Trust ADK Agent — 3-Legged OAuth2 Updates via Managed Agent Gateway

Updates below were executed by Vertex AI Agent Engine (`AGENT_IDENTITY`) egressing through **GCP Managed Agent Gateway** using the signed-in human operator's **3-Legged OAuth2 GitHub credential** from **GCP Auth Manager** after explicit Human-in-the-Loop confirmation (zero tokens in LLM context).

| Timestamp (UTC) | GitHub 3LO User | HITL Approver | Update Text | Egress Governance | Agent SPIFFE Identity |
| :--- | :--- | :--- | :--- | :--- | :--- |
| `2026-11-14T00:11:16Z` | `@msathe-tech` | `operator-console` | Release check passed | `Managed Agent Gateway` | `spiffe://agents.global.org-454101079359.system.id.goog/resources/aiplatform/projects/633964655923/locations/us-central1/reasoningEngines/3773745183242321920` |
| `2026-11-14T00:14:21Z` | `@msathe-tech` | `operator-console` | Hello from Zero-Trust ADK Agent | `Managed Agent Gateway` | `spiffe://agents.global.org-454101079359.system.id.goog/resources/aiplatform/projects/633964655923/locations/us-central1/reasoningEngines/3773745183242321920` |
| `2026-11-16T16:41:01Z` | `@msathe-tech` | `operator-console` | Release check passed | `Managed Agent Gateway` | `spiffe://agents.global.org-454101079359.system.id.goog/resources/aiplatform/projects/633964655923/locations/us-central1/reasoningEngines/3773745183242321920` |
| `2026-11-16T16:45:16Z` | `@msathe-tech` | `operator-console` | Release check passed | `Managed Agent Gateway` | `spiffe://agents.global.org-454101079359.system.id.goog/resources/aiplatform/projects/633964655923/locations/us-central1/reasoningEngines/3773745183242321920` |
