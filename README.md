# A Model for Optimizing Electronic Toll Collection Systems

## Package Status

This package is ready for public GitHub upload review. The earlier `NOTHING-TO-DO` classification was stale: direct inspection of the PATH-ETC folder found the electronic toll collection model workbooks, Carquinez Bridge input workbook, and the model user manual that match the published paper.

## Bibliographic Information

- Row ID: `paper-2003-04`
- Citation: Levinson, David M., and Elva Chang. (2003). A Model for Optimizing Electronic Toll Collection Systems. Transportation Research Part A: Policy and Practice 37(4):293-314. https://doi.org/10.1016/S0965-8564(02)00017-4
- DOI: https://doi.org/10.1016/S0965-8564(02)00017-4

## What This Package Contains

- `paper/`: local reference copy of the published paper used for audit validation. Treat this as a review convenience unless publication rights are separately cleared.
- `data/original/` and `data/modernized/`: the Carquinez Bridge traffic-count workbook, preserved as original `.xls` and LibreOffice `.xlsx`.
- `code/original/`: original Excel 97-era model, example, payment-choice, enumeration, and ETC lane/welfare model workbooks.
- `code/modernized/`: LibreOffice `.xlsx` conversions for easier inspection.
- `code/extracted_vba/`: extracted VBA/XLM text for workbooks with embedded macro streams.
- `documentation/`: the user manual for the computerized ETC benefit-cost model.
- `metadata/`: file map, workbook sheet/formula summary, macro summary, and source-boundary decisions.

## Evidence Basis

The paper states that the welfare model is applied to the Carquinez Bridge, uses base-year traffic data and ETC share assumptions, and notes that the software for solving the model is documented in Chang et al. (1998). The staged PATH-ETC workbooks contain matching Carquinez traffic counts, ETC share/logit workbooks, and the model sheets for lane allocation, delay, agency costs, time value, fuel, emissions, and summary results.

## Exclusions

Draft/report documents, comments, and duplicate/parallel workbook variants in the source folder were not copied. See `metadata/SOURCE_BOUNDARY_DECISIONS.csv` for the explicit inclusion/exclusion boundary.

## Current Review Notes

- No human-subject, personal-data, or controlled-access raw dataset issue was found for this package.
- Original `.xls` workbooks are preserved because they are the authoritative legacy files.
- Modern `.xlsx` conversions are provided for inspection; they should not replace the originals as provenance artifacts.
- Add an explicit repository license before public release if the repository is created as a standalone public package.

<!-- package-hardening-status:start -->
## Package Hardening Status

Generated: 2026-05-21 20:04:48 AEST

- Pipeline: `READY-TO-UPLOAD/PUBLIC`
- Sidecars added/updated: `PACKAGE_STATUS.md`, `PACKAGE_MANIFEST.csv`, `LICENSE_STATUS.md`.
- Paper reference copies are for local audit convenience and are not public-upload assets without rights review.
- Final GitHub upload should use the manifest include statuses and the license-status note.
<!-- package-hardening-status:end -->
