# Cross-Enterprise Sales Data Integration

This project contains a Databricks-based data engineering workflow for integrating FMCG sales data from parent and child company sources. It includes source CSV files, notebooks for setup and data processing, dashboard queries, and project architecture resources.

## Project structure

- `0_data/` - Full-load and incremental-load source data for the parent and child companies.
- `1_codes/1_setup/` - Catalog/schema setup, date table creation, and shared utilities.
- `1_codes/2_dimension_data_processing/` - Customer, product, and pricing data processing notebooks.
- `1_codes/3_fact_data_processing/` - Full and incremental fact data processing notebooks.
- `2_dashboarding/` - Dashboard query and exported dashboard PDF.
- `resources/` - Architecture diagram files.

## Usage

Import the notebooks into a Databricks workspace, review and update any workspace-specific catalog or data paths, then run the setup and processing notebooks for the load you want to perform. The dashboard query and PDF are provided under `2_dashboarding/`.
