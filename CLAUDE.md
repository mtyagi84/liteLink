# ZYX ERP Project — Context

## Overview
_TBD — already-built Oracle APEX ERP application. Which modules/domains it covers, business purpose, and current state (in production? being actively extended?) not yet described._

**This project has no connection to VMS or AirFareApp** — separate DB objects, separate APEX application, separate schema/workspace. Do not assume shared tables, packages, or conventions from those projects.

---

## Tech Stack
- **Frontend**: Oracle APEX
- **Database**: Oracle (instance/workspace TBD — confirm whether same or different OCI tenancy from VMS, even though schema itself is separate)
- **Language**: PL/SQL
- **Development approach**: Local APEX export files (`.sql` page/app exports) placed under `apex-exports/`, developed/customized with the APEXLang skill, then reimported/deployed — not live SQLcl-connection development.

---

## Naming Convention
_TBD — no prefix chosen yet. For reference, sibling projects use `PAAS_`/`HCM_` (VMS) and `AF_` (AirFareApp) to stay visually distinct within their own shared schemas; ZYX's schema is separate so a prefix isn't strictly required for that reason, but pick one if it helps distinguish ZYX's own object groups internally._

---

## Core Tables
_TBD — no DDL reviewed yet._

---

## Key Packages & Procedures
_TBD._

---

## Business Logic Notes
_TBD._

---

## Files in This Repo
| File/Folder | Contents |
|------|---------|
| `apex-exports/` | The ERP application's APEX page/app export `.sql` files — the source APEXLang works from locally |
