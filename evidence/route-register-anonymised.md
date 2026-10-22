# Route register (anonymised)

**246 ordered route records** across 15 applications, which are pseudonymised. Each row is a source-anchored candidate route, not an observed attack. Findings are numbered per application; generic labels replace product-specific wording; source locations are withheld. Where one generic label covers several distinct underlying items, a letter suffix tells them apart. Bands: B1 Critical, B2 Major, B3 Moderate, B4 Limited.

## Aspen: workflow-automation platform (13 routes)

| Route | First step | Next finding | Band | Capability gained (ring) | Candidate outcome (ring) |
|---|---|---|---|---|---|
| Aspen-R01 | code finding: Aspen-F14 | Aspen-F15 | B1 | standard-user account or session obtained (a) (AR4) | server-side code execution (d) (AR1) |
| Aspen-R02 | code finding: Aspen-F11 | Aspen-F08 | B2 | attacker-controlled data written (a) (AR4) | data disclosure beyond the caller's permissions (b) (AR4) |
| Aspen-R03 | code finding: Aspen-F02 | Aspen-F08 | B2 | attacker-controlled data written (a) (AR4) | data disclosure beyond the caller's permissions (c) (AR4) |
| Aspen-R04 | code finding: Aspen-F05 | Aspen-F10 | B2 | another user's credential reused (AR4) | secret or credential disclosure (AR2) |
| Aspen-R05 | code finding: Aspen-F14 | Aspen-F06 | B1 | standard-user account or session obtained (b) (AR4) | server-side code execution (e) (AR1) |
| Aspen-R06 | code finding: Aspen-F04 | Aspen-F09 | B1 | administrator or staff session obtained (AR3) | server-side code execution (b) (AR1) |
| Aspen-R07 | config: publicly exposed endpoint or workflow (b) | Aspen-F13 | B1 | config grants position (AR5) | server-side code execution (c) (AR1) |
| Aspen-R08 | config: publicly exposed endpoint or workflow (d) | Aspen-F16 | B2 | config grants position (AR5) | arbitrary file write on the server (b) (AR2) |
| Aspen-R09 | config: publicly exposed endpoint or workflow (a) | Aspen-F12 | B2 | config grants position (AR5) | data disclosure beyond the caller's permissions (a) (AR4) |
| Aspen-R10 | config: publicly exposed endpoint or workflow (c) | Aspen-F19 | B2 | config grants position (AR5) | arbitrary file write on the server (a) (AR1) |
| Aspen-R11 | code finding: Aspen-F07 | Aspen-F18 | B2 | attacker-controlled data written (b) (AR4) | arbitrary database access (AR2) |
| Aspen-R12 | code finding: Aspen-F03 | Aspen-F17 | B2 | identifier or metadata disclosed (AR5) | unauthorised modification or deletion (AR3) |
| Aspen-R13 | code finding: Aspen-F01 | Aspen-F09 | B1 | administrator session obtained through an indirect route (AR3) | server-side code execution (a) (AR1) |

## Basalt: identity and access management server (49 routes)

