# ZISBIBBMTRINFO
**Description:** Budget billing information
**Total Fields:** 9
**Key Fields:** MANDT, OPBEL, VKONT, SEQ

## Programs Using This Table
- `zisbi0108`
- `zisbi0112`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `SEQ` | CHAR | 2 | 🔑 | Sequence No. |
| 5 | `GERAET` | CHAR | 18 |  | Device |
| 6 | `I_ZWSTNDAB` | DEC | 31 |  | Billed meter reading |
| 7 | `I_ZWSTVOR` | DEC | 31 |  | Previous meter reading |
| 8 | `UMWFAKT` | DEC | 31 |  | Conversion Factor |
| 9 | `I_ABRMENGE` | DEC | 31 |  | Billing quantity for internal billing format |
