# ZISCS_PON_AGENDA
**Description:** Config for the Proactive Outage Notification (2019) System
**Total Fields:** 8
**Key Fields:** MANDT, OBJ_NAME, TYPE, COUNTER

## Programs Using This Table
- `ziscs_pon_ctrl_panel`
- `ziscs_pon_import_sent_hist`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OBJ_NAME` | CHAR | 40 | 🔑 | Object Name in Object Directory |
| 3 | `TYPE` | CHAR | 30 | 🔑 | ABAP: Name of Variant Variable |
| 4 | `COUNTER` | NUMC | 4 | 🔑 | ABAP: Current selection number |
| 5 | `SIGN` | CHAR | 1 |  | ABAP: ID: I/E (include/exclude values) |
| 6 | `OPTI` | CHAR | 2 |  | ABAP: Selection option (EQ/BT/CP/...) |
| 7 | `LOW` | CHAR | 255 |  | Case-sensitive Text of 255 length |
| 8 | `HIGH` | CHAR | 255 |  | Case-sensitive Text of 255 length |