| Route | First step | Next finding | Band | Capability gained (ring) | Candidate outcome (ring) |
|---|---|---|---|---|---|
| Basalt-R01 | config: open registration or permissive default | Basalt-F06 | B1 | config grants position (AR4) | platform-level administration taken over (b) (AR2) |
| Basalt-R02 | code finding: Basalt-F08 | Basalt-F06 | B1 | standard-user account or session obtained (a) (AR4) | platform-level administration taken over (b) (AR2) |
| Basalt-R03 | code finding: Basalt-F17 | Basalt-F06 | B1 | standard-user account or session obtained (b) (AR4) | platform-level administration taken over (b) (AR2) |
| Basalt-R04 | credential: credential, token or account obtained (phishing, issuance or reuse) (d) | Basalt-F06 | B1 | credential grants position (AR4) | platform-level administration taken over (b) (AR2) |
| Basalt-R05 | code finding: Basalt-F10 | Basalt-F14 | B1 | platform-level administration obtained (a) (AR2) | server-side code execution (a) (AR1) |
| Basalt-R06 | code finding: Basalt-F09 | Basalt-F14 | B1 | platform-level administration obtained (a) (AR2) | server-side code execution (a) (AR1) |
| Basalt-R07 | code finding: Basalt-F05 | Basalt-F14 | B1 | platform-level administration obtained (b) (AR2) | server-side code execution (a) (AR1) |
| Basalt-R08 | code finding: Basalt-F16 | Basalt-F14 | B1 | administrator session obtained through an indirect route (e) (AR3) | server-side code execution (a) (AR1) |
| Basalt-R09 | code finding: Basalt-F11 | Basalt-F14 | B1 | administrator or staff session obtained (AR3) | server-side code execution (a) (AR1) |
| Basalt-R10 | code finding: Basalt-F20 | Basalt-F14 | B1 | administrator or staff session obtained (AR3) | server-side code execution (a) (AR1) |
| Basalt-R11 | code finding: Basalt-F19 | Basalt-F14 | B1 | administrator session obtained through an indirect route (a) (AR3) | server-side code execution (a) (AR1) |
| Basalt-R12 | code finding: Basalt-F01 | Basalt-F14 | B1 | administrator session obtained through an indirect route (a) (AR3) | server-side code execution (a) (AR1) |
| Basalt-R13 | code finding: Basalt-F03 | Basalt-F14 | B1 | administrator session obtained through an indirect route (d) (AR3) | server-side code execution (a) (AR1) |
| Basalt-R14 | code finding: Basalt-F02 | Basalt-F14 | B1 | administrator session obtained through an indirect route (f) (AR3) | server-side code execution (a) (AR1) |
| Basalt-R15 | code finding: Basalt-F07 | Basalt-F14 | B1 | administrator session obtained through an indirect route (b) (AR3) | server-side code execution (a) (AR1) |
| Basalt-R16 | code finding: Basalt-F12 | Basalt-F14 | B1 | administrator session obtained through an indirect route (c) (AR3) | server-side code execution (a) (AR1) |
| Basalt-R17 | code finding: Basalt-F22 | Basalt-F14 | B1 | identifier or metadata disclosed (b) (AR5) | server-side code execution (b) (AR1) |
| Basalt-R18 | code finding: Basalt-F05 | Basalt-F10 | B1 | administrator session obtained through an indirect route (g) (AR3) | platform-level administration taken over (a) (AR2) |
| Basalt-R19 | code finding: Basalt-F05 | Basalt-F09 | B1 | administrator session obtained through an indirect route (g) (AR3) | platform-level administration taken over (a) (AR2) |
| Basalt-R20 | code finding: Basalt-F16 | Basalt-F10 | B1 | administrator session obtained through an indirect route (g) (AR3) | platform-level administration taken over (a) (AR2) |
| Basalt-R21 | code finding: Basalt-F16 | Basalt-F09 | B1 | administrator session obtained through an indirect route (g) (AR3) | platform-level administration taken over (a) (AR2) |
| Basalt-R22 | code finding: Basalt-F11 | Basalt-F10 | B1 | administrator session obtained through an indirect route (g) (AR3) | platform-level administration taken over (a) (AR2) |
| Basalt-R23 | code finding: Basalt-F11 | Basalt-F09 | B1 | administrator session obtained through an indirect route (g) (AR3) | platform-level administration taken over (a) (AR2) |
| Basalt-R24 | code finding: Basalt-F20 | Basalt-F10 | B1 | administrator session obtained through an indirect route (g) (AR3) | platform-level administration taken over (a) (AR2) |
| Basalt-R25 | code finding: Basalt-F20 | Basalt-F09 | B1 | administrator session obtained through an indirect route (g) (AR3) | platform-level administration taken over (a) (AR2) |
| Basalt-R26 | code finding: Basalt-F19 | Basalt-F10 | B1 | administrator session obtained through an indirect route (g) (AR3) | platform-level administration taken over (a) (AR2) |
| Basalt-R27 | code finding: Basalt-F19 | Basalt-F09 | B1 | administrator session obtained through an indirect route (g) (AR3) | platform-level administration taken over (a) (AR2) |
| Basalt-R28 | code finding: Basalt-F01 | Basalt-F10 | B1 | administrator session obtained through an indirect route (g) (AR3) | platform-level administration taken over (a) (AR2) |
| Basalt-R29 | code finding: Basalt-F01 | Basalt-F09 | B1 | administrator session obtained through an indirect route (g) (AR3) | platform-level administration taken over (a) (AR2) |
| Basalt-R30 | code finding: Basalt-F03 | Basalt-F10 | B1 | administrator session obtained through an indirect route (g) (AR3) | platform-level administration taken over (a) (AR2) |
| Basalt-R31 | code finding: Basalt-F03 | Basalt-F09 | B1 | administrator session obtained through an indirect route (g) (AR3) | platform-level administration taken over (a) (AR2) |
| Basalt-R32 | code finding: Basalt-F02 | Basalt-F10 | B1 | administrator session obtained through an indirect route (g) (AR3) | platform-level administration taken over (a) (AR2) |
| Basalt-R33 | code finding: Basalt-F02 | Basalt-F09 | B1 | administrator session obtained through an indirect route (g) (AR3) | platform-level administration taken over (a) (AR2) |
| Basalt-R34 | code finding: Basalt-F07 | Basalt-F10 | B1 | administrator session obtained through an indirect route (g) (AR3) | platform-level administration taken over (a) (AR2) |
| Basalt-R35 | code finding: Basalt-F07 | Basalt-F09 | B1 | administrator session obtained through an indirect route (g) (AR3) | platform-level administration taken over (a) (AR2) |
| Basalt-R36 | code finding: Basalt-F12 | Basalt-F10 | B1 | administrator session obtained through an indirect route (g) (AR3) | platform-level administration taken over (a) (AR2) |
| Basalt-R37 | code finding: Basalt-F12 | Basalt-F09 | B1 | administrator session obtained through an indirect route (g) (AR3) | platform-level administration taken over (a) (AR2) |
| Basalt-R38 | credential: privileged credential or token obtained | Basalt-F06 | B1 | credential grants position (AR3) | platform-level administration taken over (b) (AR2) |
| Basalt-R39 | credential: credential, token or account obtained (phishing, issuance or reuse) (b) | Basalt-F13 | B1 | credential grants position (AR4) | trust or integrity compromise of a shared component (AR2) |
| Basalt-R40 | code finding: Basalt-F06 | Basalt-F12 | B1 | client-management authority obtained (AR2) | administrator or account session taken over (c) (AR3) |
| Basalt-R41 | credential: credential, token or account obtained (phishing, issuance or reuse) (c) | Basalt-F12 | B1 | credential grants position (AR4) | administrator or account session taken over (b) (AR3) |
| Basalt-R42 | code finding: Basalt-F04 | Basalt-F21 | B2 | identifier or metadata disclosed (a) (AR5) | data disclosure beyond the caller's permissions (AR2) |
| Basalt-R43 | credential: credential, token or account obtained (phishing, issuance or reuse) (f) | Basalt-F02 | B2 | credential grants position (AR4) | administrator or account session taken over (f) (AR3) |
| Basalt-R44 | credential: credential, token or account obtained (phishing, issuance or reuse) (e) | Basalt-F07 | B2 | credential grants position (AR4) | administrator or account session taken over (e) (AR3) |
| Basalt-R45 | credential: credential, token or account obtained (phishing, issuance or reuse) (g) | Basalt-F15 | B2 | credential grants position (AR4) | administrator or account session taken over (a) (AR3) |
| Basalt-R46 | credential: credential, token or account obtained (phishing, issuance or reuse) (a) | Basalt-F19 | B2 | credential grants position (AR4) | administrator or account session taken over (d) (AR3) |
| Basalt-R47 | credential: credential, token or account obtained (phishing, issuance or reuse) (a) | Basalt-F01 | B2 | credential grants position (AR4) | administrator or account session taken over (d) (AR3) |
| Basalt-R48 | code finding: Basalt-F06 | Basalt-F18 | B2 | secret or credential read (AR2) | protected outcome reached (AR2) |
| Basalt-R49 | victim: victim opens attacker-influenced content | Basalt-F16 | B1 | victim grants position (AR4) | administrator or account session taken over (e) (AR3) |

