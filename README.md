# dbt-cratedb

## About

[CrateDB] adapter plugin for [dbt] (data build tool).

> CrateDB is a distributed SQL database that makes it simple to store and
> analyze massive amounts of data in real-time. Built on top of Lucene.

> dbt enables data analysts and engineers to transform their data using the
> same practices that software engineers use to build applications.


## Supported software versions
- CrateDB 4.x.x
- dbt 0.20


## Setup
Install package in development mode.
```shell
git clone https://github.com/crate-workbench/dbt-cratedb
cd dbt-cratedb
python3 -m venv .venv
source .venv/bin/activate
pip install --verbose --prefer-binary --editable=.
```


## Handbook

### Authentication

```yaml
type: cratedbadapter
threads: 1
host: 20.94.130.194
port: 5432
user: crate
password: ""
database: ""
schema: dbt_dev
```


## Note

This repository includes the source code of the [dbt-cratedb] package on PyPI,
conceived by [Julio Sánchez Jiménez].


[CrateDB]: https://github.com/crate/crate 
[dbt-cratedb]: https://pypi.org/project/dbt-cratedb/
[dbt]: https://github.com/dbt-labs/dbt-core
[Julio Sánchez Jiménez]: https://github.com/jsnchzjmnz
