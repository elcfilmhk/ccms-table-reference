# ZISCSPROGRESSLST
**Description:** Current and planned orders for progress list
**Total Fields:** 48
**Key Fields:** MANDT, ORDER_ID, OUTAGE_ID

## Programs Using This Table
- `z_bapi_check_tcall============ft`
- `ziscs0110`
- `ziscs0111`
- `ziscs0113`
- `ziscs0116`
- `ziscs0117`
- `ziscs0118`
- `ziscs0125`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ORDER_ID` | CHAR | 24 | 🔑 | Order ID |
| 3 | `OUTAGE_ID` | CHAR | 11 | 🔑 | De-energisation (outage) ID |
| 4 | `REC_INDICATOR` | CHAR | 10 |  | Planned or Current Indicator |
| 5 | `PLANNED_REQ_ID` | NUMC | 10 |  | Planned (Future) Request Identifier |
| 6 | `OUTAGE_STATUS` | CHAR | 40 |  | De-energisation Status |
| 7 | `ORDER_STATUS` | CHAR | 16 |  | Order Status |
| 8 | `ORDER_COMP_TIME` | CHAR | 14 |  | Order Completion Time |
| 9 | `INCIDENT_STATUS` | CHAR | 32 |  | Incident Status |
| 10 | `INCIDENT_ID` | CHAR | 11 |  | Incident Identifier |
| 11 | `INCIDENT_TIME` | CHAR | 14 |  | Incident Start Time |
| 12 | `PROJECT_ID` | NUMC | 10 |  | Project or Request Identifier |
| 13 | `CUST_MSG` | CHAR | 255 |  | Customer Message |
| 14 | `AFFECTED_AREA` | CHAR | 255 |  | Affected Area |
| 15 | `ORDER_LOCATION` | CHAR | 80 |  | Order or De-energisation Location |
| 16 | `OUTAGE_TYPE` | CHAR | 20 |  | De-energisation Type |
| 17 | `CRITICAL_CUST` | NUMC | 1 |  | Critical Customers Affected Flag |
| 18 | `PLANNED_REASON` | CHAR | 100 |  | Planned Reason 1 |
| 19 | `OPERATION_CTR` | CHAR | 2 |  | Operation Center |
| 20 | `REGION` | CHAR | 10 |  | Region |
| 21 | `MAIN_CREW` | CHAR | 32 |  | Main Crew |
| 22 | `LEAD_CREW_MBR` | CHAR | 24 |  | Lead Crew Member |
| 23 | `CONTACT_INFO` | CHAR | 100 |  | Crew Contact Information |
| 24 | `PL_OUTAGE_FROM` | CHAR | 14 |  | Planned Outage Required From Time |
| 25 | `PL_OUTAGE_TO` | CHAR | 14 |  | Planned Outage Required To Time |
| 26 | `OUTAGE_TIME` | CHAR | 14 |  | De-energisation Start Time |
| 27 | `OR_RESTORE_TIME` | CHAR | 14 |  | Original Estimated Restoration Time |
| 28 | `RESTORE_TIME` | CHAR | 14 |  | Estimated Restoration Time |
| 29 | `ACK_TIME` | CHAR | 14 |  | Order First Dispatch (Acknowledged) Time |
| 30 | `ARRIVAL_TIME` | CHAR | 14 |  | Order First Arrival Time |
| 31 | `APP_TIME` | CHAR | 14 |  | Appointment Time |
| 32 | `OUT_RESTORE_STAT` | CHAR | 60 |  | De-energisation Restoration Status |
| 33 | `OUT_RESTORE_TIME` | CHAR | 14 |  | De-energisation Restoration Time |
| 34 | `NO_OUT_CUST` | NUMC | 10 |  | De-energisation Number of Customers Affected |
| 35 | `FULL_REST_TIME` | CHAR | 14 |  | Full Restoration Time |
| 36 | `MAX_NO_CUST` | NUMC | 10 |  | Maximum Number of Customers Affected |
| 37 | `VOLTAGE_LEVEL` | CHAR | 10 |  | Voltage Level |
| 38 | `KVA_LOAD_LOSS` | NUMC | 10 |  | KVA Load Loss |
| 39 | `CAUSE` | CHAR | 32 |  | Cause |
| 40 | `ORDER_COMMENTS` | CHAR | 200 |  | Order Comments |
| 41 | `DATE_CREATED` | CHAR | 14 |  | Date Created |
| 42 | `DATE_UPDATED` | CHAR | 14 |  | Date Updated |
| 43 | `MARK_DELETE` | CHAR | 1 |  | Mark the record as deleted |
| 44 | `ORIGINATOR` | CHAR | 48 |  | Originator |
| 45 | `ORIGINATOR_PHONE` | CHAR | 32 |  | Originator Phone Number |
| 46 | `SHORT_NOTICE` | CHAR | 1 |  | Short Notice Flag |
| 47 | `PL_OUTAGE_FROM2` | CHAR | 14 |  | Planned Outage Required From Time 2 |
| 48 | `PL_OUTAGE_TO2` | CHAR | 14 |  | Planned Outage Required To Time 2 |