## Cobalt: self-hosted chat front end for language models (8 routes)

| Route | First step | Next finding | Band | Capability gained (ring) | Candidate outcome (ring) |
|---|---|---|---|---|---|
| Cobalt-R01 | code finding: Cobalt-F05 | Cobalt-F03 | B1 | standard-user account or session obtained (a) (AR4) | server-side code execution (c) (AR1) |
| Cobalt-R02 | config: non-default configuration or feature enabled (a) | Cobalt-F08 | B1 | config grants position (AR5) | server-side code execution (a) (AR1) |
| Cobalt-R03 | victim: victim opens attacker-influenced content | Cobalt-F10 | B1 | victim grants position (AR4) | server-side code execution (b) (AR3) |
| Cobalt-R04 | config: non-default configuration or feature enabled (b) | Cobalt-F06 | B1 | config grants position (AR5) | server-side code execution (d) (AR1) |
| Cobalt-R05 | code finding: Cobalt-F09 | Cobalt-F05 | B1 | identifier or metadata disclosed (AR5) | administrator or account session taken over (AR4) |
| Cobalt-R06 | code finding: Cobalt-F05 | Cobalt-F02 | B2 | standard-user account or session obtained (b) (AR4) | data disclosure beyond the caller's permissions (AR4) |
| Cobalt-R07 | code finding: Cobalt-F01 | Cobalt-F04 | B2 | administrator or staff session obtained (AR3) | trust or integrity compromise of a shared component (b) (AR2) |
| Cobalt-R08 | code finding: Cobalt-F07 | Cobalt-F04 | B2 | administrator session obtained through an indirect route (AR3) | trust or integrity compromise of a shared component (a) (AR2) |

## Dune: machine-learning experiment and model-management platform (11 routes)

| Route | First step | Next finding | Band | Capability gained (ring) | Candidate outcome (ring) |
|---|---|---|---|---|---|
| Dune-R01 | artifact: untrusted artifact selected for processing (j) | Dune-F06 | B1 | artifact grants position (AR5) | server-side code execution (g) (AR1) |
| Dune-R02 | artifact: untrusted artifact selected for processing (f) | Dune-F01 | B1 | artifact grants position (AR5) | server-side code execution (i) (AR1) |
| Dune-R03 | input: untrusted input reaches a command | Dune-F10 | B1 | input grants position (AR5) | server-side code execution (f) (AR1) |
| Dune-R04 | artifact: untrusted artifact selected for processing (c) | Dune-F04 | B1 | artifact grants position (AR5) | server-side code execution (c) (AR1) |
| Dune-R05 | artifact: untrusted artifact selected for processing (d) | Dune-F11 | B1 | artifact grants position (AR5) | server-side code execution (d) (AR1) |
| Dune-R06 | artifact: untrusted artifact selected for processing (b) | Dune-F03 | B1 | artifact grants position (AR5) | server-side code execution (b) (AR1) |
| Dune-R07 | artifact: untrusted artifact selected for processing (g) | Dune-F07 | B1 | artifact grants position (AR5) | server-side code execution (h) (AR1) |
| Dune-R08 | artifact: untrusted artifact selected for processing (i) | Dune-F05 | B1 | artifact grants position (AR5) | server-side code execution (k) (AR1) |
| Dune-R09 | artifact: untrusted artifact selected for processing (a) | Dune-F02 | B1 | artifact grants position (AR5) | server-side code execution (a) (AR1) |
| Dune-R10 | artifact: untrusted artifact selected for processing (h) | Dune-F08 | B1 | artifact grants position (AR5) | server-side code execution (j) (AR1) |
| Dune-R11 | artifact: untrusted artifact selected for processing (e) | Dune-F09 | B1 | artifact grants position (AR5) | server-side code execution (e) (AR1) |

## Ember: mobile and web backend service (15 routes)

| Route | First step | Next finding | Band | Capability gained (ring) | Candidate outcome (ring) |
|---|---|---|---|---|---|
| Ember-R01 | credential: credential, token or account obtained (phishing, issuance or reuse) (c) | Ember-F07 | B2 | credential grants position (AR4) | secret or credential disclosure (AR3) |
| Ember-R02 | control_gap: missing rate or lockout control | Ember-F07 | B2 | control_gap grants position (AR5) | secret or credential disclosure (AR3) |
| Ember-R03 | code finding: Ember-F13 | Ember-F12 | B1 | intermediate capability obtained (AR4) | administrator or account session taken over (a) (AR3) |
| Ember-R04 | credential: credential, token or account obtained (phishing, issuance or reuse) (b) | Ember-F09 | B1 | credential grants position (AR4) | write access as any user (c) (AR1) |
| Ember-R05 | credential: credential, token or account obtained (phishing, issuance or reuse) (b) | Ember-F01 | B1 | credential grants position (AR4) | write access as any user (a) (AR1) |
| Ember-R06 | credential: credential, token or account obtained (phishing, issuance or reuse) (b) | Ember-F03 | B2 | credential grants position (AR4) | unauthorised modification or deletion (AR2) |
| Ember-R07 | credential: credential, token or account obtained (phishing, issuance or reuse) (a) | Ember-F09 | B1 | credential grants position (AR4) | write access as any user (b) (AR1) |
| Ember-R08 | credential: credential, token or account obtained (phishing, issuance or reuse) (a) | Ember-F01 | B1 | credential grants position (AR4) | write access as any user (d) (AR1) |
| Ember-R09 | credential: credential, token or account obtained (phishing, issuance or reuse) (a) | Ember-F03 | B2 | credential grants position (AR4) | unauthorised modification or deletion (AR2) |
| Ember-R10 | credential: credential, token or account obtained (phishing, issuance or reuse) (a) | Ember-F04 | B1 | credential grants position (AR4) | arbitrary database access (AR1) |
| Ember-R11 | credential: credential, token or account obtained (phishing, issuance or reuse) (a) | Ember-F06 | B1 | credential grants position (AR4) | arbitrary database access (AR1) |
| Ember-R12 | victim: victim opens attacker-influenced content (a) | Ember-F11 | B2 | victim grants position (AR4) | administrator or account session taken over (c) (AR3) |
| Ember-R13 | victim: victim opens attacker-influenced content (b) | Ember-F08 | B2 | victim grants position (AR4) | administrator or account session taken over (c) (AR3) |
| Ember-R14 | code finding: Ember-F10 | Ember-F02 | B2 | identifier or metadata disclosed (b) (AR5) | administrator or account session taken over (b) (AR4) |
| Ember-R15 | code finding: Ember-F10 | Ember-F05 | B2 | identifier or metadata disclosed (a) (AR5) | data disclosure beyond the caller's permissions (AR2) |

