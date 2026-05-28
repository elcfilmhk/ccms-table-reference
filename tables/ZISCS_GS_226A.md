# ZISCS_GS_226A
**Description:** Government Subsidy Termination Check (226A figure)
**Total Fields:** 14
**Key Fields:** MANDT, VKONT, CPUDT, CPUTM, SEQ

## Programs Using This Table
- `ziscs0360`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `CPUDT` | DATS | 8 | 🔑 | Date of entry |
| 4 | `CPUTM` | TIMS | 6 | 🔑 | Time of Entry |
| 5 | `SEQ` | NUMC | 2 | 🔑 | Sequence number for Gov subsidy |
| 6 | `PROCID` | CHAR | 12 |  | Process ID |
| 7 | `REFMTH` | DATS | 8 |  | Entitlement ref month |
| 8 | `BALENT` | CURR | 13 |  | Entitlement balance |
| 9 | `ENTAMT` | CURR | 13 |  | Entitlement amount |
| 10 | `ENTVID` | CURR | 13 |  | Entitlement voided |
| 11 | `ENTUSG` | CURR | 13 |  | Entitlement usage |
| 12 | `ITEM_A` | CHAR | 1 |  | Figure A Check |
| 13 | `ITEM_B` | CHAR | 1 |  | Figure B Check |
| 14 | `ITEM_C` | CHAR | 1 |  | Figure C Check |
