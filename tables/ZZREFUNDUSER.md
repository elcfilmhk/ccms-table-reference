# ZZREFUNDUSER
**Description:** Structure for getting refund creator
**Total Fields:** 8
**Key Fields:** _none_

## Programs Using This Table
- `zisfi0028`
- `zisfi0204`
- `zisfi0341`
- `zisfi0345`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `OPBEL` | CHAR | 12 |  | Document Number in Contract Accounts Receivable and Payable |
| 2 | `RDATE` | DATS | 8 |  | Date ID |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `PYMET` | CHAR | 1 |  | Payment Method |
| 5 | `USERNAME` | CHAR | 12 |  | User name of the person responsible in change document |
| 6 | `UDATE` | DATS | 8 |  | Creation date of the change document |
| 7 | `UTIME` | TIMS | 6 |  | Time changed |
| 8 | `AUTO` | CHAR | 1 |  | Auto-Refund Indicator |
