# ZISDMNEWSRVRDG
**Description:** Reading of the new service meter cases to follow-up
**Total Fields:** 5
**Key Fields:** MANDT, ID, GERNR, ZWNUMMER

## Programs Using This Table
- `zisdm0050`
- `zisdm0254`
- `zrdm_us_rep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ID` | NUMC | 10 | 🔑 | ID for new service case |
| 3 | `GERNR` | CHAR | 18 | 🔑 | Device |
| 4 | `ZWNUMMER` | NUMC | 3 | 🔑 | Register |
| 5 | `READING` | DEC | 31 |  | The reading of the new service meter |
