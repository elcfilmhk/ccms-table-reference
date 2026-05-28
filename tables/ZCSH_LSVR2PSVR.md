# ZCSH_LSVR2PSVR
**Description:** RWD Context Sensitive Help Logical to Phsyical Server Tbl
**Total Fields:** 4
**Key Fields:** LSERVER

## Programs Using This Table
- `z_zcsh_pid_maint`
- `z_zcsh_pid_maint2`
- `z_zcsh_upload_lsvr2psvr2_data`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `LSERVER` | CHAR | 18 | 🔑 | Data element  for RWD Context Sensitive Help |
| 2 | `PSERVER` | CHAR | 255 |  | Text, 255 Characters |
| 3 | `LSVRDESCR` | CHAR | 60 |  | Short Description of Repository Objects |
| 4 | `HLPPATH` | CHAR | 255 |  | Text, 255 Characters |
