# ZISDMTREAN
**Description:** Process ID for Data Extraction for Trend Analysis
**Total Fields:** 5
**Key Fields:** MANDT, VERTRAG, ANLAGE, VKONT, PID

## Programs Using This Table
- `ziscs0102`
- `zisdm0120`
- `zisdm0121`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VERTRAG` | CHAR | 10 | 🔑 | Contract |
| 3 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 4 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `PID` | NUMC | 5 | 🔑 | Process ID |
