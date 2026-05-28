# ZISFI_WF_LOCK_H
**Description:** Create Lock History when Mass Upload
**Total Fields:** 14
**Key Fields:** MANDY, GPART, VKONT, LOOBJ1, LOTYP, PROID, LOCKR, FDATE, TDATE, ERZDT, ERZET

## Programs Using This Table
- `zisfi0286`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDY` | CLNT | 3 | 🔑 | Client |
| 2 | `GPART` | CHAR | 10 | 🔑 | Business Partner Number |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `LOOBJ1` | CHAR | 32 | 🔑 | Lock object |
| 5 | `LOTYP` | CHAR | 2 | 🔑 | Lock Object Category |
| 6 | `PROID` | CHAR | 2 | 🔑 | Process Code (Example: Dunning, Payment) |
| 7 | `LOCKR` | CHAR | 1 | 🔑 | Lock Reason |
| 8 | `FDATE` | DATS | 8 | 🔑 | Lock valid from |
| 9 | `TDATE` | DATS | 8 | 🔑 | Lock valid to |
| 10 | `ERZDT` | DATS | 8 | 🔑 | Date created |
| 11 | `ERZET` | TIMS | 6 | 🔑 | Entry time |
| 12 | `BETRH` | CURR | 13 |  | Amount In Local Currency With +/- Signs |
| 13 | `STATUS` | CHAR | 1 |  | Insert Lock Status |
| 14 | `MESSAGE` | CHAR | 250 |  | Message |
