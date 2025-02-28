## ADX Tables Imported
- Queries

### LAW Table Export Mapping

| Unique Tables                 | Source Connector   | Standard | Migration Method | Rule Name                   | Destination    | Namespace/Hubname                              |
|-------------------------------|--------------------|----------|------------------|-----------------------------|----------------|------------------------------------------------|
| AADManagedIdentitySignInLogs  | Entra ID Connector | yes      | Export           | AADManagedIdentitySignInLogs | Syslog         | nc-cg-p-adx-seh/am-aadmanagedidentitysigninlogs |
| AzureActivity                 | Azure Activity     | yes      | Export           | AzureActivity               | AzureActivity  | nc-cg-p-adx-seh/am-azureactivity                |
| syslog                        | AMA                | yes      | Export           | Syslog                      | Syslog         | nc-cg-p-adx-seh/am-syslog                       |
