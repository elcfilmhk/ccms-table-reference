# ZISCSCTSCN
**Description:** Custom table for Call Taking Screen
**Total Fields:** 46
**Key Fields:** MANDT, ZZORIGCALLID

## Programs Using This Table
- `z_bapi_create_tcall===========ft`
- `zctscn`
- `ziscs0110`
- `ziscs0111`
- `ziscs0116`
- `ziscs0117`
- `ziscs0118`
- `ziscs0119`
- `ziscs0123`
- `ziscs_web_create_tcall========ft`
- `ziscs_web_create_tcall_ws=====ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZORIGCALLID` | NUMC | 10 | 🔑 | Original Call ID |
| 3 | `ZZTICKETNO` | CHAR | 12 |  | Ticket Number |
| 4 | `ZZDATETIME` | CHAR | 19 |  | Call date/time received |
| 5 | `ZZDATE` | DATS | 8 |  | Date |
| 6 | `ZZTIME` | TIMS | 6 |  | Time |
| 7 | `ZZPREMISE` | CHAR | 10 |  | Premise |
| 8 | `ZZCONTRACTACCT` | CHAR | 12 |  | Contract Account Number |
| 9 | `ZZDEVICE` | CHAR | 18 |  | Serial Number |
| 10 | `ZZSPATNCD` | CHAR | 2 |  | Special Attention Code |
| 11 | `ZZCONTACTNAME` | CHAR | 40 |  | Contact Name |
| 12 | `ZZCHCONTACT` | CHAR | 20 |  | Chinese Contact Name |
| 13 | `ZZLOCDESC` | CHAR | 80 |  | Location Description |
| 14 | `ZZCHLOCDESC` | CHAR | 80 |  | Location Description |
| 15 | `ZZCTPHONE` | CHAR | 32 |  | Contact Phone |
| 16 | `ZZCTEMAIL` | CHAR | 50 |  | Contact Email |
| 17 | `ZZCALLCODE` | CHAR | 4 |  | Call Type Code |
| 18 | `ZZCALLTYPE` | CHAR | 20 |  | Call Type |
| 19 | `ZZSUBCALL1` | CHAR | 30 |  | Sub Call Type 1 |
| 20 | `ZZSUBCALL2` | CHAR | 30 |  | Sub Call Type 2 |
| 21 | `ZZRCVPROFILE` | CHAR | 1 |  | Received By Profile |
| 22 | `ZZUSERCAT` | CHAR | 20 |  | User Category |
| 23 | `ZZRCVBY` | CHAR | 10 |  | Received By |
| 24 | `ZZRCVPHONE` | CHAR | 8 |  | Received By Contact Phone |
| 25 | `ZZCOMMENT1` | CHAR | 100 |  | Comments |
| 26 | `ZZCOMMENT2` | CHAR | 100 |  | Comments additional line 2 |
| 27 | `ZZCALLBACK` | CHAR | 1 |  | Callback Required |
| 28 | `ZZAPPT` | CHAR | 1 |  | Appointment Required |
| 29 | `ZZDISCON` | CHAR | 1 |  | Disconnect. Followup Completed |
| 30 | `ZZCALLBACKCOMP` | CHAR | 1 |  | Callback Completed |
| 31 | `ZZTYPHOON` | CHAR | 1 |  | Typhoon Mode |
| 32 | `ZZOPCTR` | CHAR | 2 |  | Operation Centre |
| 33 | `ZZSUBSTN` | CHAR | 20 |  | Sub Station Number |
| 34 | `ZZINCID` | CHAR | 11 |  | Incident ID |
| 35 | `ZZINCSTATUS` | CHAR | 32 |  | Incident Status |
| 36 | `ZZREMARK` | CHAR | 100 |  | Callback/Followup Remarks |
| 37 | `ZZTOTCOM` | CHAR | 1 |  | To TCOM |
| 38 | `ZZCONTRACT` | CHAR | 10 |  | Contract |
| 39 | `ZZCALLID` | CHAR | 10 |  | TCOM Call ID |
| 40 | `ZZORIGTCOMID` | CHAR | 10 |  | Original TCOM Call ID |
| 41 | `ZZNUMCODE` | NUMC | 10 |  | Call Code (Numeric) |
| 42 | `ZZCDATETIME` | CHAR | 19 |  | Call date/time saved |
| 43 | `ZZCDATE` | DATS | 8 |  | Date |
| 44 | `ZZCTIME` | TIMS | 6 |  | Time |
| 45 | `ZZINCOMING_CHNL` | CHAR | 1 |  | Incoming Channel |
| 46 | `ZZINCOMING_ID` | CHAR | 50 |  | Incoming ID |
