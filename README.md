# CREATE-A-STORAGE-ACCOUNT-IN-AZURE-USING-THE-CLI

## Create a storage account:

```
az storage account create \
 --name helloworld12345 \
 --resource-group resource-group-west \
 --location westus2
```

## Create a container:

```
az storage container create \
 --account-name helloworld12345 \
 --name images \
 --auth-mode login \
 --public-access container
 ```
