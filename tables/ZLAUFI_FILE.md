# ZLAUFI_FILE
**Description:** Payment Run to Logical File Mapping
**Total Fields:** 5
**Key Fields:** MANDT, LAUFI_PYP, CCINS

## Programs Using This Table
- `zrfkkpcds`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `LAUFI_PYP` | CHAR | 5 | 🔑 | Identification for the payment run |
| 3 | `CCINS` | CHAR | 4 | 🔑 | Payment card type |
| 4 | `FILEINTERN` | CHAR | 60 |  | Logical file name |
| 5 | `VARIANT` | CHAR | 35 |  | Variant |
