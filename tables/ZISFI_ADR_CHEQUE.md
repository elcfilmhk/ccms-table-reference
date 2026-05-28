# ZISFI_ADR_CHEQUE
**Description:** Cheque no table
**Total Fields:** 12
**Key Fields:** MANDT, APPROVALLOTID, EVENTNAME, DRCUSTNO

## Programs Using This Table
- `zisdm0327_adr`
- `zisdm0369_candi`
- `zisfi0249`
- `zisfi0249_dnld`
- `zisfi0250`
- `zisfi0250_backup`
- `zisfi0250_backup_1`
- `zisfi0274`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `APPROVALLOTID` | CHAR | 10 | 🔑 | ADR Approval Lot ID |
| 3 | `EVENTNAME` | CHAR | 50 | 🔑 | Event Name |
| 4 | `DRCUSTNO` | CHAR | 80 | 🔑 | DR Customer Number |
| 5 | `PAYMENTOPTION` | CHAR | 2 |  | DR Customer payment option |
| 6 | `PAYMENTID` | CHAR | 10 |  | ADR Payment ID |
| 7 | `CHEQUE` | CHAR | 20 |  | Cheque no |
| 8 | `AMOUNT` | DEC | 16 |  | Cheque Amount |
| 9 | `REFERNC_NUM` | CHAR | 10 |  | Reference Number |
| 10 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 11 | `ERZET` | TIMS | 6 |  | Entry time |
| 12 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
