# ZISCV_DMASK_CFG1
**Description:** Data Masking Config 1
**Total Fields:** 11
**Key Fields:** MANDT, THREAD_NAME, ID

## Programs Using This Table
- `ziscv_datamask1`
- `ziscv_datamask1_thread`
- `ziscv_datamask_thread=========ft`
- `ziscv_datamask_thread_ws======ft`
- `ziscv_field_person_name=======ft`
- `zziscv_datamask1`
- `zziscv_datamask1_thread`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `THREAD_NAME` | CHAR | 30 | 🔑 | Rules with Same thread name processed in same thread |
| 3 | `ID` | INT4 | 10 | 🔑 | Natural number |
| 4 | `SEQ` | INT4 | 10 |  | Natural number |
| 5 | `DISABLED` | CHAR | 1 |  | "X": Disabled |
| 6 | `TABLE_NAME` | CHAR | 16 |  | Table name, 16 characters |
| 7 | `MASK_MODE` | CHAR | 10 |  | Masking Mode |
| 8 | `FIELD_NAME` | CHAR | 30 |  | Field Name |
| 9 | `MASK_BLANK` | CHAR | 1 |  | General Flag |
| 10 | `CUSTOM_FM` | CHAR | 30 |  | Custom FM name |
| 11 | `MASK_STRING` | CHAR | 200 |  | Mask. "": clear; _: 1 char; %: rest; "~":repeat; "@":ski |
