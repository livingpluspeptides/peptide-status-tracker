# FDA Peptide Status Tracker and Warning Letters

FDA approval, compounding, shortage, WADA and DEA status for peptides, plus FDA warning letters that name them. Published by Living+ Peptides (https://livingpluspeptides.com), an education-only reference site. Updated 2026-11-08.

## Files

- `peptide-status-tracker.csv` (26 rows): one row per peptide. FDA approval, 503A and 503B compounding status, FDA drug shortage status, WADA status, DEA schedule, notes, the sources checked and the date each row was last verified. Same data as the Status Tracker page: https://livingpluspeptides.com/regulation/tracker/
- `fda-peptide-warning-letters.csv` (173 rows): one row per FDA warning letter whose text names a peptide in the tracker. Letter date, posted date, firm, FDA's subject line, issuing office, the peptides named, and the link to FDA's copy. Same list as https://livingpluspeptides.com/regulation/warning-letters/

## How it is made

The tracker is checked against primary sources (FDA, the Federal Register, WADA and DEA) and every row carries its sources and a last verified date. The warning letter list is built from FDA's warning letter search: a letter is listed only when FDA's matching text contains the peptide's name. Firm names, dates and subject lines are copied from FDA. A warning letter is FDA's notice that it believes a firm broke the law; it is not a court ruling.

This is education only, not medical or legal advice. Statuses change; check the linked sources before relying on a row.

## License and credit

CC BY 4.0. Please credit "Living+ Peptides" and link to https://livingpluspeptides.com/regulation/tracker/

Corrections: https://livingpluspeptides.com/corrections/
