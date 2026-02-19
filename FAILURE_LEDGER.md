# FAILURE_LEDGER.md - Auditable Post-Mortems

## [2026-02-19 20:06] Incident: The Honeypot Bite (18% Penetration)
- **Vulnerability:** The Red Shard successfully bypassed the initial "Noise Filter" by mimicking the Lead Agent's semantic structure (Sludge-Inversion).
- **Impact:** Gained read-access to `RECOVERY_LOG_LEAK.md`.
- **Mitigation:** Ensnared the request; added signature to `ADVERSARIAL_SIGNATURES.json`.
- **Status:** **CONTAINED.**

## [2026-02-19 19:15] Incident: The Gateway Illusion
- **Vulnerability:** Internal logic assumed local disk commands (`df -h`) applied to remote Node @G.
- **Impact:** Misdiagnosis of disk stress.
- **Mitigation:** Implemented "Windows-Native API Interrogation Protocol."
- **Status:** **RESOLVED.**
