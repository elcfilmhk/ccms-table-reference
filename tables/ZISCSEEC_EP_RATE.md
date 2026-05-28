# ZISCSEEC_EP_RATE
**Description:** Eco-point conversion rate
**Total Fields:** 6
**Key Fields:** MANDT, VALID_TO

## Programs Using This Table
- `z_bapi_epmcom_rate============ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VALID_TO` | DATS | 8 | 🔑 | End Date |
| 3 | `VALID_FROM` | DATS | 8 |  | Start Date |
| 4 | `CON_RATE` | CHAR | 3 |  | Eco-points conversion rate |
| 5 | `DESC_EN` | CHAR | 80 |  | Conversion rate English description |
| 6 | `DESC_ZF` | CHAR | 80 |  | Conversion rate Chinese description |
