# ZISCEP_EHER_IURL
**Description:** CEP - e-HER (Archive Table to store the Image URL)
**Total Fields:** 4
**Key Fields:** MANDT, CONTRACT_ACCOUNT, IMPORT_DATE, IMAGE_URL_NEW

## Programs Using This Table
- `ziscs0464`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CONTRACT_ACCOUNT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `IMPORT_DATE` | DATS | 8 | 🔑 | CEP: e-HER Data Import Date |
| 4 | `IMAGE_URL_NEW` | CHAR | 255 | 🔑 | CEP: e-HER Image URL (New) |
