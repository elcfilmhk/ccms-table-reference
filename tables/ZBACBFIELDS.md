# ZBACBFIELDS
**Description:** General fields for IS-U conversion
**Total Fields:** 13
**Key Fields:** _none_

## Programs Using This Table
- `z_conv_file_open==============ft`
- `zbacbe005`
- `zbacbe006`
- `zbacbe007`
- `zbacbe008`
- `zbacbe009`
- `zbacbe010`
- `zbacbe011`
- `zbacbe012`
- `zbacbe013`
- `zbacbe015`
- `zbacbe017`
- `zbacbe021`
- `zbacbe026`
- `zisbi0014`
- `zisbi0014t`
- `zisbi0042_2`
- `zisbi0044`
- `zisbi0054`
- `zisbi0058`
- `zisbi0069`
- `zisbi0075`
- `zisbi0192`
- `zisbi0194`
- `zisbi0205`
- `zisbi0206`
- `zisbi0208`
- `zisbi0216`
- `zisbi0259`
- `zisbw0002`
- `ziscs0022`
- `ziscs0028`
- `ziscs0067`
- `ziscs0068`
- `ziscs0071`
- `ziscs0076`
- `ziscs0083`
- `ziscs0087`
- `ziscs0108`
- `ziscs0120`
- `ziscs0198`
- `ziscs0207`
- `ziscs0367_pyl`
- `ziscs0374`
- `ziscs0404`
- `ziscs0504`
- `ziscs0505`
- `ziscs0712`
- `ziscs0718`
- `ziscs0720`
- `ziscs0732`
- `ziscs0808`
- `zisdm0009`
- `zisdm0039`
- `zisdm0106`
- `zisdm0108`
- `zisdm0287`
- `zisdm0288`
- `zisdm0289`
- `zisdm0290`
- `zisdm0318`
- `zisdm0399`
- `zisfi0076`
- `zisfi0088`
- `zisfi0097`
- `zisfi0125`
- `zisfi0132`
- `zisfi0170`
- `zisfi0201`
- `zisfi0210`
- `zisfi0275`
- `zisfibocsetup`
- `zissd00072`
- `zissd00075`
- `zissd00076`
- `zissd00077`
- `zsdsodl02`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `FILE` | CHAR | 255 |  | &nbsp; |
| 2 | `FILE_RECEIPT` | CHAR | 255 |  | &nbsp; |
| 3 | `FILE_TRANSFER` | CHAR | 255 |  | &nbsp; |
| 4 | `FIRMA` | CHAR | 5 |  | Company (Client) for Migration |
| 5 | `OBJECT` | CHAR | 10 |  | Migration Object |
| 6 | `MAPPE_RECEIPT` | CHAR | 12 |  | Session name |
| 7 | `MAPPE_TRANSFER` | CHAR | 12 |  | Session name |
| 8 | `FFORMAT` | CHAR | 3 |  | File format |
| 9 | `VARIANTS` | CHAR | 1 |  | Identifier create variants |
| 10 | `DATA` | CHAR | 1500 |  | Data part of sequential file |
| 11 | `NUM_REC` | NUMC | 5 |  | Number of records |
| 12 | `ADD_CPU_AP` | CHAR | 1 |  | Add CPU data Application server |
| 13 | `ADD_CPU_DB` | CHAR | 1 |  | Add CPU data Database server |
