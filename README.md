# MedVault — Phase 1 Web App

Patient-owned encrypted health records for Pakistan. Mate Technologies.

- **index.html** — the patient app (PIN-derived AES-256-GCM vault, timeline, trends, emergency card, QR consent sharing, email sign-in + sync via Supabase)
- **gateway.html** — the clinician consent gateway (scoped read-only sessions, live audit logging, instant revocation lockout)

Backend: Supabase (schema + consent API deployed separately). The keys embedded here are the project's public client keys; row-level security and client-side encryption are the security boundary.

Hosted via GitHub Pages: https://asimshafi.github.io/medvault-app/