# ZISCSTSLOTS
**Description:** Appointment Time Slots
**Total Fields:** 6
**Key Fields:** MANDT, WORK_DATE, WORK_TIME, GEWRK

## Programs Using This Table
- `ziscs0003`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `WORK_DATE` | DATS | 8 | 🔑 | Date |
| 3 | `WORK_TIME` | TIMS | 6 | 🔑 | Start Time of Time Slot |
| 4 | `GEWRK` | NUMC | 8 | 🔑 | Object ID of the Work Center |
| 5 | `APP_FLAG` | CHAR | 1 |  | Appointment |
| 6 | `KALID` | CHAR | 2 |  | Factory calendar ID |
