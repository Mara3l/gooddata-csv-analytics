# gooddata-csv-analytics

# How to analyze CSV data

Intro...

## Steps

- import csv to import_csv folder (seed)
- postgres:
    - local -> postgres_local docker compose
    - cloud -> noen.dev or other tools
- configure dbt ~/.dbt/profile.yaml

## Tips

### Connect to docker psotgres


```bash
$ psql -h localhost -U admin -d postgres
```