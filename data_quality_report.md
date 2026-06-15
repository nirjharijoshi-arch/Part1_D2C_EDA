# Data Quality Report

## Findings

### Missing Values
No major missing-value issues were identified in the modeling snapshot.

### Duplicates
Duplicate checks were performed across all datasets. No material duplicate issues were observed.

### Join Keys
customer_id is the primary key across datasets and supports joining.

### Leakage Risks
The churn_next_60d target must never be used as an input feature.

Snapshot-based features are safe because they are recorded on or before the snapshot date.

### Date Consistency
Snapshot date is consistently 2025-09-30 across customer-level modeling data.

## Recommendation

Maintain strict separation between features available at snapshot date and future churn outcomes.
