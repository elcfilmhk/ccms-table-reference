# ZISCAGENDA
**Description:** General Custom Table to populate data
**Total Fields:** 8
**Key Fields:** MANDT, OBJ_NAME, TYPE, COUNTER

## Programs Using This Table
- `zbapi_get_active_cainfo=======ft`
- `zdiscon`
- `zisbi0001`
- `zisbi0003`
- `zisbi0009`
- `zisbi0014`
- `zisbi0014t`
- `zisbi0042`
- `zisbi0042_1`
- `zisbi0042_2`
- `zisbi0042_ami`
- `zisbi0042_newfm`
- `zisbi0048`
- `zisbi0055`
- `zisbi0056`
- `zisbi0062`
- `zisbi0062_1`
- `zisbi0062_1t`
- `zisbi0063`
- `zisbi0071`
- `zisbi0071_tmp`
- `zisbi0104`
- `zisbi0108`
- `zisbi0132`
- `zisbi0167_bw`
- `zisbi0174`
- `zisbi0201`
- `zisbi0202`
- `zisbi0213`
- `zisbi0216`
- `zisbi0270`
- `zisbi0270t`
- `zisbi0271`
- `ziscrm0009`
- `ziscrm0010`
- `ziscrm0020`
- `ziscrm0030`
- `ziscrm0031`
- `ziscrm0034`
- `ziscrm0035`
- `ziscrm0305`
- `ziscrmaddrcomp`
- `ziscs0004`
- `ziscs0038`
- `ziscs0060`
- `ziscs0060_so_nr`
- `ziscs0085`
- `ziscs0099`
- `ziscs0106`
- `ziscs0135`
- `ziscs0141`
- `ziscs0156`
- `ziscs0161`
- `ziscs0170`
- `ziscs0172`
- `ziscs0173`
- `ziscs0174`
- `ziscs0176`
- `ziscs0178`
- `ziscs0184`
- `ziscs0187`
- `ziscs0201`
- `ziscs0205`
- `ziscs0207`
- `ziscs0210`
- `ziscs0216`
- `ziscs0218`
- `ziscs0222`
- `ziscs0225`
- `ziscs0226a`
- `ziscs0226b`
- `ziscs0226c`
- `ziscs0226d`
- `ziscs0226e`
- `ziscs0226f`
- `ziscs0226g`
- `ziscs0228`
- `ziscs0229`
- `ziscs0237`
- `ziscs0238`
- `ziscs0244`
- `ziscs0251`
- `ziscs0256`
- `ziscs0259`
- `ziscs0282`
- `ziscs0284`
- `ziscs0288`
- `ziscs0297`
- `ziscs0298`
- `ziscs0303`
- `ziscs0304`
- `ziscs0305`
- `ziscs0307`
- `ziscs0309`
- `ziscs0312`
- `ziscs0313`
- `ziscs0314`
- `ziscs0317`
- `ziscs0320`
- `ziscs0321`
- `ziscs0378`
- `ziscs0400`
- `ziscs0402`
- `ziscs0437`
- `ziscs0449`
- `ziscs0456`
- `ziscs0457`
- `ziscs0458`
- `ziscs0459`
- `ziscs0463`
- `ziscs0478_eec`
- `ziscs0500`
- `ziscs0504`
- `ziscs0541`
- `ziscs0705`
- `ziscs0710`
- `ziscs0831`
- `ziscs0859`
- `ziscsbnka`
- `zisdm0022`
- `zisdm0022_bulk`
- `zisdm0116`
- `zisdm0118`
- `zisfi0001`
- `zisfi0003`
- `zisfi0036`
- `zisfi0059`
- `zisfi0072`
- `zisfi0072_new`
- `zisfi0083`
- `zisfi0083_1`
- `zisfi0083_1t`
- `zisfi0083_2`
- `zisfi0083_m2`
- `zisfi0083_m2t`
- `zisfi0101`
- `zisfi0102`
- `zisfi0110`
- `zisfi0111`
- `zisfi0118`
- `zisfi0124`
- `zisfi0130`
- `zisfi0131`
- `zisfi0138`
- `zisfi0141_bkgrd`
- `zisfi0159`
- `zisfi0189`
- `zisfi0190`
- `zisfi0223`
- `zisfi0239`
- `zisfi0247`
- `zisfi0251`
- `zisfi0255`
- `zisfi0277`
- `zisfi0278`
- `zisfi0280`
- `zisfi0317`
- `zisfi0323`
- `zisfi0334`
- `zissd00092`
- `zissd00096`
- `zissd00111`
- `zpremises`
- `zprintdoc`
- `zreaexcep`
- `zreprjt00`
- `ztest_zisfi0277`
- `ztest_zisfi0278`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OBJ_NAME` | CHAR | 40 | 🔑 | Object Name in Object Directory |
| 3 | `TYPE` | CHAR | 30 | 🔑 | ABAP: Name of Variant Variable |
| 4 | `COUNTER` | NUMC | 4 | 🔑 | ABAP: Current selection number |
| 5 | `SIGN` | CHAR | 1 |  | ABAP: ID: I/E (include/exclude values) |
| 6 | `OPTI` | CHAR | 2 |  | ABAP: Selection option (EQ/BT/CP/...) |
| 7 | `LOW` | CHAR | 60 |  | Structure of generic SELECT-OPTION for (dynamic selections) |
| 8 | `HIGH` | CHAR | 60 |  | Structure of generic SELECT-OPTION for (dynamic selections) |
