# ZDEPOSIT
**Description:** Security Deposit Strucure
**Total Fields:** 57
**Key Fields:** _none_

## Programs Using This Table
- `z_generate_contact============ft`
- `z_get_security_deposit========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `ZTRIGGER` | LANG | 1 |  | Logon Language |
| 2 | `HIERARCHI` | LANG | 1 |  | Logon Language |
| 3 | `PARENT_VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 5 | `BPKIND` | CHAR | 4 |  | Business Partner Type |
| 6 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 7 | `KTOKL` | CHAR | 4 |  | Account class |
| 8 | `KTOTX` | CHAR | 40 |  | Text for account class |
| 9 | `NAME` | CHAR | 40 |  | Name 1 of organization |
| 10 | `VERTRAG` | CHAR | 10 |  | Contract |
| 11 | `VTREF` | CHAR | 20 |  | Reference Specifications from Contract |
| 12 | `EINZDAT` | DATS | 8 |  | Move-in date from legacy system |
| 13 | `SEC_START` | DATS | 8 |  | Start date for security deposit |
| 14 | `ANLAGE` | CHAR | 10 |  | Installation |
| 15 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 16 | `MRU` | CHAR | 8 |  | Meter Reading Unit |
| 17 | `TOT_DEPOSIT` | CURR | 13 |  | Currency-dependent amount |
| 18 | `REQ_DEPOSIT` | CURR | 13 |  | Currency-dependent amount |
| 19 | `INS_DEPOSIT` | CURR | 13 |  | Currency-dependent amount |
| 20 | `INS_PERCENT` | INT4 | 10 |  | Natural number |
| 21 | `FUR_DEPOSIT` | CURR | 13 |  | Currency-dependent amount |
| 22 | `AVG_75` | CURR | 13 |  | Net amount of billing line item |
| 23 | `HIGH_60` | CURR | 13 |  | Net amount of billing line item |
| 24 | `CONSUMP1` | CURR | 13 |  | Currency-dependent amount |
| 25 | `CONSUMP2` | CURR | 13 |  | Currency-dependent amount |
| 26 | `CONSUMP3` | CURR | 13 |  | Currency-dependent amount |
| 27 | `BIS1` | DATS | 8 |  | Date at Which a Time Slice Expires |
| 28 | `BIS2` | DATS | 8 |  | Date at Which a Time Slice Expires |
| 29 | `BIS3` | DATS | 8 |  | Date at Which a Time Slice Expires |
| 30 | `WAERS` | CUKY | 5 |  | Currency Key |
| 31 | `CREDIT1` | NUMC | 4 |  | Creditw. no. for January |
| 32 | `CREDIT2` | NUMC | 4 |  | Creditworthiness number for February |
| 33 | `CREDIT3` | NUMC | 4 |  | Creditworthiness number for March |
| 34 | `CREDIT4` | NUMC | 4 |  | Creditworthiness number for April |
| 35 | `CREDIT5` | NUMC | 4 |  | Creditworthiness number for May |
| 36 | `CREDIT6` | NUMC | 4 |  | Creditw. no. for June |
| 37 | `CREDIT7` | NUMC | 4 |  | Creditw.no. for July |
| 38 | `CREDIT8` | NUMC | 4 |  | Creditw.no. for August |
| 39 | `CREDIT9` | NUMC | 4 |  | Creditw.no. for September |
| 40 | `CREDIT10` | NUMC | 4 |  | Creditw.no. for October |
| 41 | `CREDIT11` | NUMC | 4 |  | Creditw.no. for November |
| 42 | `CREDIT12` | NUMC | 4 |  | Creditworthiness number for December |
| 43 | `CREDIT13` | NUMC | 4 |  | Creditw. no. for January |
| 44 | `CREDIT14` | NUMC | 4 |  | Creditw. no. for January |
| 45 | `CREDIT15` | NUMC | 4 |  | Creditw. no. for January |
| 46 | `CREDIT16` | NUMC | 4 |  | Creditw. no. for January |
| 47 | `CREDIT17` | NUMC | 4 |  | Creditw. no. for January |
| 48 | `CREDIT18` | NUMC | 4 |  | Creditw. no. for January |
| 49 | `CREDIT19` | NUMC | 4 |  | Creditw. no. for January |
| 50 | `CREDIT20` | NUMC | 4 |  | Creditw. no. for January |
| 51 | `CREDIT21` | NUMC | 4 |  | Creditw. no. for January |
| 52 | `CREDIT22` | NUMC | 4 |  | Creditw. no. for January |
| 53 | `CREDIT23` | NUMC | 4 |  | Creditw. no. for January |
| 54 | `CREDIT24` | NUMC | 4 |  | Creditw. no. for January |
| 55 | `BP_MANUAL` | NUMC | 4 |  | Manual Creditworthiness |
| 56 | `BP_SYSTEM` | NUMC | 3 |  | Creditworthiness factor as a percentage |
| 57 | `AC_SYSTEM` | NUMC | 4 |  | Creditworthiness |
