# ZISDMRCDUN
**Description:** Mapping Register Type & UOM to CISS Record Unit
**Total Fields:** 5
**Key Fields:** MANDT, ZWART, ZWTYP, MASSREAD

## Programs Using This Table
- `zisdm0019`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZWART` | CHAR | 2 | 🔑 | Register type |
| 3 | `ZWTYP` | CHAR | 2 | 🔑 | Register Category |
| 4 | `MASSREAD` | UNIT | 3 | 🔑 | Unit of measurement for meter reading |
| 5 | `ZZRCDUNIT` | CHAR | 3 |  | CISS Record Unit |
