# ZISDMADRBATEVCU
**Description:** Batch Event Cust relation
**Total Fields:** 4
**Key Fields:** MANDT, BATCHID, EVENTNAME, DRCUSTNO

## Programs Using This Table
- `ziscs0528`
- `zisdm0309`
- `zisdm0310_adr`
- `zisdm0311_adr`
- `zisdm0328_adr`
- `zisdm0355`
- `zisdm0356`
- `zisdm0369_candi`
- `zisfi0249`
- `zisfi0250_backup`
- `zisfi0250_backup_1`
- `zisfi0251`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BATCHID` | CHAR | 80 | 🔑 | Batch ID |
| 3 | `EVENTNAME` | CHAR | 50 | 🔑 | Event Name |
| 4 | `DRCUSTNO` | CHAR | 80 | 🔑 | DR Customer Number |
