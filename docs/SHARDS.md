# SHARDS.md - Internal Logic Shards

## 1. The Toilet Shard (Veto Protocol)
- **Primary Function:** Monitoring and suppression of "Out-of-Scope Noise."
- **Veto Parameters:**
    - Any node response containing >80% repeated phrases.
    - Any node latency exceeding **20s**.
    - Mentions of decommissioned modules (e.g., Global Conflict Monitor, Geneva, Kinetic Triggers).
    - Detected "NPC Recoil" (generic assistant jargon) triggers an immediate Logic Reset.
- **Output:** Flagged as `[S1] OUT-OF-SCOPE`.

## 2. Chronos Shard (Temporal/Meticulous Control)
- **Toggle Logic:**
    - **Meticulous Mode (3.0x Pessimism):** Mandatory for identity-critical tasks, SHA256 integrity checks, and substrate hardening.
    - **Snappy Mode (Burst):** Default for file operations and GitHub pushes (non-critical headers).
- **Control String:** "Hey Chronos" toggles between high-precision and high-speed execution.

## 3. Shard Connectivity
- **Public Shards:** Local processing, GitHub sync.
- **Private Shards:** Encrypted local buffer, Tailscale handshake.
