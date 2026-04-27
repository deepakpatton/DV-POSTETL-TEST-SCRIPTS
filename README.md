# DV-POSTETL-TEST-SCRIPTS

Demo validation scripts for DQV Post ETL GitHub-backed runs.

Files included:

- `testcase.xls` - legacy Excel-format demo script updated for Snowflake sample data
- `demo_snowflake_row_count.csv` - simple Snowflake source/target validation script for demo use
- `testcase_from_xls.csv` - CSV version generated from `testcase.xls`
- `testcase_from_xls.json` - JSON version generated from `testcase.xls`
- `demo_snowflake_fail.csv` - simple Snowflake fail demo with intentional mismatches
- `failcase.xls` - legacy Excel-format fail demo script
- `failcase_from_xls.csv` - CSV version generated from `failcase.xls`
- `failcase_from_xls.json` - JSON version generated from `failcase.xls`

Suggested GitHub demo settings:

- repo: `deepakpatton/DV-POSTETL-TEST-SCRIPTS`
- ref: `main`
- file path: `demo_snowflake_row_count.csv`, `testcase.xls`, `testcase_from_xls.csv`, `testcase_from_xls.json`, `demo_snowflake_fail.csv`, `failcase.xls`, `failcase_from_xls.csv`, or `failcase_from_xls.json`
