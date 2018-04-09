[![pipeline status](https://gitlab.getweave.com/weave-lab/ops/odbc/badges/master/pipeline.svg)](https://gitlab.getweave.com/weave-lab/ops/odbc/commits/master)
[![coverage report](https://gitlab.getweave.com/weave-lab/ops/odbc/badges/master/coverage.svg)](https://gitlab.getweave.com/weave-lab/ops/odbc/commits/master)
odbc driver written in go. Implements database driver interface as used by standard database/sql package. It calls into odbc dll on Windows, and uses cgo (unixODBC) everywhere else.

To get started using odbc, have a look at the [wiki](../../wiki) pages.