## Fjord: software-translation management platform (13 routes)

| Route | First step | Next finding | Band | Capability gained (ring) | Candidate outcome (ring) |
|---|---|---|---|---|---|
| Fjord-R01 | victim: victim opens attacker-influenced content | Fjord-F02 | B1 | victim grants position (AR4) | platform-level administration taken over (a) (AR2) |
| Fjord-R02 | credential: credential, token or account obtained (phishing, issuance or reuse) | Fjord-F10 | B1 | credential grants position (AR4) | platform-level administration taken over (b) (AR2) |
| Fjord-R03 | victim: victim opens attacker-influenced content (privileged user) | Fjord-F03 | B1 | victim grants position (AR3) | administrator or account session taken over (AR3) |
| Fjord-R04 | victim: victim opens attacker-influenced content (privileged user) | Fjord-F04 | B1 | victim grants position (AR3) | administrator or account session taken over (AR3) |
| Fjord-R05 | code finding: Fjord-F02 | Fjord-F09 | B1 | administrator or staff session obtained (AR3) | server-side code execution (b) (AR1) |
| Fjord-R06 | code finding: Fjord-F10 | Fjord-F01 | B1 | privileged permission granted (AR2) | server-side code execution (b) (AR1) |
| Fjord-R07 | code finding: Fjord-F03 | Fjord-F09 | B1 | administrator session obtained through an indirect route (AR3) | server-side code execution (b) (AR1) |
| Fjord-R08 | code finding: Fjord-F04 | Fjord-F09 | B1 | administrator session obtained through an indirect route (AR3) | server-side code execution (b) (AR1) |
| Fjord-R09 | code finding: Fjord-F08 | Fjord-F06 | B2 | identifier or metadata disclosed (c) (AR5) | server-side code execution (a) (AR2) |
| Fjord-R10 | code finding: Fjord-F07 | Fjord-F06 | B2 | identifier or metadata disclosed (d) (AR5) | server-side code execution (a) (AR2) |
| Fjord-R11 | code finding: Fjord-F05 | Fjord-F06 | B2 | identifier or metadata disclosed (a) (AR5) | server-side code execution (a) (AR2) |
| Fjord-R12 | code finding: Fjord-F11 | Fjord-F06 | B2 | identifier or metadata disclosed (b) (AR5) | server-side code execution (a) (AR2) |
| Fjord-R13 | config: open registration or permissive default | Fjord-F06 | B2 | config grants position (AR4) | trust or integrity compromise of a shared component (AR2) |

## Garnet: publishing and membership platform (21 routes)

| Route | First step | Next finding | Band | Capability gained (ring) | Candidate outcome (ring) |
|---|---|---|---|---|---|
| Garnet-R01 | code finding: Garnet-F08 | Garnet-F02 | B1 | administrator session obtained through an indirect route (g) (AR3) | server-side code execution (AR1) |
| Garnet-R02 | code finding: Garnet-F06 | Garnet-F02 | B1 | administrator or staff session obtained (a) (AR3) | server-side code execution (AR1) |
| Garnet-R03 | code finding: Garnet-F10 | Garnet-F02 | B1 | administrator session obtained through an indirect route (c) (AR3) | server-side code execution (AR1) |
| Garnet-R04 | code finding: Garnet-F18 | Garnet-F02 | B1 | administrator session obtained through an indirect route (b) (AR3) | server-side code execution (AR1) |
| Garnet-R05 | code finding: Garnet-F17 | Garnet-F02 | B1 | administrator session obtained through an indirect route (b) (AR3) | server-side code execution (AR1) |
| Garnet-R06 | code finding: Garnet-F11 | Garnet-F02 | B1 | administrator session obtained through an indirect route (a) (AR3) | server-side code execution (AR1) |
| Garnet-R07 | code finding: Garnet-F01 | Garnet-F02 | B1 | administrator session obtained through an indirect route (b) (AR3) | server-side code execution (AR1) |
| Garnet-R08 | code finding: Garnet-F12 | Garnet-F02 | B1 | administrator session obtained through an indirect route (b) (AR3) | server-side code execution (AR1) |
| Garnet-R09 | code finding: Garnet-F09 | Garnet-F02 | B1 | administrator session obtained through an indirect route (b) (AR3) | server-side code execution (AR1) |
| Garnet-R10 | code finding: Garnet-F07 | Garnet-F02 | B1 | administrator session obtained through an indirect route (b) (AR3) | server-side code execution (AR1) |
| Garnet-R11 | code finding: Garnet-F03 | Garnet-F02 | B1 | administrator session obtained through an indirect route (d) (AR3) | server-side code execution (AR1) |
| Garnet-R12 | code finding: Garnet-F13 | Garnet-F02 | B1 | administrator session obtained through an indirect route (e) (AR3) | server-side code execution (AR1) |
| Garnet-R13 | code finding: Garnet-F20 | Garnet-F03 | B1 | secret or credential read (AR2) | administrator or account session taken over (b) (AR3) |
| Garnet-R14 | code finding: Garnet-F15 | Garnet-F03 | B1 | secret or credential read (AR2) | administrator or account session taken over (b) (AR3) |
| Garnet-R15 | code finding: Garnet-F05 | Garnet-F03 | B1 | secret or credential read (AR2) | administrator or account session taken over (b) (AR3) |
| Garnet-R16 | code finding: Garnet-F19 | Garnet-F03 | B1 | secret or credential read (AR2) | administrator or account session taken over (b) (AR3) |
| Garnet-R17 | code finding: Garnet-F03 | Garnet-F04 | B2 | administrator session obtained through an indirect route (f) (AR3) | secret or credential disclosure (AR2) |
| Garnet-R18 | code finding: Garnet-F03 | Garnet-F16 | B2 | administrator or staff session obtained (b) (AR3) | unauthorised modification or deletion (AR3) |
| Garnet-R19 | config: non-default configuration or feature enabled (a) | Garnet-F17 | B1 | config grants position (AR5) | administrator or account session taken over (c) (AR3) |
| Garnet-R20 | config: non-default configuration or feature enabled (b) | Garnet-F18 | B1 | config grants position (AR5) | administrator or account session taken over (c) (AR3) |
| Garnet-R21 | credential: credential, token or account obtained (phishing, issuance or reuse) | Garnet-F14 | B2 | credential grants position (AR4) | administrator or account session taken over (a) (AR3) |

