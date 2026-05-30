# `ETTIFN`

**Description:** Installation Billing Index — billing history index
**Category:** Standard SAP Table
**References:** 145 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/ettifn/) — validated 2026-05-30, schema v1.0
**Schema fields:** 18 fields | **Data types:** CHAR(12), CUKY(1), CURR(1), DATS(2), DEC(2)

## Key Fields
`BELNR`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `BIS` | BISZEITSCH | — | DATS | 8 | 0 | Date at Which a Time Slice Expires |
| `BELNR` | E_BELNR | — | CHAR | 12 | 0 | Number of a billing document |
| `MBELNR` | E_BELNR | — | CHAR | 12 | 0 | Number of a billing document |
| `MAUSZUG` | MAUSZUG | — | CHAR | 1 | 0 | Fact was changed as a result of move-out |
| `ALTBIS` | BISZEITSCH | — | DATS | 8 | 0 | Date at Which a Time Slice Expires |
| `INAKTIV` | INAKTIVKZ | — | CHAR | 1 | 0 | Entry Inactive |
| `MANAEND` | MANAEND | — | CHAR | 1 | 0 | Indicator: manual change to calculated value |
| `TARIFART` | TARIFART | — | CHAR | 8 | 0 | Rate Type |
| `KONDIGR` | KONDIGR | — | CHAR | 10 | 0 | Rate fact group |
| `WERT1` | E_WERT1 | — | DEC | 16 | 7 | Entry value (installed value) for a device |
| `WERT2` | E_WERT2 | — | DEC | 16 | 7 | Value to be billed |
| `STRING1` | STRING1 | — | CHAR | 10 | 0 | First key field for operand value |
| `STRING2` | STRING2 | — | CHAR | 10 | 0 | Second key field for operand value |
| `STRING3` | STRING3 | — | CHAR | 1 | 0 | Third key field for operand value |
| `STRING4` | STRING4 | — | CHAR | 1 | 0 | Fourth key field for operand value |
| `ERSATZWERT` | ERSATZWERT | — | CHAR | 1 | 0 | Replacement value for operands |
| `BETRAG` | E_BETRAG | — | CURR | 13 | 2 | Currency-dependent amount |
| `WAERS` | WAERS | — | CUKY | 5 | 0 | Currency Key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `AB`, `ANLAGE`, `BELNR`, `BETRAG`, `BIS`, `INAKTIV`, `OPERAND`, `WAERS`, `WERT1`, `ab`, `anlage`, `belnr`, `bis`, `inaktiv`, `operand`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `ANLAGE`, `anlage`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_get_bill_csmpt.txt`
- `z_calculate_deposit.txt`
- `z_isdm_get_ami_effective_date.txt`
- `zeedm_ptr.txt`
- `zisbi0026.txt`
- `zisbi0151.txt`
- `zisbiami_calc_bill_costs.txt`
- `zisbw0021.txt`
- `ziscs0090.txt`
- `ziscs0121.txt`
- `ziscs0252f01.txt`
- `ziscsami_get_billing_period.txt`
- `ziscseec_get_adjacent_bills.txt`
- `zisdatveri.txt`
- `zisdm0058.txt`
- `zisdm0089.txt`
- `zisdm0104.txt`
- `zisdm0170.txt`
- `zisdm0278.txt`
- `zreprjt00.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_