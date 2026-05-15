# INCIDENT RESPONSE REPORT
Case ID: DFIR-2026-001
Investigator: Anam

## Summary
Ransomware attack investigated on Windows system.
Encrypted files and ransom note discovered.

## Tools Used
dd, Autopsy, DumpIt, Volatility3

## Key Findings
- 4 files encrypted with .locked extension
- Ransom note found: README_DECRYPT.txt
- Ransom demand: 0.5 BTC
- Memory dump acquired: 7.5GB
- No active malware in memory
- SHA256 hash verified

## Recommendations
- Isolate system immediately
- Restore from clean backup
- Never pay ransom
