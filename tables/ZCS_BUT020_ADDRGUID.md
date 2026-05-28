# ZCS_BUT020_ADDRGUID
**Description:** Stucture For Check ADDR_GUID Existence
**Total Fields:** 4
**Key Fields:** _none_

## Programs Using This Table
- `ziscv01b`
- `ziscv02`
- `ziscv04`
- `ziscv04g`
- `ziscv05`
- `ziscv05g`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 2 | `ADDRNUMBER` | CHAR | 10 |  | Address Number |
| 3 | `ADDRESS_GUID` | RAW | 16 |  | GUID of a Business Partner Address |
| 4 | `ADDR_FOUND` | CHAR | 1 |  | Corresponding Addr GUID Found |
