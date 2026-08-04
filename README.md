# PostgreSQL (postgres)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

PostgreSQL is a powerful, open-source object-relational database system with over 35 years of active development that has earned a strong reputation for reliability, feature robustness, and performance. It supports advanced SQL features, JSON, full-text search, custom data types, extensions, and transactional DDL. PostgreSQL does not expose a native HTTP REST API; client applications connect via the libpq C client library, JDBC, ODBC, or one of dozens of language-specific drivers using the PostgreSQL wire protocol (default port 5432).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/postgres/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/postgres/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Database
- Relational Database
- SQL
- Open Source
- PostgreSQL
- Object-Relational
- Data Storage

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### PostgreSQL Wire Protocol

The PostgreSQL frontend/backend protocol is the low-level message-based protocol used by all client drivers (libpq, JDBC, ODBC, psycopg, pgx, node-postgres, etc.) to communicate with the PostgreSQL server over TCP/IP or Unix sockets. Authentication supports password, SCRAM-SHA-256, MD5, GSSAPI, SSPI, certificate, LDAP, and other pluggable methods.

- **Human URL:** [https://www.postgresql.org/docs/current/protocol.html](https://www.postgresql.org/docs/current/protocol.html)
- **Base URL:** `postgresql://hostname:5432`

#### Tags

- Database
- Wire Protocol
- SQL
- Connection Protocol

#### Properties

- [Documentation](https://www.postgresql.org/docs/current/protocol.html)
- [Specification](https://www.postgresql.org/docs/current/protocol-message-formats.html)
- [Graph Q L](graphql/postgres-graphql.md)

### libpq C Client Library

libpq is the official C application programmer's interface to PostgreSQL and the underlying library used by most other PostgreSQL client interfaces. It provides connection management, query execution, prepared statements, COPY support, asynchronous operations, and SSL/TLS.

- **Human URL:** [https://www.postgresql.org/docs/current/libpq.html](https://www.postgresql.org/docs/current/libpq.html)
- **Base URL:** `postgresql://hostname:5432`

#### Tags

- Database
- C Library
- Client Library
- libpq

#### Properties

- [Documentation](https://www.postgresql.org/docs/current/libpq.html)

### PostgreSQL JDBC Driver

The official Type 4 JDBC driver for PostgreSQL enables Java applications to connect to PostgreSQL using the standard JDBC API. It supports connection pooling, prepared statements, batched updates, LOBs, COPY, and SSL connections.

- **Human URL:** [https://jdbc.postgresql.org/documentation/](https://jdbc.postgresql.org/documentation/)
- **Base URL:** `jdbc:postgresql://hostname:5432/database`

#### Tags

- Database
- JDBC
- Java
- Driver

#### Properties

- [Documentation](https://jdbc.postgresql.org/documentation/)
- [Git Hub](https://github.com/pgjdbc/pgjdbc)

### PostgreSQL ODBC Driver (psqlODBC)

The official ODBC driver for PostgreSQL providing Open Database Connectivity for Windows, Linux, and macOS applications including Microsoft Office, Tableau, Power BI, and other BI/ETL tools that consume ODBC data sources.

- **Human URL:** [https://odbc.postgresql.org/](https://odbc.postgresql.org/)
- **Base URL:** `Driver={PostgreSQL};Server=hostname;Port=5432;Database=mydb`

#### Tags

- Database
- ODBC
- Driver
- BI Integration

#### Properties

- [Documentation](https://odbc.postgresql.org/docs/)
- [Git Hub](https://github.com/postgresql-interfaces/psqlodbc)

## Common Properties

- [Website](https://www.postgresql.org)
- [Documentation](https://www.postgresql.org/docs/)
- [Download](https://www.postgresql.org/download/)
- [Source  Code](https://git.postgresql.org/gitweb/?p=postgresql.git)
- [Git Hub  Mirror](https://github.com/postgres/postgres)
- [Mailing  Lists](https://www.postgresql.org/list/)
- [Community](https://www.postgresql.org/community/)
- [License](https://www.postgresql.org/about/licence/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
