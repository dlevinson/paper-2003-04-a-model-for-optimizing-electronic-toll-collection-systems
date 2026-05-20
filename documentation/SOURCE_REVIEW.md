# Source Review

Generated: 2026-05-17 00:26:45 AEST

## Paper Evidence

Levinson, David M., and Elva Chang. (2003). A Model for Optimizing Electronic Toll Collection Systems. Transportation Research Part A: Policy and Practice 37(4):293-314. https://doi.org/10.1016/S0965-8564(02)00017-4

The paper develops a dynamic payment-choice and welfare optimization model for electronic toll collection and applies it to the Carquinez Bridge. The paper text explicitly states that data from the Carquinez Bridge are used for the case application, and that the software for solving the model is documented in Chang et al. (1998).

## Local Asset Evidence

The PATH-ETC folder contains the relevant model artifacts:

- `CarquinToll.xls` contains Carquinez Bridge daily and monthly traffic counts.
- `market2.1.xls` contains model sheets named `Price`, `ETCLANE`, `Input-Start`, `Input-Detail`, `Results Summary`, `Results-Detail`, `Agency Costs Reduction`, `Delay`, `PY`, `Interest Gain`, `Time Value`, and `Fuel & Emission`.
- `logittest.xls` and `SampleEnumeration.xls` contain payment-choice/logit and sensitivity-enumeration workbooks.
- `AUTOMAT.XLS`, `Example.xls`, and `BC-ETC-UsersManual.pdf` document and preserve the base computerized benefit-cost model.

## Package Boundary

The package includes only the paper reference, data workbook, model/code workbooks, extracted macro text, the user manual, and metadata. Drafts, comments, letters, and duplicate/parallel variants were excluded.
