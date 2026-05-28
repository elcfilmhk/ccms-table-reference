# ZCSH_HELPINFO
**Description:** RWD Context Sensitive Help
**Total Fields:** 4
**Key Fields:** HPROGRAM, HDYNPRO, HTCODE

## Programs Using This Table
- `z_zcsh_upload_helpinfo_data`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `HPROGRAM` | CHAR | 40 | 🔑 | ABAP Program: Current Master Program |
| 2 | `HDYNPRO` | CHAR | 4 | 🔑 | Dynpro Number |
| 3 | `HTCODE` | CHAR | 20 | 🔑 | Transaction Code |
| 4 | `OBJECT` | CHAR | 255 |  | Text, 255 Characters |
