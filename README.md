# Rings of Risk: supporting material (draft)

Supporting material for the working draft *Rings of Risk: Consequence and Reachability in Application-Code Vulnerability Chains* by John Pellew and Faizan Raza (Kolega.Dev).

**Status: draft, subject to revision.**

The 15 applications studied are **pseudonymised** (Aspen, Basalt, Cobalt, …). Application names, versions, vulnerability identifiers, source locations and project-specific wording are withheld to respect coordinated vulnerability disclosure. Each application is described by what it does, with size and adoption given as coarse bands in the paper.

## Contents

| Path | What it is |
|---|---|
| [`paper/Rings-of-Risk-DRAFT.pdf`](paper/Rings-of-Risk-DRAFT.pdf) | The working draft paper. |
| [`evidence/route-register-anonymised.md`](evidence/route-register-anonymised.md) | The 246 source-anchored candidate route records, by application. |
| [`evidence/composed-path-register-anonymised.md`](evidence/composed-path-register-anonymised.md) | The 54 exact-ID joined path records, including joins rejected on source review. |
| [`evidence/access-ring-classification-anonymised.md`](evidence/access-ring-classification-anonymised.md) | How capabilities, outcomes and enabling steps were assigned to Access Rings (AR1–AR5). |
| [`evidence/route-audit-anonymised.json`](evidence/route-audit-anonymised.json) | The machine-readable route audit behind the registers and the paper's maps. |

## Reading notes

- Consequence bands follow the paper: B1 Critical, B2 Major, B3 Moderate, B4 Limited.
- Every route is a candidate route supported by source review under stated conditions. None is an observed or demonstrated attack, and the applications were not run.
- Ring assignments are a reviewed reading of the audit text, not a measured quantity.
- Findings are numbered per application (for example `Cobalt-F07`). Where one generic label covers several distinct underlying items, a letter suffix tells them apart.