## Harbor: workflow-orchestration platform (5 routes)

| Route | First step | Next finding | Band | Capability gained (ring) | Candidate outcome (ring) |
|---|---|---|---|---|---|
| Harbor-R01 | code finding: Harbor-F04 | Harbor-F08 | B2 | secret or credential read (AR2) | unauthorised modification or deletion (AR3) |
| Harbor-R02 | code finding: Harbor-F01 | Harbor-F08 | B2 | identifier or metadata disclosed (AR5) | platform-level administration taken over (a) (AR3) |
| Harbor-R03 | code finding: Harbor-F02 | Harbor-F05 | B2 | data readable beyond the caller's permissions (a) (AR4) | platform-level administration taken over (b) (AR2) |
| Harbor-R04 | code finding: Harbor-F06 | Harbor-F03 | B2 | data readable beyond the caller's permissions (b) (AR4) | secret or credential disclosure (AR2) |
| Harbor-R05 | credential: privileged credential or token obtained | Harbor-F07 | B1 | credential grants position (AR3) | server-side code execution (AR1) |

## Indigo: visual builder for language-model agents and pipelines (7 routes)

| Route | First step | Next finding | Band | Capability gained (ring) | Candidate outcome (ring) |
|---|---|---|---|---|---|
| Indigo-R01 | code finding: Indigo-F05 | Indigo-F06 | B2 | identifier or metadata disclosed (c) (AR5) | unauthorised modification or deletion (AR4) |
| Indigo-R02 | code finding: Indigo-F05 | Indigo-F04 | B2 | identifier or metadata disclosed (a) (AR5) | data disclosure beyond the caller's permissions (b) (AR4) |
| Indigo-R03 | code finding: Indigo-F05 | Indigo-F07 | B2 | identifier or metadata disclosed (a) (AR5) | data disclosure beyond the caller's permissions (a) (AR4) |
| Indigo-R04 | code finding: Indigo-F05 | Indigo-F08 | B1 | identifier or metadata disclosed (b) (AR5) | arbitrary file write on the server (AR2) |
| Indigo-R05 | code finding: Indigo-F01 | Indigo-F03 | B2 | secret or credential read (b) (AR2) | secret or credential disclosure (AR2) |
| Indigo-R06 | code finding: Indigo-F02 | Indigo-F03 | B2 | secret or credential read (a) (AR2) | secret or credential disclosure (AR2) |
| Indigo-R07 | config: publicly exposed endpoint or workflow | Indigo-F09 | B1 | config grants position (AR5) | server-side code execution (AR1) |

## Juniper: download manager with a web interface (8 routes)

| Route | First step | Next finding | Band | Capability gained (ring) | Candidate outcome (ring) |
|---|---|---|---|---|---|
| Juniper-R01 | victim: victim opens attacker-influenced content (privileged user) | Juniper-F05 | B1 | victim grants position (AR3) | server-side code execution (g) (AR3) |
| Juniper-R02 | code finding: Juniper-F05 | Juniper-F02 | B1 | platform-level administration obtained (b) (AR2) | server-side code execution (d) (AR1) |
| Juniper-R03 | code finding: Juniper-F05 | Juniper-F04 | B1 | platform-level administration obtained (a) (AR2) | server-side code execution (f) (AR1) |
| Juniper-R04 | config: non-default configuration or feature enabled (a) | Juniper-F01 | B1 | config grants position (AR5) | server-side code execution (a) (AR1) |
| Juniper-R05 | config: non-default configuration or feature enabled (b) | Juniper-F04 | B1 | config grants position (AR5) | server-side code execution (b) (AR1) |
| Juniper-R06 | code finding: Juniper-F06 | Juniper-F04 | B1 | secret or credential read (AR2) | server-side code execution (c) (AR3) |
| Juniper-R07 | victim: victim opens attacker-influenced content | Juniper-F03 | B2 | victim grants position (AR4) | arbitrary file write on the server (AR1) |
| Juniper-R08 | control_gap: missing rate or lockout control | Juniper-F04 | B1 | control_gap grants position (AR5) | server-side code execution (e) (AR1) |

## Kestrel: enterprise wiki and application platform (63 routes)

