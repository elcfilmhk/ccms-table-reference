# ZISCS_COPY_BILL
**Description:** Copy Bill Path
**Total Fields:** 5
**Key Fields:** MANDT, SYSID, BILL_TYPE

## Programs Using This Table
- `zisbi0268`
- `zopenpdf`
- `zprintdoc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SYSID` | CHAR | 8 | 🔑 | ABAP System Field: Name of SAP System |
| 3 | `BILL_TYPE` | NUMC | 2 | 🔑 | Bill Type |
| 4 | `DESCRIPTION` | CHAR | 100 |  | Bill Desccription |
| 5 | `PATH` | CHAR | 255 |  | File Path |
