# ZISCEP_EHER_IMG
**Description:** CEP - e-HER (Configuration Table to store the Image Link)
**Total Fields:** 7
**Key Fields:** MANDT, IMAGE_IDENTIFIER, SYSTEM_TYPE

## Programs Using This Table
- `ziscs0457`
- `ziscs0463`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `IMAGE_IDENTIFIER` | CHAR | 40 | 🔑 | CEP: e-HER Image Identifier |
| 3 | `SYSTEM_TYPE` | CHAR | 1 | 🔑 | CEP: e-HER (System Type) |
| 4 | `IMAGE_URL_ORIGIN` | CHAR | 255 |  | CEP: e-HER Image URL (Original) |
| 5 | `IMAGE_URL_NEW` | CHAR | 255 |  | CEP: e-HER Image URL (New) |
| 6 | `IMAGE_MIME_PATH` | CHAR | 255 |  | CEP: e-HER Image (MIME Repository Path) |
| 7 | `IMAGE_DATA_URI` | CHAR | 100 |  | CEP: e-HER Image (Data URI) |
