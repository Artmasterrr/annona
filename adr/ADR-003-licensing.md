# ADR-003: Licensing of the public repository

- **Status:** Accepted
- **Date:** 2026-10-20

## Context
Annona has two repositories. The public repository `annona` holds the
domain-neutral core and a civil scenario pack. The private repository holds the
military scenario pack. The public repository exists so that others can follow
the progress of the project (through regular posts on LinkedIn) and, later, so
that potential users and customers can run a demo.

## Decision
We license the public repository under the Apache License 2.0. It lets
customers, partners and laboratories use the work while the copyright stays
with the author. Its explicit patent grant makes it acceptable to corporate
legal teams.

## Consequences
- **Positive:** the project is visible; external reviews and analysis become possible.
- **Negative:** anyone can use the code, including commercially and in closed
  products, as long as they keep the attribution and licence notice.
- **Irreversible:** code already published under Apache 2.0 stays under it;
  a change of licence applies only to future versions.

## Alternatives considered
| Alternative | Why rejected |
|---|---|
| No licence | All rights reserved by default: nobody can legally use or run the code, which defeats the purpose of a public demo |
| AGPL-3.0 | Many companies forbid AGPL dependencies; it would limit adoption by employers and customers |
| BSL | Not an open-source licence; restricts production use until a change date and weakens trust in a showcase repository |