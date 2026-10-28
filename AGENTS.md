## General Instructions

- When you write code, always first implement a minimal working example. Only do the most important error validation (like in try-catch statements), no need to consider every small edge case. Prefer concise, readable code over best robustness.

## Data

- Never access any data in the `/data` folder.
- The CSV files in the `/data` folder have the following structure: `Abschlussdatum;Abschlusszeit;Buchungsdatum;Valutadatum;Währung;Belastung;Gutschrift;Einzelbetrag;Saldo;Transaktions-Nr.;Beschreibung1;Beschreibung2;Beschreibung3;Fussnoten;`
- The code you generate can read and process the data from the `/data` folder, but you as the LLM coding agent are not allowed.