| Route | First step | Next finding | Band | Capability gained (ring) | Candidate outcome (ring) |
|---|---|---|---|---|---|
| Kestrel-R01 | victim: victim opens attacker-influenced content (privileged user) (t) | Kestrel-F33 | B1 | victim grants position (AR3) | server-side code execution (f) (AR1) |
| Kestrel-R02 | victim: victim opens attacker-influenced content (privileged user) (s) | Kestrel-F08 | B1 | victim grants position (AR3) | server-side code execution (g) (AR1) |
| Kestrel-R03 | victim: victim opens attacker-influenced content (privileged user) (b) | Kestrel-F48 | B1 | victim grants position (AR3) | server-side code execution (d) (AR1) |
| Kestrel-R04 | victim: victim opens attacker-influenced content (privileged user) (o) | Kestrel-F40 | B1 | victim grants position (AR3) | server-side code execution (m) (AR3) |
| Kestrel-R05 | victim: victim opens attacker-influenced content | Kestrel-F09 | B1 | victim grants position (AR4) | server-side code execution (n) (AR3) |
| Kestrel-R06 | config: non-default configuration or feature enabled (c) | Kestrel-F11 | B1 | config grants position (AR5) | arbitrary database access (a) (AR1) |
| Kestrel-R07 | config: non-default configuration or feature enabled (c) | Kestrel-F49 | B1 | config grants position (AR5) | arbitrary database access (b) (AR1) |
| Kestrel-R08 | config: non-default configuration or feature enabled (n) | Kestrel-F16 | B1 | config grants position (AR5) | server-side code execution (k) (AR1) |
| Kestrel-R09 | config: non-default configuration or feature enabled (o) | Kestrel-F42 | B2 | config grants position (AR5) | secret or credential disclosure (a) (AR2) |
| Kestrel-R10 | config: non-default configuration or feature enabled (h) | Kestrel-F18 | B1 | config grants position (AR5) | arbitrary file write on the server (AR1) |
| Kestrel-R11 | victim: victim opens attacker-influenced content (privileged user) (a) | Kestrel-F52 | B1 | victim grants position (AR3) | server-side code execution (b) (AR1) |
| Kestrel-R12 | victim: victim opens attacker-influenced content (privileged user) (a) | Kestrel-F56 | B1 | victim grants position (AR3) | administrator or account session taken over (a) (AR3) |
| Kestrel-R13 | victim: victim opens attacker-influenced content (privileged user) (a) | Kestrel-F15 | B1 | victim grants position (AR3) | administrator or account session taken over (a) (AR3) |
| Kestrel-R14 | victim: victim opens attacker-influenced content (privileged user) (a) | Kestrel-F44 | B1 | victim grants position (AR3) | administrator or account session taken over (a) (AR3) |
| Kestrel-R15 | victim: victim opens attacker-influenced content (privileged user) (v) | Kestrel-F17 | B1 | victim grants position (AR3) | server-side code execution (e) (AR1) |
| Kestrel-R16 | victim: victim opens attacker-influenced content (privileged user) (w) | Kestrel-F03 | B1 | victim grants position (AR3) | server-side code execution (l) (AR1) |
| Kestrel-R17 | config: non-default configuration or feature enabled (d) | Kestrel-F03 | B1 | config grants position (AR5) | server-side code execution (l) (AR1) |
| Kestrel-R18 | victim: victim opens attacker-influenced content (privileged user) (p) | Kestrel-F22 | B1 | victim grants position (AR3) | server-side code execution (c) (AR1) |
| Kestrel-R19 | victim: victim opens attacker-influenced content (privileged user) (i) | Kestrel-F01 | B1 | victim grants position (AR3) | administrator or account session taken over (a) (AR3) |
| Kestrel-R20 | code finding: Kestrel-F43 | Kestrel-F24 | B2 | identifier or metadata disclosed (e) (AR5) | data disclosure beyond the caller's permissions (c) (AR4) |
| Kestrel-R21 | config: non-default configuration or feature enabled (p) | Kestrel-F30 | B2 | config grants position (AR5) | administrator or account session taken over (b) (AR3) |
| Kestrel-R22 | config: non-default configuration or feature enabled (m) | Kestrel-F24 | B2 | config grants position (AR5) | data disclosure beyond the caller's permissions (d) (AR4) |
| Kestrel-R23 | config: non-default configuration or feature enabled (a) | Kestrel-F28 | B1 | config grants position (AR5) | server-side code execution (a) (AR1) |
| Kestrel-R24 | victim: victim opens attacker-influenced content (privileged user) (u) | Kestrel-F07 | B1 | victim grants position (AR3) | server-side code execution (i) (AR1) |
| Kestrel-R25 | victim: victim opens attacker-influenced content (privileged user) (j) | Kestrel-F25 | B1 | victim grants position (AR3) | server-side code execution (i) (AR1) |
| Kestrel-R26 | victim: victim opens attacker-influenced content (privileged user) (c) | Kestrel-F41 | B1 | victim grants position (AR3) | server-side code execution (i) (AR1) |
| Kestrel-R27 | victim: victim opens attacker-influenced content (privileged user) (f) | Kestrel-F02 | B1 | victim grants position (AR3) | server-side code execution (i) (AR1) |
| Kestrel-R28 | victim: victim opens attacker-influenced content (privileged user) (h) | Kestrel-F37 | B1 | victim grants position (AR3) | server-side code execution (i) (AR1) |
| Kestrel-R29 | victim: victim opens attacker-influenced content (privileged user) (g) | Kestrel-F14 | B1 | victim grants position (AR3) | server-side code execution (i) (AR1) |
| Kestrel-R30 | victim: victim opens attacker-influenced content (privileged user) (d) | Kestrel-F57 | B1 | victim grants position (AR3) | server-side code execution (i) (AR1) |
| Kestrel-R31 | victim: victim opens attacker-influenced content (privileged user) (q) | Kestrel-F59 | B1 | victim grants position (AR3) | server-side code execution (i) (AR1) |
| Kestrel-R32 | victim: victim opens attacker-influenced content (privileged user) (m) | Kestrel-F60 | B1 | victim grants position (AR3) | server-side code execution (i) (AR1) |
| Kestrel-R33 | victim: victim opens attacker-influenced content (privileged user) (n) | Kestrel-F20 | B1 | victim grants position (AR3) | server-side code execution (i) (AR1) |
| Kestrel-R34 | config: non-default configuration or feature enabled (i) | Kestrel-F50 | B1 | config grants position (AR5) | server-side code execution (h) (AR1) |
| Kestrel-R35 | config: non-default configuration or feature enabled (l) | Kestrel-F07 | B1 | config grants position (AR5) | server-side code execution (h) (AR1) |
| Kestrel-R36 | config: non-default configuration or feature enabled (f) | Kestrel-F57 | B1 | config grants position (AR5) | server-side code execution (h) (AR1) |
| Kestrel-R37 | config: non-default configuration or feature enabled (k) | Kestrel-F06 | B1 | config grants position (AR5) | server-side code execution (h) (AR1) |
| Kestrel-R38 | victim: victim opens attacker-influenced content (privileged user) (l) | Kestrel-F47 | B1 | victim grants position (AR3) | server-side code execution (p) (AR1) |
| Kestrel-R39 | victim: victim opens attacker-influenced content (privileged user) (k) | Kestrel-F55 | B1 | victim grants position (AR3) | server-side code execution (p) (AR1) |
| Kestrel-R40 | victim: victim opens attacker-influenced content (privileged user) (e) | Kestrel-F19 | B1 | victim grants position (AR3) | server-side code execution (p) (AR1) |
| Kestrel-R41 | victim: victim opens attacker-influenced content (privileged user) (e) | Kestrel-F05 | B1 | victim grants position (AR3) | server-side code execution (p) (AR1) |
| Kestrel-R42 | victim: victim opens attacker-influenced content (privileged user) (e) | Kestrel-F46 | B1 | victim grants position (AR3) | server-side code execution (p) (AR1) |
| Kestrel-R43 | victim: victim opens attacker-influenced content (privileged user) (e) | Kestrel-F54 | B1 | victim grants position (AR3) | server-side code execution (p) (AR1) |
| Kestrel-R44 | victim: victim opens attacker-influenced content (privileged user) (e) | Kestrel-F21 | B1 | victim grants position (AR3) | server-side code execution (p) (AR1) |
| Kestrel-R45 | victim: victim opens attacker-influenced content (privileged user) (e) | Kestrel-F45 | B1 | victim grants position (AR3) | server-side code execution (p) (AR1) |
| Kestrel-R46 | victim: victim opens attacker-influenced content (privileged user) (e) | Kestrel-F26 | B1 | victim grants position (AR3) | server-side code execution (p) (AR1) |
| Kestrel-R47 | config: non-default configuration or feature enabled (g) | Kestrel-F23 | B2 | config grants position (AR5) | data disclosure beyond the caller's permissions (a) (AR4) |
| Kestrel-R48 | config: non-default configuration or feature enabled (j) | Kestrel-F29 | B1 | config grants position (AR5) | secret or credential disclosure (b) (AR2) |
| Kestrel-R49 | config: non-default configuration or feature enabled (b) | Kestrel-F38 | B1 | config grants position (AR5) | server-side code execution (h) (AR1) |
| Kestrel-R50 | code finding: Kestrel-F12 | Kestrel-F58 | B2 | identifier or metadata disclosed (a) (AR5) | data disclosure beyond the caller's permissions (b) (AR4) |
| Kestrel-R51 | code finding: Kestrel-F43 | Kestrel-F58 | B2 | identifier or metadata disclosed (d) (AR5) | data disclosure beyond the caller's permissions (b) (AR4) |
| Kestrel-R52 | code finding: Kestrel-F10 | Kestrel-F58 | B2 | identifier or metadata disclosed (c) (AR5) | data disclosure beyond the caller's permissions (b) (AR4) |
| Kestrel-R53 | code finding: Kestrel-F32 | Kestrel-F58 | B2 | identifier or metadata disclosed (b) (AR5) | data disclosure beyond the caller's permissions (b) (AR4) |
| Kestrel-R54 | config: non-default configuration or feature enabled (e) | Kestrel-F51 | B1 | config grants position (AR5) | server-side code execution (j) (AR1) |
| Kestrel-R55 | code finding: Kestrel-F04 | Kestrel-F51 | B1 | administrator or staff session obtained (AR3) | server-side code execution (h) (AR1) |
| Kestrel-R56 | victim: victim opens attacker-influenced content (privileged user) (r) | Kestrel-F36 | B1 | victim grants position (AR3) | server-side code execution (h) (AR1) |
| Kestrel-R57 | code finding: Kestrel-F34 | Kestrel-F36 | B1 | administrator session obtained through an indirect route (AR3) | server-side code execution (h) (AR1) |
| Kestrel-R58 | victim: victim opens attacker-influenced content (privileged user) (x) | Kestrel-F13 | B1 | victim grants position (AR3) | server-side code execution (o) (AR1) |
| Kestrel-R59 | victim: victim opens attacker-influenced content (privileged user) (x) | Kestrel-F34 | B1 | victim grants position (AR3) | server-side code execution (o) (AR1) |
| Kestrel-R60 | victim: victim opens attacker-influenced content (privileged user) (x) | Kestrel-F35 | B1 | victim grants position (AR3) | server-side code execution (o) (AR1) |
| Kestrel-R61 | victim: victim opens attacker-influenced content (privileged user) (x) | Kestrel-F39 | B1 | victim grants position (AR3) | server-side code execution (o) (AR1) |
| Kestrel-R62 | code finding: Kestrel-F27 | Kestrel-F53 | B1 | identifier or metadata disclosed (f) (AR5) | administrator or account session taken over (d) (AR3) |
| Kestrel-R63 | code finding: Kestrel-F27 | Kestrel-F31 | B1 | stored credential readable (AR4) | administrator or account session taken over (c) (AR3) |

