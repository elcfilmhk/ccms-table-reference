# ZISCS_EEC_EO_CONS_COMP_OUT
**Description:** Output Structure FOR FM 'ZISCSEEC_EO_CONS_COMPARISON'
**Total Fields:** 13
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0734`
- `ziscseec_eo_cons_comparison===ft`
- `ziscseec_eo_cons_comparison_wsft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `SEQ` | INT4 | 10 |  | Sorting Sequence of Bills; 0=most recently issued |
| 3 | `BELNR` | CHAR | 12 |  | Number of a billing document |
| 4 | `PERIOD_LABEL` | CHAR | 20 |  | Char 20 |
| 5 | `BEGABRPE` | DATS | 8 |  | Start of billing period |
| 6 | `ENDABRPE` | DATS | 8 |  | End of billing period |
| 7 | `TOT_KWH` | DEC | 16 |  | Entry value (installed value) for a device |
| 8 | `LASTYR_BELNR` | CHAR | 12 |  | Number of a billing document |
| 9 | `LASTYR_BEGABRPE` | DATS | 8 |  | Start of billing period |
| 10 | `LASTYR_ENDABRPE` | DATS | 8 |  | End of billing period |
| 11 | `LASTYR_TOT_KWH` | DEC | 16 |  | Entry value (installed value) for a device |
| 12 | `TEMP` | DEC | 10 |  | Minimum time in microseconds |
| 13 | `HUM` | DEC | 10 |  | Minimum time in microseconds |
