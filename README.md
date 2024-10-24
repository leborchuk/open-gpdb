----------------------------------------------------------------------

![Greenplum](logo-greenplum.png)

We've forked here the original GPDB repository after Greenplum became a closed-source project. And continue to make it production-ready.

The main goal is:
- to fix bugs, especially those leading to core dump master/segment processes;
- to adopt existing GP/PG extensions for the latest stable GP version;
- backporting stable features from other projects (Postgres > 9.4, Cloudberry);
- creating a new stable version (7.X) by fixing everything we stumble upon.

The current last stable version is 6X. It's used by major of our clients and partners. 

If you want to try it right away - https://yandex.cloud/en/services/managed-greenplum 

## Roadmap

## Build and try out

## Repositories

This is the main repository for Greenplum Database. Alongside this, there are several ecosystem repositories for the Cloudberry Database, including the website, extensions, connectors, adapters, and other utilities.

- [open-gpdb/yezzey](https://github.com/open-gpdb/yezzey): Extension to fast offload/download AO/AOCS data to/from S3.
- [open-gpdb/yproxy](https://github.com/open-gpdb/yproxy): GP <-> S3 proxy for schedule and limit requests rate from hot to S3
- [open-gpdb/pgaudit](https://github.com/open-gpdb/pgaudit): PGAudit extension for GP
- [open-gpdb/gp_relaccess_stats](https://github.com/open-gpdb/gp_relaccess_stats): Greenplum extension to collect stats on table operations like SELECT/UPDATE/INSERT/DELETE/TRUNCATE
- [open-gpdb/gp_relsizes_stats](https://github.com/open-gpdb/gp_relsizes_stats): Greenplum extension to collect statistics on the distribution of memory occupied by tables and files on segment hosts.
- [open-gpdb/pxf](https://github.com/open-gpdb/pxf): Platform Extension Framework (PXF) for Greenplum Database.

### Other projects we`d like to recommend

- [wal-g](https://github.com/wal-g/wal-g) Database physical backup/restore tool
- [cloudberry](https://github.com/cloudberrydb/cloudberrydb) New MPP Database compatible with Greenplum Database
- [gpdb](https://github.com/greenplum-db) Archived original Greenplum Database

## Community & Support 

## Contribution

## Acknowledgment
Thanks to PostgreSQL, Greenplum Database and other great open source projects to make our project has a sound foundation.

## License
Our patches are released under the Apache License, Version 2.0. Some components may have [PostgreSQL License](https://www.postgresql.org/about/licence/) if it is explicity mentioned in the NOTICE file. 
