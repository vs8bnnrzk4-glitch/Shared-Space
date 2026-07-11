# Releases

A release manifest records governance state and hash-bound lineage.

Allowed states:

- `PROPOSED`
- `REVIEWING`
- `ACCEPTED`
- `ACTIVE`
- `SUPERSEDED`
- `BLOCKED`

A GitHub commit or merge does not create acceptance or activation. `ACCEPTED` requires the recorded bilateral governance predicates. `ACTIVE` requires a separate activation authority when activation is applicable.
