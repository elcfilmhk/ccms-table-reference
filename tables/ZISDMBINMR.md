# ZISDMBINMR
**Description:** Customized structure for reference meter reading
**Total Fields:** 4
**Key Fields:** _none_

## Programs Using This Table
- `zisdm0022`
- `zisdm0022_bulk`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `ZZREFNO` | CHAR | 3 |  | Reference number |
| 2 | `ZZDEVICE` | CHAR | 18 |  | Serial Number |
| 3 | `ZZRGNUMBER` | INT1 | 3 |  | Register number |
| 4 | `ZZMR` | CHAR | 36 |  | Expected meter reading in screen format |
