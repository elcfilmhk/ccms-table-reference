# ZISCEP_EHER_MIME
**Description:** CEP - e-HER (Formatted HTML Data with Base64 Image)
**Total Fields:** 5
**Key Fields:** MANDT, CONTRACT_ACCOUNT, IMPORT_DATE, IMAGE_URL_NEW

## Programs Using This Table
- `ziscs0457`
- `ziscs0458`
- `ziscs0463`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CONTRACT_ACCOUNT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `IMPORT_DATE` | DATS | 8 | 🔑 | CEP: e-HER Data Import Date |
| 4 | `IMAGE_URL_NEW` | CHAR | 255 | 🔑 | CEP: e-HER Image URL (New) |
| 5 | `IMAGE_BASE64` | STRG | 0 |  | CEP: e-HER Image (Base64) |