## Lumen: web-interface toolkit for machine-learning demos (5 routes)

| Route | First step | Next finding | Band | Capability gained (ring) | Candidate outcome (ring) |
|---|---|---|---|---|---|
| Lumen-R01 | victim: victim opens attacker-influenced content | Lumen-F01 | B2 | victim grants position (AR4) | secret or credential disclosure (c) (AR3) |
| Lumen-R02 | control_gap: missing rate or lockout control | Lumen-F04 | B2 | control_gap grants position (AR5) | secret or credential disclosure (b) (AR3) |
| Lumen-R03 | config: non-default configuration or feature enabled | Lumen-F03 | B2 | config grants position (AR5) | trust or integrity compromise of a shared component (AR2) |
| Lumen-R04 | config: non-default configuration or feature enabled | Lumen-F03 | B2 | config grants position (AR5) | secret or credential disclosure (a) (AR2) |
| Lumen-R05 | config: non-default configuration or feature enabled | Lumen-F02 | B1 | config grants position (AR5) | server-side code execution (AR1) |

## Marble: build-automation server (8 routes)

| Route | First step | Next finding | Band | Capability gained (ring) | Candidate outcome (ring) |
|---|---|---|---|---|---|
| Marble-R01 | victim: victim opens attacker-influenced content (privileged user) | Marble-F04 | B1 | victim grants position (AR3) | administrator or account session taken over (d) (AR3) |
| Marble-R02 | victim: victim opens attacker-influenced content (a) | Marble-F07 | B1 | victim grants position (AR4) | administrator or account session taken over (c) (AR3) |
| Marble-R03 | victim: victim opens attacker-influenced content (c) | Marble-F03 | B1 | victim grants position (AR4) | administrator or account session taken over (b) (AR3) |
| Marble-R04 | victim: victim opens attacker-influenced content (b) | Marble-F02 | B1 | victim grants position (AR4) | administrator or account session taken over (b) (AR3) |
| Marble-R05 | config: non-default configuration or feature enabled (a) | Marble-F01 | B2 | config grants position (AR5) | secret or credential disclosure (a) (AR2) |
| Marble-R06 | code finding: Marble-F06 | Marble-F01 | B2 | secret or credential read (a) (AR2) | secret or credential disclosure (b) (AR2) |
| Marble-R07 | config: non-default configuration or feature enabled (b) | Marble-F05 | B1 | config grants position (AR5) | administrator or account session taken over (a) (AR3) |
| Marble-R08 | code finding: Marble-F06 | Marble-F05 | B1 | secret or credential read (b) (AR2) | administrator or account session taken over (e) (AR3) |

