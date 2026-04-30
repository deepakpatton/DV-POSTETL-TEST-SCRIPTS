# Medallion Validation Scripts

These scripts are intended for DQV.AI validation runs against the Snowflake
Medallion flow in `MULTISTAGE_VALIDATION`.

Files:

- `claims_flow_suite.csv`
- `member_flow_suite.csv`
- `combined_suite.csv`

The combined suite validates:

- Raw to Gold audit reconciliation for enterprise claims
- Raw to Silver row-count reconciliation for enterprise claims
- Silver invalid claims count against Gold DQ summary
- Raw to Silver row-count reconciliation for member claims
- Silver to Gold serving reconciliation for member claims
