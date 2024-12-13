## Rainy ETL 

This project is a simple ETL pipeline that extracts data from a public API (gcp-public-data-arco-era5/raw/date-variable-single_level/2022), transforms it, and loads it into a parquet file. 

1. Process pull the data from the API
a. 
```bash
curl https://sdk.cloud.google.com | bash
exec -l $SHELL
gcloud init
```

```bash
gcloud auth login
```

```bash