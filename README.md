# Nuna
Sentinel to ADX migration.

## Standard Tables
```mermaid
graph LR
   sourcetable-->|namespace| hubtable
   hubtable-->_import
   _import-->|fn_table| table
```

1. [AzureActivity.kql](AzureActivity.kql)
2. [AADManagedIdentitySignInLogs.kql](AADManagedIdentitySignInLogs.kql)
