# Reactive Relational Database Connectivity CI

This project contains the Concourse CI configuration for the R2DBC project.  Since the pipeline definitions stretches beyond a single repository, a separate project is required to manage it.

The status of each component of R2DBC is found in the following matrix:

| Job                | 1.0 Status |
| ------------------ | ---------- |
| `r2dbc-spi`        | [![r2dbc-spi](https://ci.spring.io/api/v1/teams/r2dbc/pipelines/r2dbc/jobs/r2dbc-spi/badge)](https://ci.spring.io/teams/r2dbc/pipelines/r2dbc/jobs/r2dbc-spi) |
| `r2dbc-mssql`      | [![r2dbc-mssql](https://ci.spring.io/api/v1/teams/r2dbc/pipelines/r2dbc/jobs/r2dbc-mssql/badge)](https://ci.spring.io/teams/r2dbc/pipelines/r2dbc/jobs/r2dbc-mssql) |
| `r2dbc-over-adba`  | [![r2dbc-over-adba](https://ci.spring.io/api/v1/teams/r2dbc/pipelines/r2dbc/jobs/r2dbc-over-adba/badge)](https://ci.spring.io/teams/r2dbc/pipelines/r2dbc/jobs/r2dbc-over-adba) |
| `r2dbc-h2`         | [![r2dbc-h2](https://ci.spring.io/api/v1/teams/r2dbc/pipelines/r2dbc/jobs/r2dbc-h2/badge)](https://ci.spring.io/teams/r2dbc/pipelines/r2dbc/jobs/r2dbc-h2) |
| `r2dbc-postgresql` | [![r2dbc-postgresql](https://ci.spring.io/api/v1/teams/r2dbc/pipelines/r2dbc/jobs/r2dbc-postgresql/badge)](https://ci.spring.io/teams/r2dbc/pipelines/r2dbc/jobs/r2dbc-postgresql) |
| `r2dbc-client`     | [![r2dbc-client](https://ci.spring.io/api/v1/teams/r2dbc/pipelines/r2dbc/jobs/r2dbc-client/badge)](https://ci.spring.io/teams/r2dbc/pipelines/r2dbc/jobs/r2dbc-client) |

## License
This project is released under version 2.0 of the [Apache License][l].

[l]: https://www.apache.org/licenses/LICENSE-2.0
