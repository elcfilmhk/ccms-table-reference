# ZISDMIMPLOG_REC
**Description:** EDM Import Log Reading Record (For ZISDM0380)
**Total Fields:** 4
**Key Fields:** MANDT, RUN_TS

## Programs Using This Table
- `zisdm0380`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUN_TS` | DEC | 15 | 🔑 | UTC Time Stamp in Short Form (YYYYMMDDhhmmss) |
| 3 | `START_TS` | DEC | 15 |  | UTC Time Stamp in Short Form (YYYYMMDDhhmmss) |
| 4 | `FINISHED` | CHAR | 1 |  | Checkbox |
