SF create DB:
create or replace database DEMO_AF_DBT_1;
create or replace schema DEMO_AF_DBT_1.AF_DBT_SF_1;

Config DBT:
Account integrations - Git

Credentials:
DEMO_AF_DBT_SF_1 - Snowflake
Account: SWTWMVG-EO50959
Database: DEMO_AF_DBT_1
Warehouse: COMPUTE_WH
Schema: dbt_krzpiszcz

Environment:
DEV
Deployment connection:
Account: SWTWMVG-EO50959
DB: DEMO_AF_DBT_1
Warehouse: COMPUTE_WH

Deployment credentials:
krispik1, pwd, schema: AF_DBT_SF_1

Jobs:
ie.: dbt seed
