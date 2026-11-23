# Post-Market Surveillance Trend Review: Prismaflex CRRT (FDA MAUDE, May-Oct 2026)

Independent exercise on public data: a post-market surveillance review of adverse event reports for Prismaflex continuous renal replacement therapy (CRRT) sets and machines, covering trend analysis, serious-case review and reportability assessment under US and EU rules.

## Data
- Source: FDA MAUDE database, brand name "Prismaflex", Date Report Received 1 May 2026 to 31 Oct 2026, retrieved 21 Nov 2026.
- 487 reports (complete set: the search returned under MAUDE's 500-record cap with no truncation warning).
- 603 device problem codes across 29 problem types (reports with several codes split, one code per row).

## Method
1. Pareto analysis of device problem codes.
2. Monthly trend by event type (malfunction, injury, death).
3. Reporting lag: calendar days from event date to FDA receipt.
4. Review of all 20 death and injury narratives: what happened, whether a device problem was involved, patient outcome, possible duplicates.
5. Reportability assessment of each serious case against 21 CFR 803.3 and 803.50 (US) and EU MDR 2017/745 Article 2(65) and Article 87 (EU).

## Key findings
- 467 malfunctions, 16 injuries, 4 deaths.
- Fluid/Blood Leak is 57.2% of problem codes; leak, break and crack together are 76.6%.
- Monthly reports: 85, 90, 95, 92, 69, 56. The Sep-Oct fall is likely reporting lag (median 28 days from event to receipt; 38% over 30 days), not improvement.
- Device failure confirmed in 2 of 20 serious cases; 18 not evaluated or cause not determined.
- Main harm pattern: in 9 serious cases blood could not be returned after an alarm, leak or machine stop; a transfusion was reported in 8.
- 20 serious reports represent about 17 distinct events (duplicates across reporting sites).
- All 20 serious cases meet US and EU reporting thresholds: neither regime requires proof of causation. 4 deaths fall under the EU 10-day deadline; 16 under 15 days.

## Files
| File | Contents |
|---|---|
| `Prismaflex_MAUDE_PMS_Review_May-Oct2026.xlsx` | Data, Pareto, monthly trend, reporting lag, serious-case review and reportability assessment |
| `Prismaflex_MAUDE_PMS_Review_Summary.pdf` | Two-page written summary, escalation recommendations and limitations |

## Limitations
MAUDE gives counts, not rates (no denominator of devices in use). Reports are unverified and many devices were not evaluated. Duplicates exist, and recent months are incomplete. This is not a manufacturer investigation.

## References
- FDA MAUDE: https://www.accessdata.fda.gov/scripts/cdrh/cfdocs/cfmaude/search.cfm
- 21 CFR Part 803: https://www.ecfr.gov/current/title-21/chapter-I/subchapter-H/part-803
- EU MDR 2017/745: https://eur-lex.europa.eu/eli/reg/2017/745/oj
- MDCG 2023-3 (vigilance Q&A): https://health.ec.europa.eu/latest-updates/mdcg-2023-3-rev1-questions-and-answers-vigilance-terms-and-concepts-outlined-regulation-eu-2017745-2024-11-11_en
- FDA recall notice, Prismaflex and Oxiris sets: https://www.fda.gov/medical-devices/medical-device-recalls-and-early-alerts/dialysis-tubing-set-correction-vantive-updates-use-instructions-prismaflex-and-oxiris-sets
