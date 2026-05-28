# ZISCS_MASKED_BP
**Description:** Masked BP
**Total Fields:** 8
**Key Fields:** MANDT, PARTNER1, PARTNER2, VKONT

## Programs Using This Table
- `ziscs0376`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PARTNER1` | CHAR | 10 | 🔑 | Business Partner Number |
| 3 | `PARTNER2` | CHAR | 10 | 🔑 | Business Partner Number |
| 4 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `SCASE` | CHAR | 20 |  | Data Masking Case |
| 6 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `ERZET` | TIMS | 6 |  | Entry time |
| 8 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
