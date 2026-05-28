# ZISDMMTSST
**Description:** Customized structure for Meter Testing System interface
**Total Fields:** 51
**Key Fields:** _none_

## Programs Using This Table
- `zisdm0034`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `SERNR` | CHAR | 18 |  | Serial Number |
| 2 | `FLAG` | CHAR | 1 |  | Flag field: 'N' for Create, 'U' for Update |
| 3 | `ZWNUMMER` | CHAR | 3 |  | Register |
| 4 | `ZWTYP` | CHAR | 2 |  | Register category |
| 5 | `MASSREAD` | CHAR | 6 |  | unit of measure |
| 6 | `ZWART` | CHAR | 2 |  | Register type |
| 7 | `STANZVOR` | CHAR | 2 |  | Places before the decimal point in a register |
| 8 | `STANZNAC` | CHAR | 2 |  | Places after the decimal in a register |
| 9 | `ZWFAKT` | CHAR | 12 |  | Register Factor in character format |
| 10 | `ZWGRUPPE` | CHAR | 8 |  | Register Group |
| 11 | `FUNKLAS` | CHAR | 8 |  | Function class |
| 12 | `BAUKLAS` | CHAR | 8 |  | Construction class |
| 13 | `ZCONNECT` | CHAR | 2 |  | Connection value |
| 14 | `MATNR` | CHAR | 18 |  | Material Number |
| 15 | `HERST` | CHAR | 30 |  | Manufacturer of asset |
| 16 | `TYPBZ` | CHAR | 20 |  | Manufacturer model number |
| 17 | `AB` | NUMC | 8 |  | Valid from date 'DDMMYYYY' |
| 18 | `BAUJJ` | CHAR | 4 |  | Year of construction |
| 19 | `BGLJAHR` | NUMC | 4 |  | Certification Year |
| 20 | `BESITZ` | NUMC | 2 |  | Inspection relevance of device |
| 21 | `PLOMBE` | CHAR | 2 |  | Seal code |
| 22 | `ZWSTAND` | CHAR | 36 |  | Meter reading recorded |
| 23 | `EQART` | CHAR | 10 |  | Meter type |
| 24 | `INVNR` | CHAR | 25 |  | Primary voltage |
| 25 | `SECVOL` | CHAR | 25 |  | Secondary voltage |
| 26 | `GROES` | CHAR | 18 |  | Size/dimension |
| 27 | `TIDNR` | CHAR | 25 |  | Technical identification number |
| 28 | `APPROVALNR` | CHAR | 15 |  | Device inspection number |
| 29 | `STONR` | CHAR | 40 |  | User status |
| 30 | `LTDATE` | CHAR | 10 |  | Last Test/Inspection Date 'DDMMYYYY' |
| 31 | `FULLLOAD` | CHAR | 30 |  | Accuracy - Full Load PF1 |
| 32 | `LIGHTLOAD` | CHAR | 30 |  | Accuracy - Light Load PF1 |
| 33 | `INDUCTIVE` | CHAR | 30 |  | Accuracy - Inductive PF0.5 |
| 34 | `CREEPING` | CHAR | 30 |  | Accuracy - Creeping |
| 35 | `DIALTEST` | CHAR | 8 |  | Dial Test |
| 36 | `ZRESULT` | CHAR | 30 |  | Results |
| 37 | `REMARK1` | CHAR | 30 |  | Remark 1 |
| 38 | `REMARK2` | CHAR | 30 |  | Remark 2 |
| 39 | `REPROGID` | CHAR | 8 |  | Re-Program Rate ID |
| 40 | `LASTREDATE` | CHAR | 10 |  | Last Re-Program Date 'DDMMYYYY' |
| 41 | `REPCOUNT` | NUMC | 4 |  | Re-Program Count |
| 42 | `RESCOUNT` | NUMC | 4 |  | Re-Set Count |
| 43 | `TOTALKWH` | CHAR | 30 |  | Total KWh Reading before Inspection |
| 44 | `OPERATORID` | CHAR | 30 |  | Operator ID |
| 45 | `REMARK3` | CHAR | 30 |  | Remark 3 |
| 46 | `REMARK4` | CHAR | 30 |  | Remark 4 |
| 47 | `UII` | CHAR | 72 |  | Unique Item Identifier |
| 48 | `/UPL/SER_NO` | CHAR | 30 |  | Serial Number |
| 49 | `/UPL/MOB_NO` | CHAR | 30 |  | Mobile Number |
| 50 | `/UPL/SER_PR` | CHAR | 30 |  | Service Provider |
| 51 | `/UPL/FIRMWARE` | CHAR | 12 |  | Firmware Version |
