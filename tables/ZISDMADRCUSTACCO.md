# ZISDMADRCUSTACCO
**Description:** ADR Event customer CA/Meter
**Total Fields:** 5
**Key Fields:** MANDT, EVENTNAME, DRCUSTNO, VKONTO, SERNR

## Programs Using This Table
- `zisdm0309`
- `zisdm0310_adr`
- `zisdm0328_adr`
- `zisdm0356`
- `zisdm0369_candi`
- `zisfi0249`
- `zisfi0249_dnld`
- `zisfi0250`
- `zisfi0250_backup`
- `zisfi0250_backup_1`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EVENTNAME` | CHAR | 50 | 🔑 | Event Name |
| 3 | `DRCUSTNO` | CHAR | 80 | 🔑 | DR Customer Number |
| 4 | `VKONTO` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
