FROM astrocrpublic.azurecr.io/runtime:3.0-2

RUN python -m venv dbt_venv && source dbt_venv/bin/activate && \
    pip install --no-cache-dir dbt-snowflake && deactivate