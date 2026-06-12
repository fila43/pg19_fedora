# postgresql19

PostgreSQL 19 for Fedora.

This package provides PostgreSQL 19 server and client programs,
along with the pgaudit extension as an integrated subpackage.

## Subpackages

- `postgresql19` - client programs
- `postgresql19-server` - server
- `postgresql19-contrib` - contrib extensions
- `postgresql19-server-devel` - development headers for extensions
- `postgresql19-docs` - documentation
- `postgresql19-upgrade` - upgrade support from PostgreSQL 18
- `postgresql19-upgrade-devel` - development support for upgrade
- `postgresql19-plperl` - PL/Perl procedural language
- `postgresql19-plpython3` - PL/Python3 procedural language
- `postgresql19-test` - test suite
- `postgresql19-static` - static libraries
- `postgresql19-private-libs` - private shared libraries
- `postgresql19-private-devel` - private development headers
- `postgresql19-test-rpm-macros` - RPM macros for build-time testing
- `postgresql19-pgaudit` - PostgreSQL Audit Extension

## Default stream

When built with `postgresql_default=1` (the default), package names
use the unversioned `postgresql-*` naming scheme, making this the
default PostgreSQL stream in the repository.

## Upgrade path

Supports in-place upgrade from PostgreSQL 18 only.
