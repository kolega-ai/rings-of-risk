# Access Ring classification (anonymised)

How capabilities, outcomes and enabling steps were assigned to Access Rings. Each row is a generic label, with the number of route records assigned to each ring. A label that appears in more than one ring was split by a reviewer on the underlying detail; those are the judgement calls.

## Capability

| Label | AR1 | AR2 | AR3 | AR4 | AR5 |
|---|---:|---:|---:|---:|---:|
| administrator or staff session obtained |  |  | 9 |  |  |
| administrator session obtained through an indirect route |  |  | 45 |  |  |
| another user's credential reused |  |  |  | 1 |  |
| attacker-controlled data written |  |  |  | 5 |  |
| client-management authority obtained |  | 1 |  |  |  |
| cross-site request protection bypassed |  |  |  | 1 |  |
| data readable beyond the caller's permissions |  |  |  | 2 |  |
| identifier or metadata disclosed |  |  |  |  | 29 |
| intermediate capability obtained |  |  |  | 1 |  |
| platform-level administration obtained |  | 5 |  |  |  |
| privileged permission granted |  | 1 |  |  |  |
| secret or credential read |  | 12 |  |  |  |
| session cookie readable by script |  |  |  | 2 |  |
| standard-user account or session obtained |  |  |  | 8 |  |
| stored credential readable |  |  |  | 1 |  |

## Outcome

| Label | AR1 | AR2 | AR3 | AR4 | AR5 |
|---|---:|---:|---:|---:|---:|
| administrator or account session taken over |  |  | 37 | 3 |  |
| arbitrary database access | 5 | 1 |  |  |  |
| arbitrary file write on the server | 3 | 2 |  |  |  |
| data disclosure beyond the caller's permissions | 1 | 3 |  | 13 |  |
| platform-level administration taken over |  | 28 | 1 |  |  |
| protected outcome reached |  | 1 | 2 |  |  |
| secret or credential disclosure |  | 14 | 4 |  |  |
| server-side code execution | 102 | 4 | 5 |  |  |
| trust or integrity compromise of a shared component |  | 7 |  |  |  |
| unauthorised modification or deletion |  | 2 | 3 | 1 |  |
| write access as any user | 4 |  |  |  |  |

## Enabling step

| Label | AR1 | AR2 | AR3 | AR4 | AR5 |
|---|---:|---:|---:|---:|---:|
| credential, token or account obtained (phishing, issuance or reuse) |  |  |  | 19 |  |
| missing rate or lockout control |  |  |  |  | 3 |
| non-default configuration or feature enabled |  |  |  |  | 30 |
| open registration or permissive default |  |  |  | 2 |  |
| privileged credential or token obtained |  |  | 2 |  |  |
| publicly exposed endpoint or workflow |  |  |  |  | 5 |
| untrusted artifact selected for processing |  |  |  |  | 10 |
| untrusted input reaches a command |  |  |  |  | 1 |
| victim opens attacker-influenced content |  |  |  | 11 |  |
| victim opens attacker-influenced content (privileged user) |  |  | 40 |  |  |
