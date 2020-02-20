# mongodb-backup
# helm chart Kubernetes
`From https://github.com/aleicher/mongo-azure-backup`

| variable | description |
| ------ | ------ |
| MONGO_URI | mongo host URI |
| AZURE_SA | Azure Storage account name |
| AZURE_BLOB_CONTAINER | name of the azure storage blob container |
| AZURE_DESTINATION_KEY | azure storage account destination key |
| DB | name of mongo database to backup |
| MONGO_USERNAME | username for mongodb |
| MONGO_PASSWORD | password to authenticate against mongodb |
| MONGO_AUTH_DB | name of mongo authentication database |
