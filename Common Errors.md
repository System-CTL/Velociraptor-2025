# Login Error After Fresh Installation - Admin Account - Velociraptor Login Issue
**OS** : *LINUX - DEBIAN* <br />
**Error logs**:
```sql
[INFO] 2025-10-17T18:45:35Z Unknown username {"details":{"remote":"127.0.0.1:55356","status":401},"operation":"Unknown username","principal":"admin"}
```
| Solution | Description |
| --- | --- |
| `User need to add` | Add admin user into data-store, run below command and set the password for admin  |
| `SOLUTION COMMAND` | sudo velociraptor --config server.config.yaml user add admin --role administrator  |



