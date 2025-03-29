# AIRBNB
Data  Engineering Project


Commands to set up dbt project-
python -m venv venv  # Recreates venv
venv\Scripts\activate  # Activates venv
pip install --upgrade pip  # Updates pip
pip install dbt-snowflake==1.9.0  # Installs dbt-snowflake
dbt init dbtlearn
*ADD CREDENTIALS OF SNOWFLAKE
cd dbtlearn
dbt debug  # check connection to SNOWFLAKE
