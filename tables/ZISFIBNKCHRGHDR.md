# ZISFIBNKCHRGHDR
**Description:** Bank Charge Header
**Total Fields:** 4
**Key Fields:** MANDT, IFACE_NAME

## Programs Using This Table
- `zisfi0094`
- `zrfkkpcds`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `IFACE_NAME` | CHAR | 12 | 🔑 | Interface Control - Interface name used in interface files |
| 3 | `HERKF` | CHAR | 2 |  | Document Origin Key |
| 4 | `UNIT_RATE` | CURR | 5 |  | Unite Rate |
