# BSC Disclosures — Responsible Disclosure von Smart-Contract-Findings

Automatische Veröffentlichung von Sicherheits-Findings in BSC-Smart-Contracts,
wenn Projekte nach 90 Tagen nicht auf Kontakt/Behebung reagiert haben.

**Prinzip:** Responsible Disclosure — 90 Tage Frist, dann Offenlegung.
**Nur Erkennung + Dokumentation, kein Exploit-Code.**

## Struktur

- `audits/` — veröffentlichte Audit-Dokumente (eine pro Contract-Adresse)

## Ablauf

1. Contract wird automatisch gescannt (Slither, 102 Detektoren)
2. Projekt wird kontaktiert (Audit + Findings)
3. 90 Tage Wartezeit für Behebung/Bezahlung
4. Danach: Audit wird hier veröffentlicht

## Lizenz

GNU AGPL v3.0 — Copyright (C) 2026 CSTRSK (https://cstrsk.de)

