# ZISBISPECBD
**Description:** Special billing documents
**Total Fields:** 6
**Key Fields:** MANDT, VKONT, BELNR, ZZREBATE_REF

## Programs Using This Table
- `zisbi0110`
- `zisbi0110_2`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `BELNR` | CHAR | 12 | 🔑 | Number of a billing document |
| 4 | `ZZREBATE_REF` | CHAR | 16 | 🔑 | Rebate reference |
| 5 | `NETTOBTR` | CURR | 13 |  | Net amount of billing line item |
| 6 | `PROCESS_IND` | NUMC | 1 |  | 1-stop invoicing, 2-invoicing |
