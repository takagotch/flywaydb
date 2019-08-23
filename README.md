### flywaydb
---
https://github.com/flyway/flyway

https://flywaydb.org/

```java
// flyway-core/src/main/java/org/flywaydb/core/api/executor/Migrationexcutor.java

public interface MigrationExecutor {
  void execute(Context context) throws SQLException;
  
  boolean canExecuteInTransaction();
}

```

```
```

```
```


