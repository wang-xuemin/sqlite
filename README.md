# GORM Sqlite Driver

## Based on gorm.io/driver/sqlite v1.4.4

![CI](https://github.com.com/go-gorm/sqlite/workflows/CI/badge.svg)

## USAGE

```go
import (
  "github.com/wang-xuemin/sqlite"
  "github.com/wang-xuemin/gorm"
)

// github.com.com/mattn/go-sqlite3
db, err := gorm.Open(sqlite.Open("gorm.db"), &gorm.Config{})
```

Checkout [https://gorm.io](https://gorm.io) for details.

### Pure go Sqlite Driver

checkout [https://github.com.com/glebarez/sqlite](https://github.com.com/glebarez/sqlite) for details

```go
import (
  "github.com.com/glebarez/sqlite"
  "github.com/wang-xuemin/gorm"
)

db, err := gorm.Open(sqlite.Open("gorm.db"), &gorm.Config{})
```
