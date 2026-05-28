# ZISDMCCUSER
**Description:** Table of CC username for SSR CA
**Total Fields:** 7
**Key Fields:** MANDT, VKONT, SLOT

## Programs Using This Table
- `zcl_object_move`
- `zisdm0364`
- `zisdm0367`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `SLOT` | CHAR | 1 | 🔑 | Email Slot number |
| 4 | `EMAIL` | CHAR | 50 |  | Email of CA account |
| 5 | `CC_UNAME` | CHAR | 20 |  | Contract Contact username |
| 6 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 7 | `TIME` | TIMS | 6 |  | Time |
