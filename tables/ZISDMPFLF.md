# ZISDMPFLF
**Description:** Power Factor and Load Factor Calculation Result
**Total Fields:** 11
**Key Fields:** _none_

## Programs Using This Table
- `z_isdm_pf_lf_calculate========ft`
- `ziscs0086b`
- `zisdm0080`
- `zisdm0179`
- `zreprjt00`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VERTRAG` | CHAR | 10 |  | Contract |
| 2 | `ZZREADDATE` | DATS | 8 |  | Meter reading date for unit |
| 3 | `ZZPOWER_FACTOR` | DEC | 4 |  | Power Factor |
| 4 | `ZZLOAD_FACTOR` | DEC | 4 |  | Load Factor |
| 5 | `ZZTOTKWH` | CHAR | 36 |  | Total KWH |
| 6 | `ZZTOTKVA` | CHAR | 36 |  | Total KVA |
| 7 | `ZZTOTKVAH` | CHAR | 36 |  | Total KVAH |
| 8 | `ZZONKWH` | CHAR | 36 |  | On KWH |
| 9 | `ZZOFFKWH` | CHAR | 36 |  | OFF KWH |
| 10 | `ZZONKVA` | CHAR | 36 |  | ON KVA |
| 11 | `ZZOFFKVA` | CHAR | 36 |  | OFF KVA |
