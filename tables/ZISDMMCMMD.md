# ZISDMMCMMD
**Description:** Master Check Installation Master Data Table
**Total Fields:** 8
**Key Fields:** MANDT, ZZMCMANLAGE, ZZANLAGE

## Programs Using This Table
- `zisdm0084`
- `zisdm0155`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZMCMANLAGE` | CHAR | 10 | 🔑 | The ID of the Master Check Installation |
| 3 | `ZZANLAGE` | CHAR | 10 | 🔑 | Installation under MCM monitoring |
| 4 | `ZZVOLTAGE` | NUMC | 7 |  | Voltage |
| 5 | `ZZRPREGION` | CHAR | 8 |  | Regional structure grouping |
| 6 | `ZZMRUOFMCM` | CHAR | 8 |  | MRU of Master Check Installation |
| 7 | `ZZCONOBJT` | CHAR | 10 |  | Connection Object of installation under MCM |
| 8 | `ZZMRUOFIND` | CHAR | 8 |  | MRU of Individual Installation |
