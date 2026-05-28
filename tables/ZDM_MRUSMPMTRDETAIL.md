# ZDM_MRUSMPMTRDETAIL
**Description:** OC MRU meter detail structure
**Total Fields:** 36
**Key Fields:** _none_

## Programs Using This Table
- `zisdm0350`
- `zisdm_mru_smp_conn_status=====ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `OC` | CHAR | 2 |  | OC for SMP |
| 2 | `MAINMRU` | CHAR | 8 |  | Meter Reading Unit |
| 3 | `ANLAGE` | CHAR | 10 |  | Installation |
| 4 | `ABLEINH` | CHAR | 8 |  | Meter Reading Unit |
| 5 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 6 | `SERNR` | CHAR | 18 |  | Serial Number |
| 7 | `HAUS` | CHAR | 30 |  | Connection Object |
| 8 | `BGLJAHR` | NUMC | 4 |  | Certification Year |
| 9 | `AGE` | INT1 | 3 |  | Age |
| 10 | `ATNAM` | CHAR | 30 |  | Characteristic Name |
| 11 | `MTRCONNSTATUS` | CHAR | 22 |  | Meter Connection Status |
| 12 | `VILLAGEID` | CHAR | 5 |  | The village indicator of the main MRU |
| 13 | `VILLAGENAME` | CHAR | 80 |  | The name of the Village |
| 14 | `PORTION` | CHAR | 8 |  | Portion |
| 15 | `COLLECTOR` | CHAR | 72 |  | Unique Item Identifier |
| 16 | `STATUS` | CHAR | 10 |  | The status of the connection |
| 17 | `LASTREADDATE` | DATS | 8 |  | The last read date of the SMP meter |
| 18 | `LASTREADTIME` | TIMS | 6 |  | The last read time of the SMP meter |
| 19 | `MANUFACTURER` | CHAR | 30 |  | Manufacturer of asset |
| 20 | `MODEL` | CHAR | 20 |  | Manufacturer model number |
| 21 | `REGIOGROUP` | CHAR | 8 |  | Regional structure grouping |
| 22 | `VBSART` | CHAR | 8 |  | Type of premise |
| 23 | `MATNR` | CHAR | 18 |  | Material Number |
| 24 | `ZWGRUPPE` | CHAR | 8 |  | Register Group |
| 25 | `GROES` | CHAR | 18 |  | Size/dimension |
| 26 | `PORTIONANLAGE` | CHAR | 8 |  | Portion |
| 27 | `INSERVICE` | CHAR | 10 |  | AMI In Service |
| 28 | `CLOSEZONE` | CHAR | 12 |  | MRU Closed Zone |
| 29 | `LANID` | CHAR | 72 |  | Unique Item Identifier |
| 30 | `MODULETYPE` | CHAR | 8 |  | Module Type |
| 31 | `EINBDAT` | DATS | 8 |  | Installation date |
| 32 | `SSRMTR_IND` | CHAR | 1 |  | SSR Meter Indicatior |
| 33 | `BAUJJ` | CHAR | 4 |  | Year of construction |
| 34 | `BAUMM` | CHAR | 2 |  | Month of construction |
| 35 | `BAUJJ_AGE` | CHAR | 4 |  | Year of construction |
| 36 | `/UPL/SER_NO` | CHAR | 30 |  | Serial Number |
