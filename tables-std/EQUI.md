# `EQUI`

**Description:** Equipment — equipment master
**Category:** Standard SAP Table
**References:** 425 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/equi/) — validated 2026-05-30, schema v1.0
**Schema fields:** 88 fields | **Data types:** CHAR(67), CUKY(1), CURR(2), DATS(10), LANG(1), NUMC(4), QUAN(1), RAW(1), UNIT(1)

## Key Fields
`MATNR`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `ERDAT` | ERDAT | — | DATS | 8 | 0 | Date on Which Record Was Created |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `EQASP` | EQASP | T002 | LANG | 1 | 0 | Language in Which the Piece of Equipment was Entered |
| `AEDAT` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `AENAM` | AENAM | — | CHAR | 12 | 0 | Name of Person Who Changed Object |
| `BEGRU` | IAUTG | T370B | CHAR | 4 | 0 | Technical object authorization group |
| `EQTYP` | EQTYP | T370T | CHAR | 1 | 0 | Equipment category |
| `EQART` | EQART | T370K | CHAR | 10 | 0 | Type of Technical Object |
| `LVORM` | RESERVE_CHAR_001 | — | CHAR | 1 | 0 | SAP Development Reserve: Format CHAR, Length 1 |
| `INVNR` | INVNR | — | CHAR | 25 | 0 | Inventory number |
| `GROES` | GROSS | — | CHAR | 18 | 0 | Size/dimension |
| `BRGEW` | OBJ_WEIGHT | — | QUAN | 13 | 3 | Weight of object |
| `GEWEI` | WEIGHT_UNIT | T006 | UNIT | 3 | 0 | Unit of weight |
| `ANSDT` | ANDTI | — | DATS | 8 | 0 | Acquisition date |
| `ANSWT` | ANSWT | — | CURR | 13 | 2 | Acquisition Value |
| `WAERS` | WAERS | TCURC | CUKY | 5 | 0 | Currency Key |
| `ELIEF` | ELIEF | LFA1 | CHAR | 10 | 0 | Vendor number |
| `GWLEN` | GWLEN | — | DATS | 8 | 0 | Date on which the warranty ends |
| `GWLDT` | GWLDT | — | DATS | 8 | 0 | Warranty Date |
| `WDBWT` | WDBWT | — | CURR | 13 | 2 | Equipment replacement value |
| `HERST` | HERST | — | CHAR | 30 | 0 | Manufacturer of asset |
| `HERLD` | HERLD | T005 | CHAR | 3 | 0 | Country of manufacture |
| `HZEIN` | HZEIN | — | CHAR | 30 | 0 | Manufacturer drawing number |
| `SERGE` | SERGE | — | CHAR | 30 | 0 | Manufacturer serial number |
| `TYPBZ` | TYPBZ | — | CHAR | 20 | 0 | Manufacturer model number |
| `BAUJJ` | BAUJJ | — | CHAR | 4 | 0 | Year of construction |
| `BAUMM` | BAUMM | — | CHAR | 2 | 0 | Month of construction |
| `APLKZ` | APLKZ | — | CHAR | 1 | 0 | Indicator: Task List Exists |
| `AULDT` | AULDT | — | DATS | 8 | 0 | First delivery date of the equipment |
| `INBDT` | ILOM_DATAB | — | DATS | 8 | 0 | Start-up Date of the Technical Object |
| `GERNR` | GERNR | — | CHAR | 18 | 0 | Serial Number |
| `EQLFN` | EQLFN | — | NUMC | 3 | 0 | Consecutive numbering of EquipUsagePeriods on same day |
| `GWLDV` | GWLDV | — | DATS | 8 | 0 | Warranty date for Sales and Distribution |
| `EQDAT` | EQDAT | — | DATS | 8 | 0 | Date, intended for SAP internal use |
| `EQBER` | EQBER | — | CHAR | 30 | 0 | Technical information, intended for SAP internal use |
| `EQNUM` | EQNUM | — | NUMC | 9 | 0 | Numerical field, intended for SAP internal use |
| `OBJNR` | J_OBJNR | — | CHAR | 22 | 0 | Object number |
| `EQSNR` | EQSNR | EQSE | CHAR | 18 | 0 | EQSE Number |
| `CUOBJ` | CUOBJ | — | NUMC | 18 | 0 | Configuration (internal object number) |
| `KRFKZ` | KRFKZ | — | CHAR | 1 | 0 | Referenced Configuration |
| `KMATN` | KMATN | MARA | CHAR | 18 | 0 | Configurable Material |
| `MATNR` | MATNR | MARA | CHAR | 18 | 0 | Material Number |
| `SERNR` | GERNR | — | CHAR | 18 | 0 | Serial Number |
| `WERK` | WERKS_D | T001W | CHAR | 4 | 0 | Plant |
| `LAGER` | LGORT_D | T001L | CHAR | 4 | 0 | Storage Location |
| `CHARGE` | CHARG_D | MCH1 | CHAR | 10 | 0 | Batch Number |
| `KUNDE` | KUNDSE | KNA1 | CHAR | 10 | 0 | Customer to Whom Serial Number was Delivered |
| `WARPL` | WARPL | MPLA | CHAR | 12 | 0 | Maintenance Plan |
| `IMRC_POINT` | IMRC_POINT | IMPTT | CHAR | 12 | 0 | Measuring Point |
| `REVLV` | REVLV | — | CHAR | 2 | 0 | Revision Level |
| `MGANR` | MGANR | BGMK | CHAR | 20 | 0 | Master warranty number |
| `BEGRUI` | INH_BEGRUI | — | CHAR | 1 | 0 | Data origin for authorization group field |
| `S_EQUI` | EQUIP_KNZ | — | CHAR | 1 | 0 | Equipment data exists |
| `S_SERIAL` | KZKSD | — | CHAR | 1 | 0 | Serial data when maintaining equipment |
| `S_KONFI` | KONFKNZ | — | CHAR | 1 | 0 | Configuration supported |
| `S_SALE` | SDKNZ | — | CHAR | 1 | 0 | Sales equipment |
| `S_FHM` | FHMKZ | — | CHAR | 1 | 0 | Equip. category relevant to production resources and tools |
| `S_ELSE` | ELSE_KNZ | — | CHAR | 1 | 0 | Indicator: Other Data Active |
| `S_ISU` | ISU_KNZ | — | CHAR | 1 | 0 | IS-U data |
| `S_EQBS` | KZEQBS | — | CHAR | 1 | 0 | EQSI Exists |
| `S_FLEET` | FLEET_KNZ | — | CHAR | 1 | 0 | Indicator: Fleet object active |
| `BSTVP` | BSTVP | — | CHAR | 1 | 0 | Stock Check for Serial Numbers |
| `SPARTE` | SPARTE | TSPA | CHAR | 2 | 0 | Division |
| `HANDLE` | ITOBTMP_TSEGGUID | — | CHAR | 22 | 0 | SAP Development Reserve: Integration of Date Segment (Key) |
| `TSEGTP` | ITOBTMP_TSEGTEMPLA | — | CHAR | 10 | 0 | SAP Development Reserve: Integration Date Segment (Tempate) |
| `EMATN` | EMATN | — | CHAR | 18 | 0 | Material Number Corresponding to Manufacturer Part Number |
| `ACT_CHANGE_AA` | AAPM_ACT_CHANGE_AA | — | CHAR | 1 | 0 | Change Equipment Master when Changing Asset |
| `S_CC` | CCC_KNZ | — | CHAR | 1 | 0 | Configuration Control Data |
| `DATLWB` | DATLWB | — | DATS | 8 | 0 | Date of Last Goods Movement |
| `UII` | UII_CHAR72 | — | CHAR | 72 | 0 | Unique Item Identifier |
| `IUID_TYPE` | IUID_TYPE | TIUID_TYPE | CHAR | 10 | 0 | Structure Type of UII |
| `UII_PLANT` | UII_PLANT | — | CHAR | 4 | 0 | Plant Responsible for UII |
| `/GEP/PASSENGER` | /GEP/FLEET_D_PASSENGER | — | NUMC | 2 | 0 | Number of Passengers |
| `/GEP/AUTOM` | /GEP/FLEET_D_AUTOM | — | CHAR | 1 | 0 | Vehicle Equipment: Automatic Transmission |
| `/GEP/KLIMA` | /GEP/FLEET_D_KLIMA | — | CHAR | 1 | 0 | Vehicle Equipment: Air Conditioning |
| `/GEP/DACHG` | /GEP/FLEET_D_DACHG | — | CHAR | 1 | 0 | Vehicle Equipment: Roof Rack |
| `/GEP/SCHNEEK` | /GEP/FLEET_D_SCHNEEK | — | CHAR | 1 | 0 | Vehicle Equipment: Snow Chains |
| `/GEP/WINTERR` | /GEP/FLEET_D_WINTERR | — | CHAR | 1 | 0 | Vehicle Equipment: Snow Tyres |
| `/GEP/VHCAT` | /GEP/FLEET_D_VHCAT | — | CHAR | 2 | 0 | Vehicle Type |
| `EQEXT_ACTIVE` | /ISDFPS/DE_LM_DB_EQEXT_ACTIVE | — | CHAR | 1 | 0 | Backpack Table /isdfps/lmeqext Active |
| `/MRSS/ID_PROFILE` | /MRSS/T_REQU_UPD | — | CHAR | 1 | 0 | Requirements Profile Was Changed Manually |
| `/MRSS/PROF_GUID` | /MRSS/T_RSG_GUID | — | RAW | 16 | 0 | GUID |
| `/MRSS/PROF_KEY` | /MRSS/T_RSG_REQUID | — | CHAR | 10 | 0 | Profile Key |
| `/MRSS/DATACHANGE` | /MRSS/T_USCREENCTL_DATACHANGED | — | CHAR | 1 | 0 | Data was changed in the controls on the user screen |
| `EQUI_SRTYPE` | COCF_SR_SRTYPE | COCF_CU_SRTYPE | CHAR | 10 | 0 | Shift Report Type |
| `EQUI_SNTYPE` | COCF_SN_SNTYPE | TQ80 | CHAR | 2 | 0 | Shift Note Type |
| `EQLB_DUTY` | DIACL_DUTY | — | CHAR | 1 | 0 | Logbook Duty |
| `EQLB_HIDE` | DIACL_HIDE | — | CHAR | 1 | 0 | Hide Logbook Display |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `BEGRU` | EQUI | MANDT | T370B |  | |
| `BEGRU` | EQUI | BEGRU | T370B |  | |
| `CHARGE` | EQUI | MANDT | MCH1 |  | |
| `CHARGE` | EQUI | MATNR | MCH1 |  | |
| `CHARGE` | EQUI | CHARGE | MCH1 |  | |
| `ELIEF` | EQUI | ELIEF | LFA1 |  | |
| `ELIEF` | EQUI | MANDT | LFA1 |  | |
| `EQART` | EQUI | MANDT | T370K |  | |
| `EQART` | EQUI | EQART | T370K |  | |
| `EQASP` | EQUI | EQASP | T002 |  | |
| `EQSNR` | EQUI | MANDT | EQSE |  | |
| `EQSNR` | EQUI | EQSNR | EQSE |  | |
| `EQTYP` | EQUI | MANDT | T370T |  | |
| `EQTYP` | EQUI | EQTYP | T370T |  | |
| `EQUI_SNTYPE` | EQUI | MANDT | TQ80 |  | |
| `EQUI_SNTYPE` | EQUI | EQUI_SNTYPE | TQ80 |  | |
| `EQUI_SRTYPE` | EQUI | MANDT | COCF_CU_SRTYPE |  | |
| `EQUI_SRTYPE` | EQUI | EQUI_SRTYPE | COCF_CU_SRTYPE |  | |
| `GEWEI` | EQUI | MANDT | T006 |  | |
| `GEWEI` | EQUI | GEWEI | T006 |  | |
| `HERLD` | EQUI | MANDT | T005 |  | |
| `HERLD` | EQUI | HERLD | T005 |  | |
| `IMRC_POINT` | EQUI | MANDT | IMPTT |  | |
| `IMRC_POINT` | EQUI | IMRC_POINT | IMPTT |  | |
| `IUID_TYPE` | EQUI | IUID_TYPE | TIUID_TYPE |  | |
| `KMATN` | EQUI | MANDT | MARA |  | |
| `KMATN` | EQUI | KMATN | MARA |  | |
| `KUNDE` | EQUI | MANDT | KNA1 |  | |
| `KUNDE` | EQUI | KUNDE | KNA1 |  | |
| `LAGER` | EQUI | MANDT | T001L |  | |
| `LAGER` | EQUI | WERK | T001L |  | |
| `LAGER` | EQUI | LAGER | T001L |  | |
| `MANDT` | EQUI | MANDT | T000 |  | |
| `MATNR` | EQUI | MANDT | MARA |  | |
| `MATNR` | EQUI | MATNR | MARA |  | |
| `MGANR` | EQUI | MANDT | BGMK |  | |
| `MGANR` | EQUI | MGANR | BGMK |  | |
| `SPARTE` | EQUI | MANDT | TSPA |  | |
| `SPARTE` | EQUI | SPARTE | TSPA |  | |
| `WAERS` | EQUI | MANDT | TCURC |  | |
| `WAERS` | EQUI | WAERS | TCURC |  | |
| `WARPL` | EQUI | MANDT | MPLA |  | |
| `WARPL` | EQUI | WARPL | MPLA |  | |
| `WERK` | EQUI | MANDT | T001W |  | |
| `WERK` | EQUI | WERK | T001W |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `EQUNR`, `OBJNR`, `SERNR`, `aedat`, `aenam`, `eqart`, `equnr`, `erdat`, `ernam`, `groes`, `herst`, `invnr`, `matnr`, `objnr`, `sernr`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `SERNR`, `aedat`, `equnr`, `erdat`, `matnr`, `sernr`

## Join Paths
- `EQUI.EQUNR` → `EGPL.EQUNR` — Equipment → Device

## Programs Using This Table
- `z_iscs_update_meter_so.txt`
- `z_isdm_create_grpbill_chkread.txt`
- `z_isdm_lpb_ready_check.txt`
- `z_isdm_mol_map_fc_loc.txt`
- `ziscs0273.txt`
- `zisdatveri.txt`
- `zisdm0091.txt`
- `zisdm0130.txt`
- `zisdm0152.txt`
- `zisdm0169.txt`
- `zisdm0191.txt`
- `zisdm0235_sub.txt`
- `zisdm0282.txt`
- `zisdm0316.txt`
- `zisdm0382.txt`
- `zisdm0394.txt`
- `zisdm_mru_smp_conn_status.txt`
- `zisem0004.txt`
- `zismd0037_extract.txt`
- `zwfm_get_mr_order_details.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_