## Nimbus: visual builder for language-model workflows (9 routes)

| Route | First step | Next finding | Band | Capability gained (ring) | Candidate outcome (ring) |
|---|---|---|---|---|---|
| Nimbus-R01 | code finding: Nimbus-F11 | Nimbus-F02 | B1 | identifier or metadata disclosed (b) (AR5) | secret or credential disclosure (d) (AR2) |
| Nimbus-R02 | code finding: Nimbus-F13 | Nimbus-F06 | B2 | identifier or metadata disclosed (d) (AR5) | secret or credential disclosure (a) (AR2) |
| Nimbus-R03 | code finding: Nimbus-F07 | Nimbus-F04 | B1 | identifier or metadata disclosed (a) (AR5) | server-side code execution (a) (AR1) |
| Nimbus-R04 | code finding: Nimbus-F11 | Nimbus-F03 | B2 | identifier or metadata disclosed (c) (AR5) | secret or credential disclosure (b) (AR2) |
| Nimbus-R05 | code finding: Nimbus-F14 | Nimbus-F01 | B1 | identifier or metadata disclosed (e) (AR5) | administrator or account session taken over (AR3) |
| Nimbus-R06 | code finding: Nimbus-F10 | Nimbus-F09 | B1 | attacker-controlled data written (AR4) | server-side code execution (c) (AR1) |
| Nimbus-R07 | code finding: Nimbus-F05 | Nimbus-F15 | B1 | identifier or metadata disclosed (f) (AR5) | server-side code execution (b) (AR1) |
| Nimbus-R08 | code finding: Nimbus-F16 | Nimbus-F12 | B2 | standard-user account or session obtained (AR4) | secret or credential disclosure (c) (AR2) |
| Nimbus-R09 | code finding: Nimbus-F08 | Nimbus-F15 | B1 | administrator session obtained through an indirect route (AR3) | server-side code execution (b) (AR1) |

## Onyx: low-code builder for internal tools (11 routes)

| Route | First step | Next finding | Band | Capability gained (ring) | Candidate outcome (ring) |
|---|---|---|---|---|---|
| Onyx-R01 | code finding: Onyx-F05 | Onyx-F01 | B1 | identifier or metadata disclosed (a) (AR5) | administrator or account session taken over (d) (AR3) |
| Onyx-R02 | config: non-default configuration or feature enabled | Onyx-F07 | B1 | config grants position (AR5) | administrator or account session taken over (b) (AR3) |
| Onyx-R03 | config: non-default configuration or feature enabled | Onyx-F10 | B2 | config grants position (AR5) | trust or integrity compromise of a shared component (a) (AR2) |
| Onyx-R04 | code finding: Onyx-F01 | Onyx-F10 | B2 | standard-user account or session obtained (AR4) | trust or integrity compromise of a shared component (b) (AR2) |
| Onyx-R05 | code finding: Onyx-F12 | Onyx-F15 | B2 | attacker-controlled data written (AR4) | arbitrary database access (AR1) |
| Onyx-R06 | code finding: Onyx-F02 | Onyx-F08 | B1 | administrator or staff session obtained (AR3) | protected outcome reached (b) (AR3) |
| Onyx-R07 | code finding: Onyx-F04 | Onyx-F14 | B1 | session cookie readable by script (AR4) | administrator or account session taken over (c) (AR3) |
| Onyx-R08 | code finding: Onyx-F04 | Onyx-F13 | B2 | session cookie readable by script (AR4) | protected outcome reached (a) (AR3) |
| Onyx-R09 | code finding: Onyx-F11 | Onyx-F14 | B2 | cross-site request protection bypassed (AR4) | administrator or account session taken over (a) (AR4) |
| Onyx-R10 | code finding: Onyx-F05 | Onyx-F09 | B2 | identifier or metadata disclosed (b) (AR5) | data disclosure beyond the caller's permissions (b) (AR2) |
| Onyx-R11 | code finding: Onyx-F03 | Onyx-F06 | B1 | secret or credential read (AR2) | data disclosure beyond the caller's permissions (a) (AR1) |
