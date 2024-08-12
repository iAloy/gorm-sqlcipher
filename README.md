# GORM Sqlite Driver

![CI](https://github.com/iAloy/gorm-sqlcipher/workflows/CI/badge.svg)

## USAGE

```go
import (
  sqlcipher "github.com/iAloy/gorm-sqlcipher"
  "gorm.io/gorm"
)

// github.com/mutecomm/go-sqlcipher
db, err := gorm.Open(sqlcipher.Open("gorm.db"), &gorm.Config{})
```

Checkout [https://gorm.io](https://gorm.io) for details.

### Pure go Sqlite Driver

checkout [https://github.com/glebarez/sqlite](https://github.com/glebarez/sqlite) for details

```go
import (
  "github.com/glebarez/sqlite"
  "gorm.io/gorm"
)

db, err := gorm.Open(sqlite.Open("gorm.db"), &gorm.Config{})
```
