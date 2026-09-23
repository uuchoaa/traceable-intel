# traceable-intel

A preparatory study for the research project **"Dark Visions: um Modelo para Construção do Núcleo
Integrado de Segurança Cibernética do Estado de Pernambuco (NISC-PE)"**, written for the selection
of the professional master's programme in software engineering (MPES 2026.2) at CESAR School.

The study reads the NISC as a software-engineering problem, an integration model rather than a
security tool: an aggregator of open security information in which everything can be traced back.
Every fetch is recorded with its URL, date and sha256; feeds are normalised to STIX 2.1; signals go
down a ladder of deterministic rules, with no model deciding; and every step is an entry in a
hash-chained ledger. The author is a software engineer, not a security practitioner, and the study
claims no security experience.

The code is not published yet. This repository will show what the study decided and measured.

## Papers

Both papers declare each experiment in writing before its code, with the yes-or-no criterion fixed
in advance. Neither has been submitted to a venue.

- [Declare, Check, Derive: A Small Model Behind a Deterministic Judge, Measured on Screens](papers/declare-check-derive.pdf) (September 2026)
- [Retrieval Refuses, a Small Model Chooses: Measuring a Local Chooser for Agents Bounded by a Declared Catalog](papers/retrieval-refuses-a-small-model-chooses.pdf) (September 2026)
