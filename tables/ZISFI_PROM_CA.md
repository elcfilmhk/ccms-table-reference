# ZISFI_PROM_CA
**Description:** Contract Account and Mapping Code Relationship
**Total Fields:** 5
**Key Fields:** MANDT, PROMO_ID, CONT_ACNT

## Programs Using This Table
- `zisfi0265`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROMO_ID` | CHAR | 10 | 🔑 | Promotion ID |
| 3 | `CONT_ACNT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `MAPPING_CODE` | CHAR | 10 |  | Mapping Code |
| 5 | `UPLOADED` | CHAR | 1 |  | Single-Character Flag |
