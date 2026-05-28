# ZISDMBRPMR
**Description:** Structure for Imput Meter Reading for Bulk Replacement
**Total Fields:** 6
**Key Fields:** _none_

## Programs Using This Table
- `zisdm0022`
- `zisdm0022_bulk`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `ZZREFNO` | CHAR | 3 |  | Reference number |
| 2 | `ZZRGNUMBER` | INT1 | 3 |  | Register number |
| 3 | `ZZOLDDEVICE` | CHAR | 18 |  | Serial Number |
| 4 | `ZZOLDMR` | CHAR | 36 |  | Expected meter reading in screen format |
| 5 | `ZZNEWDEVICE` | CHAR | 18 |  | Serial Number |
| 6 | `ZZNEWMR` | CHAR | 36 |  | Expected meter reading in screen format |
