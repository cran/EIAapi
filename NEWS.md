# EIAapi 0.2.0

Bug fix:
Fixed issue with GET requests for non-hourly data with the `eia_backfill` function:
- Added the `frequency` and `data` arguments to aligned with the `eia_get` function arguments
- Modified how `Date` objects are processed

# EIAapi 0.1.2

* Added a new function, `eia_backfill` to handle large data query from the API
* Fixed issue with the `eia_get` function - `curl` commands failed to send query with brackets 
* Added new vignette with example of the `eia_backfill` function usage

# EIAapi 0.1.1

* Modified the `eia_get` function argument - rename the `api_url` argument to `api_path`, and dropping the end-point (`https://api.eia.gov/v2/`) from the query
* Added new function - `eia_metadata` to query metadata information from the API
* Added new vignettes - introduction the EIA API

# EIAapi 0.1.0

* Added the `eia_get` function to query data from EIA API
* Added a `NEWS.md` file to track changes to the package
