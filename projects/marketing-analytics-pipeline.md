# Marketing Analytics Pipeline

An ETL pipeline and warehouse model that unifies ad performance from six platforms in Google BigQuery for Power BI dashboards.

**Status:** delivered · **Repo:** private

## What it does

Pulls daily ad metrics from Meta, TikTok, Google Ads, Snapchat, Apple Search Ads and Adjust, loads them into BigQuery, and exposes one unified view for reporting.

## Highlights

- Migration from a legacy SQL Server warehouse to serverless BigQuery, with compatibility views so existing dashboards kept working.
- Idempotent loads using date-range replacement, so reruns never duplicate data.
- One unified performance view plus a pre-aggregated rollup for fast DirectQuery.
- Validation scripts for KPIs, schemas and views; DAX measure and semantic-model guides.

## Technology

Python, Google BigQuery, SQL, Power BI and DAX, Cloud Build, Docker.

## Interested?

Source is private. Contact [@ramyfrdwan](https://github.com/ramyfrdwan).
