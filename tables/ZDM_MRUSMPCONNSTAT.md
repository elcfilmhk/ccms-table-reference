# ZDM_MRUSMPCONNSTAT
**Description:** SMP Meter Connectivity Table
**Total Fields:** 27
**Key Fields:** _none_

## Programs Using This Table
- `zisdm0350`
- `zisdm_mru_smp_conn_status=====ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `OC` | CHAR | 2 |  | OC for SMP |
| 2 | `MAINMRU` | CHAR | 8 |  | Meter Reading Unit |
| 3 | `VILLAGEID` | CHAR | 5 |  | The village indicator of the main MRU |
| 4 | `VILLAGENAME` | CHAR | 80 |  | The name of the Village |
| 5 | `METERINMRU` | NUMC | 6 |  | Meter in MRU |
| 6 | `NONSMPMETER` | NUMC | 6 |  | Non SMP Meter |
| 7 | `SMPMETER` | NUMC | 6 |  | SMP meter |
| 8 | `UNCONNSMPMETER` | NUMC | 6 |  | Unconnected SMP meter |
| 9 | `CONNSMPMETER` | NUMC | 6 |  | Connected SMP meter |
| 10 | `CONNPERTOTALMTR` | DEC | 5 |  | Connected Perc total meter |
| 11 | `CONNPERSMPMTR` | DEC | 5 |  | Connected Perc SMP meter |
| 12 | `RDGMETHOD10` | NUMC | 6 |  | RDG Method10 |
| 13 | `RDGMETHOD20` | NUMC | 6 |  | RDG Method20 |
| 14 | `RDGMETHOD30` | NUMC | 6 |  | RDG Method30 |
| 15 | `RDGMETHOD35` | NUMC | 6 |  | RDG Method35 |
| 16 | `RDGMETHOD40` | NUMC | 6 |  | RDG Method40 |
| 17 | `RDGMETHOD45` | NUMC | 6 |  | RDG Method45 |
| 18 | `RDGMETHOD50` | NUMC | 6 |  | RDG Method50 |
| 19 | `RDGMETHOD55` | NUMC | 6 |  | RDG Method55 |
| 20 | `RDGMETHOD60` | NUMC | 6 |  | RDG Method60 |
| 21 | `RDGMETHOD65` | NUMC | 6 |  | RDG Method65 |
| 22 | `RDGMETHOD70` | NUMC | 6 |  | RDG Method70 |
| 23 | `RDGMETHOD75` | NUMC | 6 |  | RDG Method75 |
| 24 | `RDGMETHODOTHER` | NUMC | 6 |  | RDG Method Other |
| 25 | `PORTION` | CHAR | 8 |  | Portion |
| 26 | `CLOSEZONE` | CHAR | 12 |  | MRU Closed Zone |
| 27 | `SSRMTR` | NUMC | 6 |  | SSR Meter |
