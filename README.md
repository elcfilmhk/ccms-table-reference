# CCMS Table Reference

**Total tables:** 2098

Each `.md` file in the `tables/` directory represents one CCMS table with:
- Table name and description
- Key fields (from SAP Data Dictionary)
- All field definitions (name, datatype, length, description)
- Programs in the CCMS repo that use this table

## Repository Structure

```
ccms-table-reference/
├── README.md               (this file)
└── tables/
    ├── ZIS_EEC_REAPPLN.md  (FiT Application - 91 fields)
    ├── ZIS_EEC_RESYSMTR.md (FiT Device-Meter - 26 fields)
    ├── ZISBI_FITREBATE.md  (FiT Rebate per device - 19 fields)
    └── ... (2,095 more tables)
```

## Table Index

### Z-Tables (2082 tables)
All custom CCMS tables. Tables starting with `Z`.

### YZ* Tables (16 tables)
SAP RSSCD000 auto-generated change-document structures.

### Other (0 tables)
Tables not starting with Z or YZ (mostly legacy/custom).

## Notes

- **Source:** Parsed from `dictionary-*.html` files in CCMS repo (`/home/vboxuser/CCMS/`)
- **Program associations:** Derived from subdirectory names in program directories
- **Standard SAP tables** (EVER, FKKVKP, DFKKOP, etc.) are NOT included — they don't have dictionary HTML files in the CCMS repo. See the main reference doc for their keys.
- **Generated:** Auto-parsed from SAP Data Dictionary HTML exports

## Selected Important Tables

| Table | Description | Fields | Programs |
|-------|-------------|--------|----------|
| `ZIS_EEC_REAPPLN` | FiT Application | 91 | ziscs0208 |
| `ZIS_EEC_RESYSMTR` | FiT Device-Location-Meter | 26 | ziscs0208 |
| `ZIS_EEC_FITAPRV` | FiT Approval | 52 | ziscs0208 |
| `ZISBI_FITREBATE` | FiT Rebate per Device | 19 | zisbi0105 |
| `ZCREATECA` | Automated Move-in | 138 | zcreateca |
| `ZTERMINATECA` | Termination CA | 27 | zcreateca |
| `ZCAZZCSSUS` | CSS User Profile | 55 | ziscs0330 |
| `ZISCS_CI_CUST` | Customer Info | 40+ | ziscs0315 |
| `ZISMDMETER` | MDMS Meter | 38 | zisdm0101 |
| `ZBAICCNFIG` | Interface Config | 7 | zisdm0256, ziscs0117 |
| `ZBACBMHIST` | Batch Migration History | 23 | zbacbjob |
| `ZISMWALERTMSG` | Middleware Alert | 8 | zismw0001 |
| `ZISOUTBOUND_SMS` | Outbound SMS | 55 | ziscs0230 |
| `ZJIVS_ARCHL_LOG` | JiVS ArchiveLink Log | 21 | zjivs0001 |

---

_Generated from CCMS repo dictionary HTML files. Standard SAP table schemas require SE11 or ChromaDB RAG access._
