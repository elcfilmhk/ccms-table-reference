# ZISDHDWNMT
**Description:** Downloaded meter tasks to ClickSchedule
**Total Fields:** 11
**Key Fields:** MANDT, CALLID

## Programs Using This Table
- `z_transfer_meter_task_to_cs===ft`
- `zisdh0001`
- `zisdh0003`
- `zisdh0008`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CALLID` | CHAR | 40 | 🔑 | CallID |
| 3 | `STATUS` | CHAR | 1 |  | Meter task download message status |
| 4 | `MESSAGE` | CHAR | 80 |  | Message for Download MRO |
| 5 | `.INCLUDE` | &nbsp; | 0 |  | Administrative data |
| 6 | `CREATION_DATE` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `CREATION_TIME` | TIMS | 6 |  | Creation time |
| 8 | `CREATED_BY` | CHAR | 12 |  | Name of Person Who Created the Object |
| 9 | `CHANGE_DATE` | DATS | 8 |  | Date of Last Change |
| 10 | `CHANGE_TIME` | TIMS | 6 |  | Change time |
| 11 | `CHANGE_BY` | CHAR | 12 |  | Name of person who changed object |
