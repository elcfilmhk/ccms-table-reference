# ZISCS_SUPSD_PAIR
**Description:** Government Supplementary Subsidy Pairing
**Total Fields:** 28
**Key Fields:** MANDT, REF_NO

## Programs Using This Table
- `ziscs0219`
- `ziscs0243`
- `ziscs0244`
- `zisfi0165`
- `zisfi0226`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REF_NO` | NUMC | 8 | 🔑 | Reference no. |
| 3 | `VSTELLE_OLD` | CHAR | 10 |  | Transfer From Premise (Old) |
| 4 | `VSTELLE_NEW` | CHAR | 10 |  | Transfer To Premise (New) |
| 5 | `STATUS` | CHAR | 2 |  | Status |
| 6 | `CA_OLD` | CHAR | 12 |  | Transfer From Contract Account (Old) |
| 7 | `CA_NEW` | CHAR | 12 |  | Transfer To Contract Account (New) |
| 8 | `TRANSFER_AMOUNT` | CURR | 11 |  | Transfer Total Amount |
| 9 | `TRANSFER_GSS` | CURR | 11 |  | Transfer GSS |
| 10 | `TRANSFER_ECRS` | CURR | 11 |  | Transfer ECRS |
| 11 | `TRANSFER_GSS2` | CURR | 11 |  | Transfer GSS2 |
| 12 | `LAST_TRSF_DATE` | DATS | 8 |  | Last Transfer Date |
| 13 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 14 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 15 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 16 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 17 | `ZDR` | CHAR | 1 |  | Deposit Request Processed |
| 18 | `ZTR` | CHAR | 1 |  | Transferred Opened Item Processed |
| 19 | `TRANSFER_GS_R1` | CURR | 11 |  | Reserved  GS 1 (GSS3) |
| 20 | `TRANSFER_GS_R2` | CURR | 11 |  | Reserved  GS 2 (ECRS2) |
| 21 | `TRANSFER_GS_R3` | CURR | 11 |  | Reserved  GS 3 |
| 22 | `TRANSFER_GS_R4` | CURR | 11 |  | Reserved  GS 4 |
| 23 | `TRANSFER_GS_R5` | CURR | 11 |  | Reserved  GS 5 |
| 24 | `TRANSFER_GS_R6` | CURR | 11 |  | Reserved  GS 6 |
| 25 | `TRANSFER_GS_R7` | CURR | 11 |  | Reserved  GS 7 |
| 26 | `TRANSFER_GS_R8` | CURR | 11 |  | Reserved  GS 8 |
| 27 | `TRANSFER_GS_R9` | CURR | 11 |  | Reserved  GS 9 |
| 28 | `TRANSFER_GS_R10` | CURR | 11 |  | Reserved  GS 10 |
