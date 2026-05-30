# `COBRB`

**Description:** Contract Type — contract category definitions
**Category:** Standard SAP Table
**References:** 2 SELECT statements across 1 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/cobrb/) — validated 2026-05-30, schema v1.0
**Schema fields:** 55 fields | **Data types:** CHAR(31), CUKY(1), CURR(2), DEC(2), NUMC(17), QUAN(1), UNIT(1)

## Key Fields
`BUKRS` | `AUFNR` | `MATNR`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `PERBZ` | PERBZ_LD | — | CHAR | 3 | 0 | Settlement type |
| `URZUO` | URZUO | TSC0D | CHAR | 3 | 0 | Source Assignment |
| `GABJA` | GABJA | — | NUMC | 4 | 0 | Valid-from year |
| `GABPE` | GABPE | — | NUMC | 3 | 0 | Valid-from period |
| `GBISJ` | GBISJ | — | NUMC | 4 | 0 | Valid-to year |
| `GBISP` | GBISP | — | NUMC | 3 | 0 | Valid to |
| `PROZS` | BRGPROZS | — | DEC | 5 | 2 | Settlement percentage rate |
| `AQZIF` | AQZIF | — | DEC | 10 | 0 | Equivalence number for order settlement |
| `BMENG` | BRGMENGE | — | QUAN | 15 | 3 | Quantity for settlement |
| `BEINH` | BRGMEINH | T006 | UNIT | 3 | 0 | Unit of measure |
| `BETRR` | BETRR | — | CURR | 15 | 2 | Amount for amount rule |
| `BWAER` | BRGBWAER | TCURC | CUKY | 5 | 0 | Currency for the amount in the amount rule |
| `BRTYP` | BRTYP | — | CHAR | 2 | 0 | Amount rule type |
| `BREST` | AMOUNTREST | — | CURR | 15 | 2 | Remaining Amount for Amount Settlement w. Amount Rule Cat. |
| `ERSJA` | ERSJA | — | NUMC | 4 | 0 | Year first used |
| `ERSPE` | ERSPE | — | NUMC | 3 | 0 | Period of first use |
| `LETJA` | LETJA | — | NUMC | 4 | 0 | Year last used |
| `LETPE` | LETPE | — | NUMC | 3 | 0 | Period of last use |
| `ZINCL` | DZINCL | — | CHAR | 1 | 0 | &quot;Including overheads&quot; - indicator |
| `DFREG` | DFREG | TKB2A | CHAR | 3 | 0 | Default Rule |
| `AVORG` | AVORG | TJ01 | CHAR | 4 | 0 | Settlement transaction |
| `VERSN` | VERSN | — | CHAR | 3 | 0 | Version |
| `KONTY` | KONTY | — | CHAR | 2 | 0 | Account assignment category |
| `KOKRS` | BRGKOKRS | TKA01 | CHAR | 4 | 0 | Controlling area of receiver |
| `WERKS` | WERKS_D | — | CHAR | 4 | 0 | Plant |
| `GSBER` | GSBER | — | CHAR | 4 | 0 | Business Area |
| `BUKRS` | BUKRS | T001 | CHAR | 4 | 0 | Company Code |
| `HKONT` | SAKNR | SKA1 | CHAR | 10 | 0 | G/L Account Number |
| `PRCTR` | PRCTR | — | CHAR | 10 | 0 | Profit Center |
| `KOSTL` | BRGKOSTL | — | CHAR | 10 | 0 | Receiver cost center |
| `AUFNR` | AUFNR | AUFK | CHAR | 12 | 0 | Order Number |
| `PS_PSP_PNR` | PS_PSP_PNR | — | NUMC | 8 | 0 | Work Breakdown Structure Element (WBS Element) |
| `ANLN1` | ANLN1 | — | CHAR | 12 | 0 | Main Asset Number |
| `ANLN2` | ANLN2 | — | CHAR | 4 | 0 | Asset Subnumber |
| `MATNR` | MATNR | — | CHAR | 18 | 0 | Material Number |
| `BWTAR` | BWTAR_D | T149D | CHAR | 10 | 0 | Valuation Type |
| `NPLNR` | NPLNR | AUFK | CHAR | 12 | 0 | Network Number for Account Assignment |
| `AUFPL` | CO_AUFPL | — | NUMC | 10 | 0 | Routing number of operations in the order |
| `APLZL` | CIM_COUNT | — | NUMC | 8 | 0 | Internal counter |
| `PAOBJNR` | RKEOBJNR | — | NUMC | 10 | 0 | Profitability Segment Number (CO-PA) |
| `PASUBNR` | RKESUBNR | — | NUMC | 4 | 0 | Profitability segment changes (CO-PA) |
| `KDAUF` | KDAUF | VBUK | CHAR | 10 | 0 | Sales Order Number |
| `KDPOS` | KDPOS | — | NUMC | 6 | 0 | Item Number in Sales Order |
| `RECID` | JV_RECIND | T8JJ | CHAR | 2 | 0 | Recovery Indicator |
| `RIFIND` | JV_RIFIND | — | CHAR | 1 | 0 | Derivation Rule for Recovery Indicator in Settlement (JV) |
| `POSNR` | CO_POSNR | — | NUMC | 4 | 0 | Order Item Number |
| `KSTRG` | KSTRG | — | CHAR | 12 | 0 | Cost Object |
| `PRZNR` | CO_PRZNR | — | CHAR | 12 | 0 | Business Process |
| `REC_OBJNR1` | SREC_OBJNR | ONR00 | CHAR | 22 | 0 | Object number for settlement receiver |
| `REC_OBJNR2` | SREC_OBJNR | ONR00 | CHAR | 22 | 0 | Object number for settlement receiver |
| `MRULE` | MANIPRULE | T8JL1 | CHAR | 4 | 0 | Manipulation Rule |
| `EXTNR` | COBR_EXTNR | — | NUMC | 3 | 0 | Distribution Rule Number |
| `STRAT` | CO_STRAT | — | NUMC | 3 | 0 | Method for Determining the Tracing Factor for Settlement |
| `ANBWA` | ANBWA | TABW | CHAR | 3 | 0 | Asset Transaction Type |
| `SRSTRAT` | SR_STRAT | TKB10SA | CHAR | 3 | 0 | Strategy for automatic generation of settlement rules |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ANBWA` | COBRB | ANBWA | TABW |  | |
| `ANBWA` | COBRB | MANDT | TABW |  | |
| `AUFNR` | COBRB | MANDT | AUFK |  | |
| `AUFNR` | COBRB | AUFNR | AUFK |  | |
| `AVORG` | COBRB | AVORG | TJ01 |  | |
| `BEINH` | COBRB | MANDT | T006 |  | |
| `BEINH` | COBRB | BEINH | T006 |  | |
| `BUKRS` | COBRB | MANDT | T001 |  | |
| `BUKRS` | COBRB | BUKRS | T001 |  | |
| `BWAER` | COBRB | MANDT | TCURC |  | |
| `BWAER` | COBRB | BWAER | TCURC |  | |
| `BWTAR` | COBRB | MANDT | T149D |  | |
| `BWTAR` | COBRB | BWTAR | T149D |  | |
| `DFREG` | COBRB | MANDT | TKB2A |  | |
| `DFREG` | COBRB | DFREG | TKB2A |  | |
| `HKONT` | T001 | KTOPL | SKA1 |  | |
| `HKONT` | COBRB | HKONT | SKA1 |  | |
| `HKONT` | COBRB | MANDT | SKA1 |  | |
| `KDAUF` | COBRB | MANDT | VBUK |  | |
| `KDAUF` | COBRB | KDAUF | VBUK |  | |
| `KOKRS` | COBRB | KOKRS | TKA01 |  | |
| `KOKRS` | COBRB | MANDT | TKA01 |  | |
| `MANDT` | COBRB | MANDT | T000 |  | |
| `MRULE` | COBRB | MANDT | T8JL1 |  | |
| `MRULE` | COBRB | KOKRS | T8JL1 |  | |
| `MRULE` | COBRB | MRULE | T8JL1 |  | |
| `NPLNR` | COBRB | MANDT | AUFK |  | |
| `NPLNR` | COBRB | NPLNR | AUFK |  | |
| `OBJNR` | COBRB | MANDT | ONR00 |  | |
| `OBJNR` | COBRB | OBJNR | ONR00 |  | |
| `RECID` | COBRB | RECID | T8JJ |  | |
| `RECID` | COBRB | MANDT | T8JJ |  | |
| `RECID` | COBRB | BUKRS | T8JJ |  | |
| `REC_OBJNR1` | COBRB | MANDT | ONR00 |  | |
| `REC_OBJNR1` | COBRB | REC_OBJNR1 | ONR00 |  | |
| `REC_OBJNR2` | COBRB | MANDT | ONR00 |  | |
| `REC_OBJNR2` | COBRB | REC_OBJNR2 | ONR00 |  | |
| `SRSTRAT` | COBRB | SRSTRAT | TKB10SA |  | |
| `URZUO` | COBRA | URSCH | TSC0D |  | |
| `URZUO` | COBRB | URZUO | TSC0D |  | |
| `URZUO` | COBRB | MANDT | TSC0D |  | |
| `URZUO` | &#039;U&#039; |  | TSC0D |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `ziscsriaufk20.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_