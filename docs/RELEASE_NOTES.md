# Release Notes

Below is the complete list of release notes for every version of ``pg_stat_monitor``.

## REL0_7_0_STABLE
### Improvements

[PG-153](https://jira.percona.com/browse/PG-153): Capture and record the application_name executing the query.

[PG-145](https://jira.percona.com/browse/PG-143): Add a new View/Query to show the actual Database name and Username.

[PG-110](https://jira.percona.com/browse/PG-110); Aggregate the number of warnings.

[PG-109](https://jira.percona.com/browse/PG-109): Log failed queries or queries with warning messages.

[PG-150](https://jira.percona.com/browse/PG-150): Differentiate different types of queries such as SELECT, UPDATE, INSERT or DELETE.

### Bugs Fixed

[PG-111](https://jira.percona.com/browse/PG-111) Show information for incomplete buckets.

[PG-112](https://jira.percona.com/browse/PG-112) Rename the column from “IP” to a more meaningful "client_ip".

[PG-148](https://jira.percona.com/browse/PG-148) Loss of query statistics/monitoring due to not enough “slots” available.

## v0.6.0
Initial Release.


## Master

### Improvements

[PG-156](https://jira.percona.com/browse/PG-156): Adding a placeholder replacement function for the prepared statement

