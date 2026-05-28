# ZISDMADRCUSTCONT
**Description:** Customer Contact Information
**Total Fields:** 9
**Key Fields:** MANDT, DRCUSTNO, SEQNO

## Programs Using This Table
- `zisdm0313_adr`
- `zisdm0314_adr`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DRCUSTNO` | CHAR | 80 | 🔑 | DR Customer Number |
| 3 | `SEQNO` | NUMC | 4 | 🔑 | ADR Item Sequence Number |
| 4 | `CUSTGROUP` | CHAR | 11 |  | Program ID |
| 5 | `PREF_CHANNEL` | CHAR | 1 |  | Preferred Channel for Communication |
| 6 | `CONTACT_INFO` | CHAR | 50 |  | Contact Information |
| 7 | `CONTACT_NAME` | CHAR | 60 |  | Name of Contact Person |
| 8 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 9 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
